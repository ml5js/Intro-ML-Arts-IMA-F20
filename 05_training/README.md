# DIY Neural Network

## Session A: Data Collection

### Objectives:
* Review the full story of building a ML model for classification or regression.
* Understand how data is formatted and downloaded including CSV and JSON.
* Review Neural Network architecture
    * A Single Perceptron
    * Activation Functions
    * Diagram the components of a simple multi-layered perceptron (XOR)
* Review the terminology of the training process
    * Training
    * Learning Rate
    * Epochs
    * Batch size
    * Loss

### Tutorials
* Tabular Data (CSV)
   * [Tabular Data](https://youtu.be/RfMkdvN-23o) from Coding Train "Data + APIs" tutorial (lots of extra stuff here the first few minutes is probably most relevant?)
   * [Tabular Data](https://youtu.be/woaR-CJEwqc) Coding Train Processing tutorial (code is not JS!)
* JSON Data
   * [What is JSON Part 1](https://youtu.be/_NFkzw6oFtQ) - Coding Train p5.js tutorial
   * [What is JSON Part 2](https://youtu.be/118sDpLOClw) - Coding Train p5.js tutorial
   * [JSON Data](https://youtu.be/uxf0--uiX0I) from Coding Train "Data + APIs" tutorial (same as above, lots of extra unrelated stuff here).

### Perceptron
* [Perceptron Video](https://youtu.be/ntKn5TPHHAk), [Perceptron p5.js code](https://editor.p5js.org/natureofcode/sketches/HkJ0cRmux)
* [Perceptron Slides](https://drive.google.com/file/d/1io05Uzpb9BclWzXyvB6wEj_Zu4uI_hOX/view?usp=sharing)
* [Neural Networks (Nature of Code Chapter 10)](http://natureofcode.com/book/chapter-10-neural-networks/)

### Color Classifier
* [Full Coding Train Video Series using TensorFlow.js](https://youtu.be/y59-frfKR58?list=PLRqwX-V7Uu6bmMRCIoTi72aNWHo7epX4L), 7.1-7.5 cover how the data was collected and cleaned
* [Crowdsourcing Colors website](https://codingtrain.github.io/CrowdSourceColorData/index.html), [Crowdsourcing Colors source code](https://github.com/CodingTrain/CrowdSourceColorData)

### ml5.js examples
* [Color Classifer JSON Data](https://editor.p5js.org/ima_ml/sketches/WOLz4pub3)
* [Color Classifier CSV Data](https://editor.p5js.org/ima_ml/sketches/8eskYqyhA)

## Session B: What is (are!) Data?

### Objectives:
* Consider how to frame the problem and collect data.
    * Understand critical questions to ask (e.g. Who is this for? What’s the context?)
    * Understand the questions to ask about sourcing and collecting data.
    * Learn how to prepare a data set, including how to normalize and properly format it.

### Guest presentation from Lydia Jessup!
* [Data Wrangling Intro slides](https://docs.google.com/presentation/d/1dPB75F-BEjhtHour7_b7b4UidKQ6vGIAOibvUlgg4EA/edit)
* [Data Discussion Slides](https://docs.google.com/presentation/d/12X2pyI_PlnYxQmRVNIC58_ExsjObkjFOx-XTmQe2vQg/edit#slide=id.g9e5bd34682_0_120)
* [311 Call ml5.js example](https://editor.p5js.org/lydiajessup/sketches/NQ6iRoAM2)

### Related Projects
* [Feminist Data Set](https://carolinesinders.com/feminist-data-set/) by Caroline Sinders
* [Gender Shades: How well do IBM, Microsoft, and Face++ AI services guess the gender of a face?](http://gendershades.org/) by Joy Buolamwini and Timnit Gebru

### Assignment 5 Due Sunday October 11

1. Find a dataset that interests you and link to it from [the assignment 5 wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Assignment-5#for-wednesday-oct-7-complete-step-1-of-weeks-assignment) Some ideas:
    * Something you find online. For example, take a look at [Kaggle](https://www.kaggle.com/) and here is a list of [datasets compiled last year](https://github.com/ml5js/Intro-ML-Arts-IMA/wiki/Datasets).
    * Find a dataset that you collect yourself or is already being collected about you. For example, personal data like steps taken per day, browser history, minutes spent on your mobile device, sensor readings, and more.
    * A dataset that you collect by crowdsourcing data. One way to approach this is to create a google form with questions and ask friends and fellow students to complete the form.
After you have found or collected your dataset, write a blog post that addresses these questions:
    * Who collected and compiled it?
    * Why was it collected?
    * How was it collected?
    * Describe the data: What are the dimensions? What are the variables and their data types? What can the first 5-20 rows tell us?
    * Is there missing, incorrect, or otherwise problematic data?
    * For whom is this data accurate or useful? What is this data *unrepresentative* of? (Who is missing and left out of the data?)
    * Knowing what you know now about machine learning, what will a model trained on this data help you do? Are there are alternative (non-machine learning) methods you could use instead?
    
2. TBD
