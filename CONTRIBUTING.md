# Contributing

To contribute to this project please either start a pull request or an issue with the details of the information that you want added.

## Pull Request Process

1. Beautify your `.md` file using [Tidy Markdown](https://github.com/slang800/tidy-markdown)
2. Verify that your Markdown has been correctly formatted by rendering your `.md` with [Grip](https://github.com/joeyespo/grip)
3. If you have edited the LaTeX file make sure to run `make realclean`
4. You may merge the pull request in once you have the sign-off of at least one maintainer. If you do not have permission to make the merge, request the approving maintainer to merge it for you.

## Areas of Requested Help

1. Adding content across experiments
2. An additional volunteer maintainer
3. Restructuring the layout design to be more readable

## FAQ

### There is a subject not listed that I think should be. How do I get it added to the listing?

If there is content missing that you'd like added please create an issue with as much description as possible (and maybe some examples). A maintainer will add the content once it has been approved. Alternatively, feel free branch the repository and add the content you want and then create a pull request.

### How do I add a paper?

All paper additions should be submitted as a single pull request on a source branch that isn't `master`.

1. Find the paper on [INSPIRE](https://inspirehep.net/?ln=en)
   - **N.B.:** If you have already found the paper on [arXiv](https://arxiv.org/) you should be able to find the INSPIRE listing linked under "References & Citations"
2. Get the BibTeX for the paper citation provided by INSPIRE (under "Export" at the bottom of the page)
3. Add this BibTeX entry to [`tex/HEPML.bib`](https://github.com/iml-wg/HEP-ML-Resources/blob/master/tex/HEPML.bib) in the appropriate chronological position
4. Add a citation to [`tex/HEPML.tex`](https://github.com/iml-wg/HEP-ML-Resources/blob/master/tex/HEPML.tex) in the appropriate chronological position
5. `make` and copy the resulting citation into [`papers.md`](https://github.com/iml-wg/HEP-ML-Resources/blob/master/papers.md) in the appropriate chronological position
   - You will need to add the appropriate hyperlinks. Follow the style used for previous entries.
6. Add and commit `tex/HEPML.bib`, `tex/HEPML.tex`, and `papers.md` to your pull request

### How do I add a workshop?

1. Update the workshop timeline. Move any workshops that have recently occurred from "Upcoming" to "Past"
2. Paste the full title of the workshop into the correct chronological position in its appropriate section ("Upcoming" or "Past")
3. Hyperlink the full title to the workshop Indico page or website
4. Add the dates of the workshop
5. If the workshop was restricted to a specific experiment add a badge following the entry with

  - SUBJECT = restricted
  - STATUS = the experiment/group the workshop was restricted to
  - COLOR = red

### How do I make a badge/shield?

Badges are made using [shields.io](http://shields.io/). Scroll down to the "Your Badge" section of the page and then fill in the subject, status, and color for the badge that you want and then click "Make Badge". Then simply paste

```
![](https://img.shields.io/badge/your-badge-url.svg)
```

into the `.md` file.

Badges do not have to be static. For example, you can have a badge that automatically detects the license for a given repository:

```
[![license](https://img.shields.io/github/license/iml-wg/HEP-ML-Resources.svg)](https://github.com/iml-wg/HEP-ML-Resources/blob/master/LICENSE)
```

generates the linked badge

[![license](https://img.shields.io/github/license/iml-wg/HEP-ML-Resources.svg)](https://github.com/iml-wg/HEP-ML-Resources/blob/master/LICENSE)
