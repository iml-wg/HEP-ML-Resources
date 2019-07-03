# HEPML Resources

[![DOI](https://zenodo.org/badge/89476450.svg)](https://zenodo.org/badge/latestdoi/89476450)
[![license](https://img.shields.io/github/license/iml-wg/HEP-ML-Resources.svg)](https://opensource.org/licenses/MIT)

Listing of useful (mostly) public learning resources for machine learning applications in high energy physics (HEPML). Listings will be in reverse chronological order (like a CV).

> **N.B.:** This listing will almost certainly be biased towards work done by ATLAS scientists, as the maintainer is a member of ATLAS and so sees ATLAS work the most. However, this is not the desired case and [help to diversify this listing](#contributing) would be greatly appreciated.

## Table of contents

- [Introductory Material](#introductory-material)
   - [Lectures](#lectures)
   - [Seminar Series](#seminar-series)
   - [Tutorials](#tutorials)
   - [Schools](#schools)
   - [Courses](#courses)
   - [Journals](#journals)
- [Software](#software)
- [Public Datasets](#public-datasets)
- [Papers](#papers)
- [Workshops](#workshops)
- [Tweets](#tweets)
- [Other HEP Resource Collections](#other-hep-resource-collections)
- [People](#people)
- [Contributing](#contributing)

## Introductory Material ![Introductory](https://img.shields.io/badge/subject-introductory-blue.svg)

### Lectures

- [Introduction to GANs](https://indico.cern.ch/event/655447/contributions/2742176/), by [Luke de Oliveira](https://ldo.io/) (November 3, 2017)

- [Frontiers with GANs](https://indico.cern.ch/event/655447/contributions/2742180/), by [Michela Paganini](http://mickypaganini.github.io) (November 3, 2017)

- [Nikhef Colloquium: "Teaching machines to discover particles"](https://indico.nikhef.nl/event/878/), by [Gilles Louppe](https://glouppe.github.io/) (September 29, 2017)

- [CERN Academic Training Lecture Regular Programme](https://indico.cern.ch/category/72/), April 2017 (Machine Learning):

  - [Machine Learning (Lecture 1)](https://indico.cern.ch/event/619370/) --- [Michael Kagan](https://www.linkedin.com/in/michael-kagan-06292616/) (SLAC)
  - [Machine Learning (Lecture 2)](https://indico.cern.ch/event/619371/) --- [Michael Kagan](https://www.linkedin.com/in/michael-kagan-06292616/) (SLAC)
  - [Deep Learning and Vision](https://indico.cern.ch/event/619372/) --- [Jonathon Shlens](https://research.google.com/pubs/JonathonShlens.html) (Google Research)

- [Deep Learning in High Energy Physics](https://youtu.be/cSxQPFb0yOw), by [Amir Farbin](http://www.uta.edu/physics/pages/faculty/profiles/farbin/index.html)

### Seminar Series

- [CERN Data Science Seminars](https://indico.cern.ch/category/9320/)

- [Inter-Experimental LHC Machine Learning Working Group](https://iml.web.cern.ch/) Guest Seminars:
  - [Open challenges for improving Generative Adversarial Networks (GANs)](https://indico.cern.ch/event/673989/), by [Ian Goodfellow](http://www.iangoodfellow.com/) (October 27, 2017)

### Tutorials

- [PyTorch Deep Learning Minicourse](https://github.com/Atcold/pytorch-Deep-Learning-Minicourse) - [CoDaS-HEP 2018](https://indico.cern.ch/event/707498/timetable/), by [Alfredo Canziani](https://github.com/Atcold) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Atcold/PyTorch-Deep-Learning-Minicourse/master)

- [Intro Tutorial on GANs](https://indico.fnal.gov/event/16720/), by [Michela Paganini](http://mickypaganini.github.io) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mickypaganini/gan_tutorial/master)

- [Scikit-learn Tutorial](https://indico.cern.ch/event/595059/contributions/2522192/), by [Gilles Louppe](https://glouppe.github.io/) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/glouppe/tutorials-iml2017/master) [![nbviewer](https://img.shields.io/badge/view%20on-nbviewer-brightgreen.svg)](https://nbviewer.jupyter.org/github/glouppe/tutorials-iml2017/tree/master/)

- [TMVA Tutorial](https://indico.cern.ch/event/595059/contributions/2522191/), by [Lorenzo Moneta](https://phonebook.cern.ch/phonebook/#personDetails/?id=415998)

- [Keras and TMVA interfaces Tutorial](https://indico.cern.ch/event/595059/contributions/2522193/), by [Stefan Wunsch](https://www.ims.kit.edu/14_117.php)

- [Boosted Decision Tree Tutorial (using XGBoost)](https://github.com/k-woodruff/bdt-tutorial), by [Katherine Woodruff](https://tele.fnal.gov/cgi-bin/telephone.script?type=name_last&accuracy=contains&string=WOODRUFF) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/k-woodruff/bdt-tutorial/master) [![nbviewer](https://img.shields.io/badge/view%20on-nbviewer-brightgreen.svg)](http://nbviewer.jupyter.org/github/k-woodruff/bdt-tutorial/tree/master/)

- [Introduction to Deep Learning with Keras Tutorial](https://gist.github.com/lukedeo/0654e7310432d6d435126c556b863907), by [Luke de Oliveira](https://ldo.io/)

- [Introduction to Deep Learning with Keras Tutorial](https://indico.cern.ch/event/487416/contributions/2174907/) - [2nd Developers@CERN Forum](https://indico.cern.ch/event/487416/timetable/), by [Michela Paganini](http://mickypaganini.github.io)

### Schools

#### HEP-ML:

##### Upcoming:

- [Deep Learning for Science Summer School 2019, Berkeley, CA, USA](https://dl4sci-school.lbl.gov/home) (July 15-19, 2019)
- [5th Machine Learning in High Energy Physics Summer School 2019](https://indico.cern.ch/event/768915/) (July 1-10, 2019)

##### Past:

- [4th Machine Learning in High Energy Physics Summer School 2018](https://indico.cern.ch/event/687473/) (August 6-12, 2018)
   - Associated [Yandex School of Data Analysis](https://github.com/yandexdataschool) repo: [mlhep2018](https://github.com/yandexdataschool/mlhep2018)
- [2nd Computational and Data Science school for High Energy Physics (CoDaS-HEP 2018)](https://indico.cern.ch/event/707498/) (July 23-27, 2018)
- [3rd Machine Learning in High Energy Physics Summer School 2017](https://indico.cern.ch/event/613571/) (July 17-23, 2017)
   - Associated [Yandex School of Data Analysis](https://github.com/yandexdataschool) repo: [mlhep2017](https://github.com/yandexdataschool/mlhep2017)
- [1st Computational and Data Science School for High Energy Physics (CoDaS-HEP)](https://indico.cern.ch/event/625333/) (July 10-13, 2017)
- [2nd Machine Learning in High Energy Physics Summer School 2016](https://indico.cern.ch/event/497368/overview) (June 20-26, 2016)
   - Associated [Yandex School of Data Analysis](https://github.com/yandexdataschool) repo: [mlhep2016](https://github.com/yandexdataschool/mlhep2016)
- [1st Machine Learning in High Energy Physics Summer School 2015](https://www.hse.ru/mlhep2015) (August 27-30, 2015)
   - Associated [Yandex School of Data Analysis](https://github.com/yandexdataschool) repo: [mlhep2015](https://github.com/yandexdataschool/mlhep2015)

#### Deep Learning:

##### Upcoming:

- [Machine Learning Summer School 2019, London, UK](https://sites.google.com/view/mlss-2019/home?authuser=0) (July 15–26, 2019)
- [Machine Learning Summer School 2019, Stellenbosch, South Africa](http://mlssafrica.com/) (January 7-18, 2019)

##### Past:

- [Machine Learning Summer School 2018, Madrid, Spain](http://mlss.ii.uam.es/mlss2018/index.html) (August 27 - September 7, 2018)
- [Machine Learning Summer School 2018, Buenos Aires, Argentina](http://mlss2018.net.ar/) (June 18-20, 2018)
- [Deep Learning and Reinforcement Learning Summer School, Toronto, Canada](https://dlrlsummerschool.ca/) (July 25 - August 3, 2018)
- [PAISS: Artificial Intelligence Summer School, Grenoble, France](https://project.inria.fr/paiss/) (July 2-6, 2018)
- [Deep Learning Summer School 2016](https://sites.google.com/site/deeplearningsummerschool2016/) (August 1-7, 2016)

### Courses

- [Advanced Machine Learning](http://www.montefiore.ulg.ac.be/~geurts/Cours/AML/aml2017_2018.html), Pierre Geurts, [Gilles Louppe](https://glouppe.github.io/), and Louis Wehenkel (Spring, 2018 - Université de Liège, Institut Montefiore)

- [Applications of Deep Learning to High Energy Physics](https://wiki.uta.edu/display/~afarbin/Physics+4%285%29391-002+-+Applications+of+Deep+Learning+to+High+Energy+Physics), [Amir Farbin](http://www.uta.edu/physics/pages/faculty/profiles/farbin/index.html) (Spring, 2017 - University of Texas at Arlington)
   - Associated GitHub repository: [DSatHEP-Tutorial](https://github.com/UTA-HEP-Computing/DSatHEP-Tutorial)

- [Tensorflow for Deep Learning Research](https://web.stanford.edu/class/cs20si/syllabus.html), (Spring, 2017 - Stanford Univeristy)

- Introduction to Machine Learning and Convolutional Neural Networks for Visual Recognition:
  - [Spring, 2017](https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) - Stanford University, [Fei-Fei Li](http://vision.stanford.edu/feifeili/), [Justin Johnson](http://cs.stanford.edu/people/jcjohns/), [Serena Yeung](http://ai.stanford.edu/~syyeung/)
  - [Winter, 2016](https://www.youtube.com/watch?v=NfnWJUyUJYU) - Stanford University, [Andrej Karpathy](https://cs.stanford.edu/people/karpathy/), [Fei-Fei Li](http://vision.stanford.edu/feifeili/), [Justin Johnson](http://cs.stanford.edu/people/jcjohns/)

### Journals

- [Distill Research Journal](http://distill.pub/)

## Software

#### Common software tools and environments used in HEP for ML

- Python environments for scientific computing

    - The [Conda package and environment manager](https://conda.io/docs/) and [Anaconda](https://www.continuum.io/anaconda-overview) Python library collection

      - [Using ROOT/PyROOT with Conda and NumPy](https://indico.cern.ch/event/619371/attachments/1450504/2236434/Kagan_Lecture2.pdf#page=99)

    - [scikit-learn](http://scikit-learn.org/stable/): General machine learning Python library

- [TMVA](https://root.cern.ch/tmva): ROOT's builtin machine learning package

  - [TMVA-branch-adder](https://github.com/pseyfert/tmva-branch-adder): wrapper to add TMVA response to TTree without boiler plate code

### High level deep learning libraries/framework APIs

- [Keras](https://keras.io/)

### Deep learning frameworks

- [TensorFlow](https://www.tensorflow.org/)
- [Theano](http://deeplearning.net/software/theano/)
- [PyTorch](http://pytorch.org/)
- [Caffe2](https://caffe2.ai/)
- [List of Conversion Tools For Saved Networks](https://github.com/ysh329/deep-learning-model-convertor)

### HEP to ML bridge tools

- [lwtnn](https://github.com/lwtnn/lwtnn): Tool to run Keras networks in C++ code

- [sklearn-porter](https://github.com/nok/sklearn-porter): Transpile trained scikit-learn estimators to C, Java, JavaScript and others

- [ONNX](https://onnx.ai) open format to represent deep learning models

- [Scikit-HEP](http://scikit-hep.org/): Toolset of interfaces and Python tools for Particle Physics

  - [root_numpy](https://github.com/scikit-hep/root_numpy): The interface between ROOT and numpy

  - [root_pandas](https://github.com/scikit-hep/root_pandas): An upgrade of root_numpy to use with pandas

  - [uproot](https://github.com/scikit-hep/uproot): Mimimalist ROOT to numpy converter (no dependency on ROOT)

- [ttree2hdf5](https://github.com/dguest/ttree2hdf5): Mimimalist ROOT to HDF5 converter (written in C++)

- [hep_ml](https://github.com/arogozhnikov/hep_ml): Python algorithms and tools for HEP ML use cases

### Images for Containerized Environments

- [ATLAS Machine Learning Docker images](https://gitlab.cern.ch/aml/containers/docker): Base images for a modern Python 3 machine learning environment for physics

<!-- ## Notebooks - [Vince Croft RooFit Notebooks](https://www.nikhef.nl/~vcroft/notebooks.html) -->

## Public Datasets

- [CERN IML public datasets listing](https://iml.web.cern.ch/public-datasets): Listing of public datsets that are used for machine learning studies at the LHC.

## Papers

> A `.bib` file for all papers listed is [available in the `tex` directory](https://github.com/iml-wg/HEP-ML-Resources/blob/master/tex/HEPML.bib).

A listing of papers of applications of machine learning to high energy physics can be found in [`papers.md`](https://github.com/iml-wg/HEP-ML-Resources/blob/master/papers.md).

## Workshops

### Upcoming



### Past

- [CMS Machine Learning Workshop (2019)](https://indico.cern.ch/event/798721/) (June 17-19, 2019) ![CMS only](https://img.shields.io/badge/restricted-CMS-red.svg)
- [Theoretical Physics for Deep Learning at ICML 2019](https://sites.google.com/view/icml2019phys4dl) (June 14, 2019)
- [3rd IML Machine Learning Workshop (2019)](https://indico.cern.ch/event/766872/) (April 15-18, 2019)
- [Accelerating the Search for Dark Matter with Machine Learning (2019)](http://indico.ictp.it/event/8674/) (April 8-12, 2019)
- [5th Connecting The Dots / Intelligent Trackers (2019)](https://indico.cern.ch/event/742793/) (April 2-5, 2019)
- [19th International Workshop on Advanced Computing and Analysis Techniques in Physics Research (ACAT 2019)](https://indico.cern.ch/event/708041/) (March 11-15, 2019)
- [Machine Learning for Jet Physics (2018)](https://indico.cern.ch/event/745718/) (November 14-16, 2018)
- [CMS Machine Learning Workshop (2018)](https://indico.cern.ch/event/730677/) (July 2-4, 2018) ![CMS only](https://img.shields.io/badge/restricted-CMS-red.svg)
- [2nd IML Machine Learning Workshop (2018)](https://indico.cern.ch/event/668017/) (April 9-12, 2018)
- [Machine Learning for Phenomenology (2018)](https://conference.ippp.dur.ac.uk/event/660/) (April 3-6, 2018)
- [4th International Connecting The Dots Workshop (2018)](https://indico.cern.ch/event/658267/) (March 20-22, 2018)
- [Accelerating the Search for Dark Matter with Machine Learning (2018)](https://indico.cern.ch/event/664842/) (January 15-19, 2018)
- [Machine Learning for Jet Physics (2017)](https://indico.physics.lbl.gov/indico/event/546/) (December 11-13, 2017)
- [Deep Learning for Physical Sciences at NIPS](https://dl4physicalsciences.github.io/) (December 8, 2017)
- [18th International Workshop on Advanced Computing and Analysis Techniques in Physics Research (ACAT 2017)](https://indico.cern.ch/event/567550/) (August 21-25, 2017)
- [Hammers & Nails - Machine Learning & HEP](https://www.weizmann.ac.il/conferences/SRitp/Summer2017/) (July 19-28, 2017)
- [CMS Machine Learning Workshop (2017)](https://indico.cern.ch/event/646801) (July 5-6, 2017) ![CMS only](https://img.shields.io/badge/restricted-CMS-red.svg)
- [ATLAS Machine Learning Workshop (2017)](https://indico.cern.ch/event/630665/overview) (June 6-9, 2017) ![ATLAS only](https://img.shields.io/badge/restricted-ATLAS-red.svg)
- [Workshop on Machine Learning and b-tagging](https://indico.cern.ch/event/615994/overview) (May 23-26, 2017) ![ATLAS only](https://img.shields.io/badge/restricted-ATLAS-red.svg)
- [DS@HEP 2017](https://indico.fnal.gov/conferenceDisplay.py?confId=13497) (May 8-12, 2017)
- [2nd S2I2 HEP/CS Workshop (Parallel Session)](https://indico.cern.ch/event/622920/timetable/#5-parallel-session-machine-lea) (May 1-3, 2017)
- [CERN openlab workshop on Machine Learning and Data Analytics](https://indico.cern.ch/event/627852/) (April 27, 2017)
- [First IML Workshop on Machine Learning](https://indico.cern.ch/event/595059/) (March 20-22, 2017)
- [DS@HEP at the Simons Foundation](https://indico.hep.caltech.edu/indico/conferenceDisplay.py?confId=102) (July 5-7, 2016)
- [ALICE Mini-Workshop 2016: Statistical Methods and Machine Learning Tutorial](https://indico.cern.ch/event/514695/) (May 18, 2016) ![ALICE only](https://img.shields.io/badge/restricted-ALICE-red.svg)
- [ATLAS Machine Learning Workshop (2016)](https://indico.cern.ch/event/483999/) (March 29-31, 2016) ![ATLAS only](https://img.shields.io/badge/restricted-ATLAS-red.svg)
- [Heavy Flavour Data Mining workshop](https://indico.cern.ch/event/433556/) (February 18-20, 2016)
- [Data Science @ LHC 2015](https://indico.cern.ch/event/395374/) (November 9-13, 2015)

## Tweets

- [#HEPML collection of tweets](https://twitter.com/search?q=HEPML&src=typd)

## People

- [HEPML directory](http://mickypaganini.github.io/HEPML_directory): Opt-in list of people working at the intersection of Machine Learning and High Energy Physics
   - Add yourself through the [Google form](https://t.co/jprokVZEiK)

## Other HEP Resource Collections

- [HEP Software Foundation](https://github.com/hsf-training)'s list of [Python Libraries of Interest to Particle Physics](https://github.com/hsf-training/PyHEP-resources)

## Contributing

Contributions to help improve the listing are very much welcome! Please read [CONTRIBUTING.md](https://github.com/matthewfeickert/HEP-ML-Resources/blob/master/CONTRIBUTING.md) for details on the process for submitting pull requests or filing issues.

## Authors

Listing maintainer: [Matthew Feickert](http://www.matthewfeickert.com/)

## Acknowledgments

- Following [PurpleBooth](https://github.com/PurpleBooth)'s [README style](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
- All badges made by [shields.io](http://shields.io/)
- Inspiration for this listing came from the [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) repo and [Dustin Tran](http://dustintran.com/)'s [Machine Learning Videos](https://github.com/dustinvtran/ml-videos) repo
- Many thanks to [everyone who has contributed their time](https://github.com/iml-wg/HEP-ML-Resources/graphs/contributors) to improve this project
