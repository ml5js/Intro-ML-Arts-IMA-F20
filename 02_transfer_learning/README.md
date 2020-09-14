# Transfer Learning

## Session A: Teachable Machine

### Objectives:
* Diagram and define the layers of a neural network, introducing the concept of a “convolutional layer.”
* Distinguish between a “feature vector” (aka logits) and the last layer (aka softmax probabilities) of a classification network.
* Understand the process of “transfer learning.”
* Learn to save a trained model for re-use later.
* [Week 2 Slides](https://docs.google.com/presentation/d/10e49FloSXEBOOcC26CKyncPDcM0qDrHYG34C_JMZdEo/edit?usp=sharing)

### Supervised Learning
* From Andrew Ng: "In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output."
* Adapted from [Nature of Code Chapter 10](http://natureofcode.com/book/chapter-10-neural-networks/): Supervised Learning is a strategy that involves a "teacher" that trains the learning system. For example, consider facial recognition. The "teacher" shows the network a bunch of faces (the teacher already knows the names associated with each face). The learning system makes its guesses and the teacher provides the answers. The learning system can then compare its answers to the known “correct” ones and make adjustments according to its errors.

### Related Projects:
* [Webcam Pacman](https://storage.googleapis.com/tfjs-examples/webcam-transfer-learning/dist/index.html) by Google’s TensorFlow.js Team
* [Pong ML](https://github.com/matamalaortiz/Pong-ML) by Alejandro Matamala Ortiz
* [Regression Curve](https://github.com/byjoohyunpark/regression-curve) by Joohyun Park
* [Asemic Writing Teachable Machine](http://blog.jzhong.today/computationaltypo/Asemic-Writing-Teachable-Machine/) by Jillian Zhong
* [Resistor classification](https://leafava2.wixsite.com/portfolio/blog-1/week-2-ml-hw) by Azalea Vaseghi and Amitabh Shrivastava

### Reading / Viewing:
1. Watch [But what *is* a Neural Network?](https://youtu.be/aircAruvnKk) by 3Blue1Brown
2. Read [How to Build a Teachable Machine with TensorFlow.js](https://observablehq.com/@nsthorat/how-to-build-a-teachable-machine-with-tensorflow-js)
3. Read [Excavating AI: The Politics of Images in Machine Learning Training Sets](https://www.excavating.ai) by Kate Crawford and Trevor Paglen (See: [ImageNet Roulette](https://imagenet-roulette.paglen.com) - going offline Sept 27, 2019).

## Session B

### ml5.js video tutorials
* [ml5.js: Transfer Learning with Feature Extractor - video tutorial](https://youtu.be/kRpZ5OqUY6Y?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
* [ml5.js: Feature Extractor Classification - video tutorial](https://youtu.be/eeO-rWYFuG0?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
* [ml5.js: Feature Extractor Regression - video tutorial](https://youtu.be/aKgq0m1YjvQ?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
* [ml5.js: Save/Load Model - video tutorial](https://youtu.be/eU7gIy3xV30?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)


### Assignment 2B:
1. Train your own image classifer using transfer learning and ml5.js and apply the model to an interactive p5.js sketch. You can train the model with Teachable Machine or with your own ml5.js code. Feel free to try sound instead of or in addition to images. You may also choose to experiment with a "regression" rather than classification.
    * [Teachable Machine ml5.js example for Image Classification](https://editor.p5js.org/ima_ml/sketches/8Wmwnig7-)
    * [Teachable Machine ml5.js example for Sound Classification](https://editor.p5js.org/ima_ml/sketches/xcdqphiVj)
2. Document your exercise in a blog post and add a link to the post and your p5 sketch on the [Assignment 2 Wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Assignment-2). In your blog post, include visual documentation such as a recorded screen capture / video of your training session and sketch running in the browser.
