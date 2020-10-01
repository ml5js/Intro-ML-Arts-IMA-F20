# Training a Neural Network

## Session A: Training a Neural Network

### Objectives:
* Learn steps to construct a vanilla neural network and train a classification model with ml5.js.
* Understand Neural Network architecture
    * What is a Perceptron?
    * What is a multi-layered perceptron?
    * Activation Functions
* Understand the terminology of the training process
    * Training
    * Learning Rate
    * Epochs
    * Batch size
    * Loss
* Understand the difference between training and inference
  
### Background: Perceptron and Artifical Neural Networks
* [What is a Neural Network?](https://youtu.be/aircAruvnKk?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) by 3Blue1Brown
* Invented in 1957 by Frank Rosenblatt at the Cornell Aeronautical Laboratory ([original paper](http://www.ling.upenn.edu/courses/cogs501/Rosenblatt1958.pdf)), a perceptron is the simplest neural network possible: a computational model of a single neuron. A perceptron consists of one or more inputs, a processor, and a single output. ([More to this history](https://github.com/ml5js/Intro-ML-Arts-IMA-F19/wiki/Brief-History-of-Artificial-Neural-Networks)
* [NOC Neural Network videos](https://youtu.be/XJ7HLz9VYz0?list=PLRqwX-V7Uu6aCibgK1PTWWu9by6XFdCfh) - 10.1 to 10.3 cover the "Perceptron", a model of a single neuron. The Perceptron forms the basis of modern multi-layer deep learning networks.
* [NOC Neural Network chapter 10](https://natureofcode.com/book/chapter-10-neural-networks/) - written explanation of Perceptron and accompanying code in 10.1 to 10.4.

### p5.js Oscillators
* [p5.js Oscillator example](https://editor.p5js.org/ima_ml/sketches/fSGClc_aK)
* [Sound Synthesis video tutorial](https://youtu.be/Bk8rLzzSink)

### Related projects that map gesture to sound
* [MARtLET](https://vimeo.com/19980514) by Michelle Nagai
* [From the Waters](https://www.youtube.com/watch?v=k6dwnr5RDow) by Anne Hege
* [This Is Not A Theremin](https://sofiaitp.wordpress.com/2018/12/04/this-is-not-a-theremin/) by Guillermo Montecinos and Sofía Suazo
* [Eye Conductor](https://andreasrefsgaard.dk/project/eye-conductor/) by Andreas Refsgaard

### Machine Learning for Human Creative Practice
* [Machine Learning for Human Creative Practice](https://vimeo.com/287094397), talk from Dr. Rebecca Fiebrink at Eyeo 2018. 

### ml5.js: Train Your Own Neural Network
* [ml5.js: Train Your Own Neural Network](https://youtu.be/8HEgeAbYphA?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y) (35 min)
* [ml5.js: Save Neural Network Training Data](https://youtu.be/q6cwxORPDo8?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y) (12 min)
* [ml5.js: Save Neural Network Trained Model](https://youtu.be/wUrg9Hjkhg0?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y) (11 min)
* [ml5: Neural Network Regression](https://youtu.be/fFzvwdkzr_c?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y) (10 min)

## Session B: Real-time Data

### Objectives:
* Revisit and examine the concepts of classification and regression as applied to real-time interaction.

### Pose Data as inputs to Neural Network
* 🎥 [ml5.js: Pose Classification with PoseNet and ml5.neuralNetwork()](https://youtu.be/FYgYyq-xqAw?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
    * 💻 [Collect Data](https://editor.p5js.org/codingtrain/sketches/kTM0Gm-1q)
    * 💻 [Load Data](https://editor.p5js.org/codingtrain/sketches/-Ywq20rM9)
    * 💻 [Deploy Model](https://editor.p5js.org/codingtrain/sketches/c5sDNr8eM)
* 🎥 [ml5.js: Pose Regression with PoseNet and ml5.neuralNetwork()](https://youtu.be/lob74HqHYJ0?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
    * 💻 [code all steps](https://editor.p5js.org/codingtrain/sketches/JI_j-PiLk)

### Pixel Data as inputs to Neural Network
* 🎥 [ml5.js: Train a Neural Network with Pixels as Input](https://youtu.be/UaKab6h9Z0I?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
    * 💻 [simple image classifier code](https://editor.p5js.org/codingtrain/sketches/rkonHpec2)

### Face Data
* 💻 [Train regression model model with Face Keypoints](https://editor.p5js.org/ima_ml/sketches/US3ZX6zCD)

### Project References
* [ml5 Playful Examples](https://ml5-fellowship-2020.github.io/examples/) by Andreas Refsgaard
* [Creatability](https://experiments.withgoogle.com/collection/creatability)

### Assignment 4 Due Sunday October 4
1. Watch [Machine Learning for Human Creative Practice](https://vimeo.com/287094397), Dr. Rebecca Fiebrink at Eyeo 2018. Write a response to the following question posed by Dr. Fiebrink:
    * How can machine learning support people's existing creative practices? Expand people's creative capabilities?
2. Dream up and design the inputs and outputs of a real-time machine learning system for interaction and audio/visual performance. This could be an idea well beyond the scope of what you can do in a weekly exercise.
3. Create your own p5+ml5 sketch that trains a model with real-time interactive data. This can be a prototype of the aforementioned idea or a simple exercise where you run this week's code examples with your own data. Here are some exercise suggestions:
    * Try to invent more elegant and intuitive interaction for collecting real-time data beyond clicking buttons?
    * What other real-time inputs might you consider beyond mouse position, image pixels, or face/pose tracking? Could you use real-time sensor data?
    * What other real-time outputs might you consider beyond color or sound modulation? Could the output be a physical computing device? Multiple outputs like R,G,B values?
4. Complete a blog post with your response, real-time ML system, and documentation of your code exercise and [link from the homework wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Assignment-4).
