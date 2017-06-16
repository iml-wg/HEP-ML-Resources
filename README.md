[![license](https://img.shields.io/github/license/iml-wg/HEP-ML-Resources.svg)]()

# HEPML Resources

## Table of contents

- [General ML Info](#general-machine-learning-information-)
- [Software](#software)
- [Lectures](#lectures)
- [Papers](#papers)
- [Workshops](#workshops)
- [Tweets](#tweets)
- [Contributing](#contributing)

Listing of useful (mostly) public learning resources for machine learning applications in high energy physics (HEPML). Listings will be in reverse chronological order (like a CV).

> **N.B.:** This listing will almost certainly be biased towards work done by ATLAS scientists, as the maintainer is a member of ATLAS and so sees ATLAS work the most. However, this is not the desired case and [help to diversify this listing](#contributing) would be greatly appreciated.

## General Machine Learning Information ![Introductory](https://img.shields.io/badge/subject-introductory-blue.svg)

### Lectures and Tutorials

- [CERN Academic Training Lecture Regular Programme](https://indico.cern.ch/category/72/), April 2017 (Machine Learning):

  - [Machine Learning (Lecture 1)](https://indico.cern.ch/event/619370/) --- [Michael Kagan](https://www.linkedin.com/in/michael-kagan-06292616/) (SLAC)
  - [Machine Learning (Lecture 2)](https://indico.cern.ch/event/619371/) --- [Michael Kagan](https://www.linkedin.com/in/michael-kagan-06292616/) (SLAC)
  - [Deep Learning and Vision](https://indico.cern.ch/event/619372/) --- [Jonathon Shlens](https://research.google.com/pubs/JonathonShlens.html) (Google Research)

- [Scikit-learn Tutorial](https://indico.cern.ch/event/595059/contributions/2522192/), [Gilles Louppe](https://glouppe.github.io/) [![nbviewer](https://img.shields.io/badge/view%20on-nbviewer-brightgreen.svg)](https://nbviewer.jupyter.org/github/glouppe/tutorials-iml2017/tree/master/)

- [Keras and TMVA interfaces Tutorial](https://indico.cern.ch/event/595059/contributions/2522193/), [Stefan Wunsch](https://www.ims.kit.edu/14_117.php)

- [Introduction to Deep Learning with Keras Tutorial](https://gist.github.com/lukedeo/0654e7310432d6d435126c556b863907), [Luke de Oliveira](https://ldo.io/)

- [Deep Learning in High Energy Physics](https://youtu.be/cSxQPFb0yOw), [Amir Farbin](http://www.uta.edu/physics/pages/faculty/profiles/farbin/index.html)

### Courses

- [Applications of Deep Learning to High Energy Physics](https://wiki.uta.edu/display/~afarbin/Physics+4%285%29391-002+-+Applications+of+Deep+Learning+to+High+Energy+Physics), [Amir Farbin](http://www.uta.edu/physics/pages/faculty/profiles/farbin/index.html) (Spring, 2017 - University of Texas at Arlington)

- [Tensorflow for Deep Learning Research](https://web.stanford.edu/class/cs20si/syllabus.html), (Spring, 2017 - Stanford Univeristy)

- [Introduction to Machine Learning and Convolutional Neural Networks for Visual Recognition](https://www.youtube.com/watch?v=NfnWJUyUJYU), [Andrej Karpathy](https://cs.stanford.edu/people/karpathy/) (Winter, 2016 - Stanford Univeristy)

- [Machine Learning in High Energy Physics 2016](https://github.com/yandexdataschool/mlhep2016), [Yandex School of Data Analysis](https://yandexdataschool.com/) (Summer, 2016 - Lund University)

### Journals

- [Distill Research Journal](http://distill.pub/)

## Software

### Common software tools and environments used in HEP for ML

- The [Conda package and environment manager](https://conda.io/docs/) and [Anaconda](https://www.continuum.io/anaconda-overview) Python library collection

  - [Using ROOT/PyROOT with Conda and NumPy](https://indico.cern.ch/event/619371/attachments/1450504/2236434/Kagan_Lecture2.pdf#page=99)

- [scikit-learn](http://scikit-learn.org/stable/)

- [TMVA](http://tmva.sourceforge.net/)

### High level deep learning libraries/framework APIs

- [Keras](https://keras.io/)

### Deep learning frameworks

- [TensorFlow](https://www.tensorflow.org/)
- [Theano](http://deeplearning.net/software/theano/)

### HEP Developed Inference Tools

- [LWTNN](https://github.com/lwtnn/lwtnn)

## Lectures

- [QCD-Aware Neural Networks for Jet Physics](https://indico.cern.ch/event/640111/), [Kyle Cranmer](http://theoryandpractice.org/)
- [(Machine) Learning to Pivot with Adversarial Networks](http://indico.iihe.ac.be/indico/conferenceDisplay.py?confId=1082), [Gilles Louppe](https://glouppe.github.io/)

### Lecture and Seminar Series

- [CERN Data Science Seminars](https://indico.cern.ch/category/9320/)

<!-- ## Notebooks - [Vince Croft RooFit Notebooks](https://www.nikhef.nl/~vcroft/notebooks.html) -->

 ## Papers

- M. Paganini, L. de Oliveira, and B. Nachman, "[CaloGAN: Simulating 3D High Energy Particle Showers in Multi-Layer Electromagnetic Calorimeters with Generative Adversarial Networks](https://inspirehep.net/record/1598455)," arXiv:1705.02355 [hep-ex]. (May 5, 2017)

- C. Shimmin, P. Sadowski, P. Baldi, E. Weik, D. Whiteson, E. Goul, and A. Sgaard, "[Decorrelated Jet Substructure Tagging using Adversarial Neural Networks](https://inspirehep.net/record/1516914)," arXiv:1703.03507 [hep-ex]. (March 9, 2017)

- G. Louppe, K. Cho, C. Becot, and K. Cranmer, "[QCD-Aware Recursive Neural Networks for Jet Physics](https://inspirehep.net/record/1511884)," arXiv:1702.00748 [hep-ph]. (February 2, 2017)

- L. de Oliveira, M. Paganini, and B. Nachman, "[Learning Particle Physics by Example: Location-Aware Generative Adversarial Networks for Physics Synthesis](https://inspirehep.net/record/1510258)," arXiv:1701.05927 [stat.ML]. (January 20, 2017)

- P. T. Komiske, E. M. Metodiev, and M. D. Schwartz, "[Deep learning in color: towards automated quark/gluon jet discrimination](https://inspirehep.net/record/1501944)," JHEP 01 (2017) 110, arXiv:1612.01551 [hep-ph]. (December 5, 2016)

- MicroBooNE Collaboration, R. Acciarri et al., "[Convolutional Neural Networks Applied to Neutrino Events in a Liquid Argon Time Projection Chamber](https://inspirehep.net/record/1498561)," JINST 12 (2017) no. 03, P03011, arXiv:1611.05531 [physics.ins-det]. (November 16, 2016)

- M. Kagan, L. d. Oliveira, L. Mackey, B. Nachman, and A. Schwartzman, "[Boosted Jet Tagging with Jet-Images and Deep Neural Networks](http://inspirehep.net/record/1504297/)," EPJ Web Conf. 127 (2016) 00009\. (November 15, 2016)

- G. Bertone, M. P. Deisenroth, J. S. Kim, S. Liem, R. Ruiz de Austri, and M. Welling, "[Accelerating the BSM interpretation of LHC data with machine learning](https://inspirehep.net/record/1496641)," arXiv:1611.02704 [hep-ph]. (November 8, 2016)

- G. Louppe, M. Kagan, and K. Cranmer, "[Learning to Pivot with Adversarial Networks](https://inspirehep.net/record/1495901)," arXiv:1611.01046 [stat.ME]. (November 3, 2016)

- J. Barnard, E. N. Dawe, M. J. Dolan, and N. Rajcic, ["Parton Shower Uncertainties in Jet Substructure Analyses with Deep Neural Networks](https://inspirehep.net/record/1485081)," Phys. Rev. D95 (2017) no. 1, 014018, arXiv:1609.00607 [hep-ph] (September 2, 2016)

- A. Aurisano, A. Radovic, D. Rocco, A. Himmel, M. D. Messier, E. Niner, G. Pawloski, F. Psihas, A. Sousa, and P. Vahle, "[A Convolutional Neural Network Neutrino Event Classifier](https://inspirehep.net/record/1444342)," JINST 11 (2016) no. 09, P09001, arXiv:1604.01444 [hep-ex]. (April 5, 2016)

- L. de Oliveira, M. Kagan, L. Mackey, B. Nachman, and A. Schwartzman, "[Jet-images deep learning edition](https://inspirehep.net/record/1405106)," JHEP 07 (2016) 069, arXiv:1511.05190 [hep-ph]. (November 16, 2015)

- P. Baldi, P. Sadowski, and D. Whiteson, ["Searching for Exotic Particles in High-Energy Physics with Deep Learning](https://inspirehep.net/record/1281836)," Nature Commun. 5 (2014) 4308, arXiv:1402.4735 [hep-ph]. (February 19, 2014)

## Workshops

### Upcoming

- [Hammers & Nails - Machine Learning & HEP](https://www.weizmann.ac.il/conferences/SRitp/Summer2017/) (July 19-28, 2017)
- [Third Machine Learning in High Energy Physics Summer School 2017](https://indico.cern.ch/event/613571/) (July 17-23, 2017)
- [First Computational and Data Science School for High Energy Physics](http://codas-hep.org/) (July 10-13, 2017)

### Past

- [ATLAS Machine Learning Workshop (2017)](https://indico.cern.ch/event/630665/overview) (June 6-9, 2017) ![ATLAS only](https://img.shields.io/badge/restricted-ATLAS-red.svg)
- [Workshop on Machine Learning and b-tagging](https://indico.cern.ch/event/615994/overview) (May 23-26, 2017) ![ATLAS only](https://img.shields.io/badge/restricted-ATLAS-red.svg)
- [DS@HEP 2017](https://indico.fnal.gov/conferenceDisplay.py?confId=13497) (May 8-12, 2017)
- [2nd S2I2 HEP/CS Workshop (Parallel Session)](https://indico.cern.ch/event/622920/timetable/#5-parallel-session-machine-lea) (May 1-3, 2017)
- [CERN openlab workshop on Machine Learning and Data Analytics](https://indico.cern.ch/event/627852/) (April 27, 2017)
- [First IML Workshop on Machine Learning](https://indico.cern.ch/event/595059/) (March 20-22, 2017)
- [DS@HEP at the Simons Foundation](https://indico.hep.caltech.edu/indico/conferenceDisplay.py?confId=102) (July 5-7, 2016)
- [Second Machine Learning in High Energy Physics Summer School 2016](https://indico.cern.ch/event/497368/overview) (June 20-26, 2016)
- [ALICE Mini-Workshop 2016: Statistical Methods and Machine Learning Tutorial](https://indico.cern.ch/event/514695/) (May 18, 2016) ![ALICE only](https://img.shields.io/badge/restricted-ALICE-red.svg)
- [ATLAS Machine Learning Workshop (2016)](https://indico.cern.ch/event/483999/) (March 29-31, 2016) ![ATLAS only](https://img.shields.io/badge/restricted-ATLAS-red.svg)
- [Data Science @ LHC 2015](https://indico.cern.ch/event/395374/) (November 9-13, 2015)

## Tweets

- [#HEPML collection of tweets](https://twitter.com/HEPfeickert/timelines/806382943342096384)

## Contributing

Contributions to help improve the listing are very much welcome! Please read [CONTRIBUTING.md](https://github.com/matthewfeickert/HEP-ML-Resources/blob/master/CONTRIBUTING.md) for details on the process for submitting pull requests or filing issues.

## Authors

Listing maintainer: [Matthew Feickert](http://www.matthewfeickert.com/)

## Acknowledgments

- Following [PurpleBooth](https://github.com/PurpleBooth)'s [README style](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
- All badges made by [shields.io](http://shields.io/)
- Inspiration for this listing came from the [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) repo
