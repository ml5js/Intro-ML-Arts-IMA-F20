# 1A: Welcome and Introduction to Machine Learning

## Objectives
* Define AI, machine learning, and deep learning.
* Overview of applications of machine learning, especially for art and design.
* History of machine learning.
* Overview of tools for machine learning.
* Classification and Regression

## Outline
* Introductions
* Syllabus
* [Slides: Introduction to ML](https://docs.google.com/presentation/d/1tehmNfZdN68_PouhwVmZ2MNrVRLs0dYixkCyhTbi_EY/edit?usp=sharing)
* p5.js review

## Supplemental Materials
* Read [What is machine learning? We drew you another flowchart](https://www.technologyreview.com/s/612437/what-is-machine-learning-we-drew-you-another-flowchart/) by Karen Hao
* Read [A People’s Guide to AI](https://alliedmedia.org/wp-content/uploads/2020/09/peoples-guide-ai.pdf) by Mimi Onuoha and Mother Cyborg (Diana Nucera)
* Read [Data & Society’s Algorithmic Accountability: A Primer](https://datasociety.net/wp-content/uploads/2018/04/Data_Society_Algorithmic_Accountability_Primer_FINAL-4.pdf)
* Watch [Seeing Machines Think — Martin Wattenberg and Fernanda Viégas](https://youtu.be/ugkfmHBW74Q)
* Watch [Kyle McDonald - Weird Intelligence](https://vimeo.com/304110435)

## p5.js review
* [Learning While Making p5.js with Lauren McCarthy](https://youtu.be/1k3X4DLDHdc)
* [Introducing the p5.js web editor!](https://youtu.be/dtHxDggkBYc)
* [p5.js web editor with Cassie Tarakajian](https://youtu.be/x1rJJRVTpAI)
* [Code! Programming with p5.js playlist](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)

## Assignment
1. Create a blog (or category on a blog) for the course. (You may use any means for publishing your assignments including, but not limited to, a GitHub markdown file, medium post, etc.) [This wiki page has resources and information on creating your own blog](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Blog-Resources). Additionally, here is some [helpful information on privacy options for your blog](https://nyu.service-now.com/sp?id=kb_article&sysparm_article=KB0012245&sys_kb_id=b2ddc9da004aa1002a5d036a271e5f70&spa=1).
2. Read [A People’s Guide to AI](https://alliedmedia.org/wp-content/uploads/2020/09/peoples-guide-ai.pdf).
3. Creating a blog post documenting and reflecting on the following exercises from [A People’s Guide to AI](https://alliedmedia.org/wp-content/uploads/2020/09/peoples-guide-ai.pdf).
   * When you hear the words "Artificial Intelligence", what are the first four things that come to your mind? (p.11)
   * Answer the questions from the "Everyday AI Activity" on pages 23-28 of the [A People’s Guide to AI](https://alliedmedia.org/wp-content/uploads/2020/09/peoples-guide-ai.pdf). 
3. Add a link to your post on the [Homework Wiki Page for Assignment 1a](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Assignment-1a). You are welcome to post under a pseudonym or alias.


## 1B: Introduction to ml5.js and pre-trained models

### Objectives:
* Understand the concept of a “machine learning model.”
* What is a “pre-trained model”?
* What does it mean to discuss the “architecture” of a machine learning model?
* Define and diagram an artificial neural network.
* Understand what ml5.js is and how it fits into the TensorFlow and open source machine learning library ecosystem.
* Learn how to create an image classifier with ml5.js and MobileNet.
* Understand how the MobileNet model was trained, specifically the origins and collection methodology for the training.
* [Session 1b Slides](https://docs.google.com/presentation/d/12q9GbIxtoA7U5GHETIUuznxwnjWviK8xPki8uiOaOS8/edit?usp=sharing)

### ml5.js video tutorials
* [A Beginner's Guide to Machine Learning with ml5.js - video tutorial](https://youtu.be/jmznx0Q1fP0?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
* [ml5.js: Image Classification with MobileNet - video tutorial](https://youtu.be/yNkAuWz5lnY?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
* [ml5.js: Webcam Image Classification - video tutorial](https://youtu.be/D9BoBSkLvFo?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)

### ml5.js resources
* [ml5 website](https://ml5js.org)
* [all ml5 examples](https://examples.ml5js.org/)

### ml5 code editor examples
* [Image Classification](https://editor.p5js.org/ml5/sketches/ImageClassification)
* [Drag and Drop Image Classification](https://editor.p5js.org/ima_ml/sketches/rnm3SJmMd)
* [Webcam Image Classification](https://editor.p5js.org/ml5/sketches/ImageClassification_Video)
* [Webcam Image Classification Text to Speech](https://editor.p5js.org/ml5/sketches/ImageClassification_VideoSound)
* [Image Classification Scavenger Hunt](https://editor.p5js.org/ml5/sketches/ImageClassification_VideoScavengerHunt)

### Defining Machine Learning yet again
* "Machine learning is programming with examples, not instructions" -- from [Kyle McDonald - Weird Intelligence](https://vimeo.com/304110435).
* "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E." -- Tom Mitchell (1998): [Machine Learning book](http://amzn.to/2nLdRgQ).
  * Example: classifying images of dogs and cats.
    * E = Watching you classify images as dogs or cats.
    * T = Classifying images as dogs or cats.
    * P = The % of images correctly classified.

### Classification and Regression
* Classification and regression both involve making a "prediction" based on input data.
* Classification refers to predicting an output with a discrete set of possibilities like a set of categories or labels. For example: "Given an input image, is it a dog or cat?"
* Regression refers to predicting an "continuous" output (a fancy way of saying number). For example: "Given the number of bedrooms, what is the price of a house?" or "Given an input image of a cat, how much does the cat weigh?"

### Reading / Viewing:
1. Read Andrey Kurenkov's ['Brief' History of Neural Nets and Deep Learning](http://www.andreykurenkov.com/writing/a-brief-history-of-neural-nets-and-deep-learning/)
2. Read [ImageNet: The Data That Transformed AI Research—and Possibly the World](https://qz.com/1034972/the-data-that-changed-the-direction-of-ai-research-and-possibly-the-world/) by Dave Gershgorn (Note: Fei-Fei Li is no longer at Google; she is currently Co-Director of the Stanford Human-Centered AI Institute)

### Assignment 1B
1. Explore [ImageNet](http://image-net.org/index). What surprises you about this data set? What questions do you have? Thinking back to last week’s assignment, can you think of any ethical considerations around how this data was collected Are there privacy considerations with the data?
2. Using the [ml5.js examples above](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/tree/main/02_ml_models#ml5-code-editor-examples), try running image classification on a variety of images. Pick at least 10 objects in your room. How many of these does it recognize? What other aspects of the image affect the classification, including but not limited to position, scale, lighting, etc.
3. Document your thoughts on MobileNet and image classification in a blog post and add a link to the [Assignment 1b Wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Assignment-1b).