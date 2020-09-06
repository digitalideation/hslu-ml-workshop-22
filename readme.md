![di logo](https://raw.githubusercontent.com/digitalideation/hslu-ml-workshop/master/docs/assets/images/di-logo-small.jpg "di logo")


# HSLU AI Autumn session :fallen_leaf:

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/webslides/webslides.svg?style=social)](https://twitter.com/digideation)

Main repository for the HSLU ML session @digitalideation.

All the info regarding the workshop as well as direct links to learning materials (slides, notebooks, examples, etc... ) are accessible via the github pages for this repository:

https://digitalideation.github.io/hslu-ml-workshop/


## Schedule

#### 07.09
* 9am - Start :smiley_cat:
* 9am - Introduction 
* 10am - Software setup + intro to tools
  * Editors + local server
  * Runway
  * Runway + html 
* 11am - Experiments
* 12pm - Lunch
* 1pm - Experiments
* 5pm - End

#### 08.09
* 9am - Experiments
* 12pm - Lunch
* 1pm - Experiments
* 4pm - Showcase
* 5pm - End :crying_cat_face:


## Content

#### Slides
1. [Slides for the ML workshop](https://digitalideation.github.io/hslu-ml-workshop/slides/)

#### Samples
The sample folder contains different examples:

```
samples/p5
├── 00_p5js.html
├── 00_runwayml.html
├── 01_styletransfer_00.html
├── 01_styletransfer_01.html
├── 01_styletransfer_02.html
├── 02_mobilenet_00.html
├── 03_cocossd_00.html
├── 04_posenet_00.html
├── 04_posenet_im2txt_00.html
├── 05_im2txt_attngan_00.html
├── 06_pix2pix_00.html
├── assets
├── css
└── js
```


## Tools

#### System requirement
_"Modern"_ machine with decent hardware and sufficient space on the hard drive (20+ Gb is good)

#### Code editor
If you don’t have a code editor, please install one. Some suggestions (in no particular order)
- [Sublime Text](https://www.sublimetext.com)
- [Visual Studio](https://code.visualstudio.com)
- [Atom](https://atom.io) 

#### Web server
We need a simple web server to interact with the models locally. 
- The easiest is to use Python's [SimpleHTTPServer](https://github.com/lmccart/itp-creative-js/wiki/SimpleHTTPServer). Type in Terminal:```python -m SimpleHTTPServer``` or if you are using Python 3, type:```python -m http.server```
- If you have node.js/npm installed you can use _live-server_: `npm install -g live-server`
- [Other recommended options](https://github.com/processing/p5.js/wiki/Local-server)

#### Runway
We are using [__Runway__](https://runwayapp.ai), a tool which makes deploying ML models easy, as middleware to build the interactive experiments. All participants to the workshop should have received an invitations with some GPU credits :tada:. For those who have not installed it prior to the workshop, we will go through the [installation process](https://docs.runwayml.com/#/getting-started/installation) together.

#### P5.js
We will use [__p5.js__ ](https://p5js.org/) for the front end. It’s a high level creative programming framework with an [intuitive API](https://p5js.org/reference/). If some of you have used Processing before you should be confortable using p5.js. To get familiar with p5 you can go through this list of tutorials / guides:
- [JS for cats](http://jsforcats.com)
- [Matt DesLauriers JS guide](https://github.com/mattdesl/workshop-data-artwork#javascript-guides)
- [P5 Learn](https://p5js.org/learn/)
- [P5 Wiki](https://github.com/processing/p5.js/wiki/)
- [Creative Coding](https://creative-coding.decontextualize.com/)
- [Shiffman's Foundation of programming in js](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
- [P5js reference](https://p5js.org/reference/)

#### Docker
[__Docker__](https://www.docker.com/) will eventually be needed in order to deploy some of the models locally. This will give us some flexibility when running experiments on our machine. A guide to getting started is [available](https://docs.runwayml.com/#/getting-started/installation?id=download-docker). For linux users, those [post install steps](https://docs.docker.com/install/linux/linux-postinstall/) could be useful as well.

> Docker for Windows requires Microsoft Hyper-V, which is supported only in the Pro, Enterprise or Education editions of Windows. If you don't have a Pro, Enterprise or Education Windows edition you will not be able to install Docker and you will be able to only run some models using cloud GPU.


## References / Reading list

* History:
  + [History - Longer history of Machine Learning](http://www.andreykurenkov.com/writing/ai/a-brief-history-of-neural-nets-and-deep-learning/)
  + [History - History of Machine Learning](https://cloud.withgoogle.com/build/data-analytics/explore-history-machine-learning/)
* Intro:
  + [Neural Networks - Intro videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
  + [Neural Networks - Intro text](https://ml4a.github.io/ml4a/neural_networks/)
  + [Machine Learning - Getting started](https://www.youtube.com/watch?v=I74ymkoNTnw)
  + [Machine Learning is fun (series)](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471)
* Books:
  + [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python)
  + [Grokking Deep Learning](https://www.manning.com/books/grokking-deep-learning)
  + [Intelligence Artificielles, Miroirs de nos vies (BD) ](http://www.sceneario.com/bande-dessinee/intelligences-artificielles/miroirs-de-nos-vies/29059.html)
* Tools:
  + [ML5js - Friendly Machine Learning for the Web](https://ml5js.org/)
  + [Tensorflow.js](https://www.tensorflow.org/js/)


## Repository structure

```
├── docs
│   ├── _layouts
│   ├── assets            (img, etc.. for content)
│   │   ├── css
│   │   └── images
│   └── slides            (slides of the presentations)
│       ├── demos
│       └── static        (img, etc.. for slides)
└── samples               (code sample)
```