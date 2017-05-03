# Contributing

To contribute to this project please either start a pull request or an issue with the details of the information that you want added.

## Pull Request Process

1. Beautify your `.md` file using [Tidy Markdown](https://github.com/slang800/tidy-markdown)
2. Verify that your Markdown has been correctly formatted by rendering your `.md` with [Grip](https://github.com/joeyespo/grip)
3. If you have edited the LaTeX file make sure to run `make realclean`

## FAQ

### How do I make a shield?

Shields are made using [shields.io](http://shields.io/). Scroll down to the "Your Badge" section of the page and then fill in the subject, status, and color for the badge that you want and then click "Make Badge". Then simply paste

```
![](https://img.shields.io/badge/your-badge-url.svg)
```

into the `.md` file.

### How do add a workshop?

1. Update the workshop timeline. Move any workshops that have recently occurred from "Upcoming" to "Past".
2. Past the full title of the workshop into the correct chronological position in its appropriate section ("Upcoming" or "Past")
3. Hyperlink the full title to the workshop Indico page or website
4. Add the dates of the workshop (Month start_date-end_date, Year)
5. If the workshop was restricted to a specific experiment add a badge following the entry with

  - SUBJECT = restricted
  - STATUS = the experiment/group the workshop was restricted to
  - COLOR = red
