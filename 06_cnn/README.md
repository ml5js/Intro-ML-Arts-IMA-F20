# Convolutional Neural Network (CNN)

- [Week 6 CNN Slides](https://docs.google.com/presentation/d/1YMlrmpkewAZE5abcoruBztRvsTdVvq1BjtqXauW66Zg/edit?usp=sharing)

## Session A: What is CNN?

### Objectives:

- Understand when and why you might train your own model from scratch versus use a pre-trained model or transfer learning.
- Learn about the Google “Quick, Draw!” dataset.
- Understand how ato work with image data for training your own model.

### Quick, Draw! Data

- [Data and Documentation](https://github.com/googlecreativelab/quickdraw-dataset)
- [Video tutorial: Replaying Drawings with node server](https://thecodingtrain.com/CodingChallenges/122.1-quick-draw)
- [Video tutorial: Replaying Drawings with Google Web API](https://thecodingtrain.com/CodingChallenges/122.2-quick-draw)
- [Preparing Data as Images for Doodle Classifer Part 1](https://youtu.be/gX7U6WA7Ffk)
- [Preparing Data as Images for Doodle Classifer Part 2](https://youtu.be/wMe6qcpD8jI)

### Examples

- [Displaying MNIST](https://editor.p5js.org/ima_ml/sketches/ndqnn8p3F)
- [Displaying Quick, Draw! 28x28 images](https://editor.p5js.org/ima_ml/sketches/wOO4nvwyw)
- [Animating Quick, Draw! paths](https://editor.p5js.org/ima_ml/sketches/aT9zxHX7n)

### Creative Quick, Draw! projects
- [Letter collages](http://frauzufall.de/en/2017/google-quick-draw/) by [Deborah Schmidt](http://frauzufall.de/)
- [Face tracking experiment](https://www.instagram.com/p/BUU8TuQD6_v/) by [Neil Mendoza](http://www.neilmendoza.com/)
- [Faces of Humanity](http://project.laboiteatortue.com/facesofhumanity/) by [Tortue](www.laboiteatortue.com)
- [Scribbling Speech](http://xinyue.de/scribbling-speech.html) by [Xinyue Yang](http://xinyue.de/)
- [How do you draw a circle?](https://qz.com/994486/the-way-you-draw-circles-says-a-lot-about-you/)

### Other Related Projects:
- [Machine Learning for Visualization by Ian Johnson](https://medium.com/@enjalot/machine-learning-for-visualization-927a9dff1cab)
- [MegaPixels: Faces](https://ahprojects.com/megapixels-glassroom/) curated by Tactical Tech, design and development by Adam Harvey
- [Watch What Neural Networks See](https://experiments.withgoogle.com/what-neural-nets-see) by Gene Kogan
- [Recognizing Human Facial Expressions With Machine Learning](https://thoughtworksarts.io/blog/recognizing-facial-expressions-machine-learning/) by Angelica Perez

## Session B: Doodle Classification

### Objectives

- Learn to train an image classifier (no convolutional layers) with ml5.js.
- Learn the distinction between different types of layers of a neural network, specifically “What is a convolutional layer?”
- Learn to feed the input of a graphics canvas into a machine learning model.

### Video Tutorials

- [What is Convolutional Neural Network Part 1](https://youtu.be/qPKsVAI_W6M?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
- [What is Convolutional Neural Network Part 2](https://youtu.be/pRWq_mtuppU?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)

### Convolutional Neural Nets

- [Original 1998 "LetNet5" paper: "Gradient-Based Learning Applied to Document Recognition"](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf) by Y. Lecun, L. Bottou, Y. Bengio, P. Haffner
- [Interactive Node-Link Visualizations of Convolutional Neural Networks](http://scs.ryerson.ca/~aharley/vis/)
- [How computers got shockingly good at recognizing images](https://arstechnica.com/science/2018/12/how-computers-got-shockingly-good-at-recognizing-images/) by Timothy B. Lee
- [Image Kernels Explained Visually](http://setosa.io/ev/image-kernels/) by Victor Powell
- [A visual and intuitive understanding of deep learning, CNNs](https://www.youtube.com/watch?v=Oqm9vsf_hvU) (0:00 - 9:40) by Octavio Good

### Examples

- [p5.js Convolution demo](https://editor.p5js.org/codingtrain/sketches/BN1lE-gyl)
- [p5.js Convolution demo -- max pooling](https://editor.p5js.org/codingtrain/sketches/GMRfsK7Wn)
- [Training a model with `ml5.neuralNetwork()` and Google Quick, Draw! images](https://editor.p5js.org/ima_ml/sketches/bL6jONrFQ)
- [Classifying Drawings with ml5's DoodleNet](https://editor.p5js.org/ima_ml/sketches/IbXlN6voN) (model trained by @yining1023)

### Assignment 6 Due Sunday October 18

#### Reading

- [An Intuitive Explanation of Convolutional Neural Networks](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/) by Ujjwal Karn
- [Exploring and Visualizing an Open Global Dataset](https://research.googleblog.com/2017/08/exploring-and-visualizing-open-global.html) by Google Research

#### Reflection

- After playing [Quick, Draw](https://quickdraw.withgoogle.com/) in class, reviewing the [Quick, Draw](https://quickdraw.withgoogle.com/data), and reading the above [Exploring and Visualizing an Open Global Dataset](https://research.googleblog.com/2017/08/exploring-and-visualizing-open-global.html) by Google Research, consider the following question. How can visualization help diagnose "data for inclusion" and "identify concrete ways that anyone can improve the variety of data, as well as check for potential biases."

#### Coding Exercise

- Build off of one of the following code examples (or invent your own) to develop you own creative use of Quick, Draw data.
    - [Rendering Quick, Draw drawings](https://editor.p5js.org/ima_ml/sketches/vCfQL93k7)
    - [Animating Quick, Draw! paths](https://editor.p5js.org/ima_ml/sketches/aT9zxHX7n)
    - [Classifying Drawings with ml5's DoodleNet: output in DOM element](https://editor.p5js.org/ima_ml/sketches/IbXlN6voN) -- *Can you make this one work with webcam input instead of canvas?*
    - [Classifying Drawings with ml5's DoodleNet: output in separate canvas](https://editor.p5js.org/ima_ml/sketches/XIZEoKBTL) 

Complete a blog post with thoughts on the Quick, Draw dataset and your code exercise. [Link from the homework wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Assignment-6).


