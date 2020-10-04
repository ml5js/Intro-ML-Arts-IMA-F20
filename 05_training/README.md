# DIY Neural Network

## Session A: Data Collection

### Objectives:
* Review the full story of building a ML model for classification or regression.
* Understand how data is formatted and downloaded including CSV and JSON.
* Consider how to frame the problem and collect data.
    * Understand critical questions to ask (e.g. Who is this for? What’s the context?)
    * Understand the questions to ask about sourcing and collecting data.
    * Learn how to prepare a data set, including how to normalize and properly format it.
* Diagram the components of a two layer "vanilla" neural network.

### Tutorials
* Tabular Data (CSV)
   * [Tabular Data](https://youtu.be/RfMkdvN-23o) from Coding Train "Data + APIs" tutorial (lots of extra stuff here the first few minutes is probably most relevant?)
   * [Tabular Data](https://youtu.be/woaR-CJEwqc) Coding Train Processing tutorial (code is not JS!)
* JSON Data
   * [What is JSON Part 1](https://youtu.be/_NFkzw6oFtQ) - Coding Train p5.js tutorial
   * [What is JSON Part 2](https://youtu.be/118sDpLOClw) - Coding Train p5.js tutorial
   * [JSON Data](https://youtu.be/uxf0--uiX0I) from Coding Train "Data + APIs" tutorial (same as above, lots of extra unrelated stuff here).

### Related Projects
* [Feminist Data Set](https://carolinesinders.com/feminist-data-set/) by Caroline Sinders
* [Gender Shades: How well do IBM, Microsoft, and Face++ AI services guess the gender of a face?](http://gendershades.org/) by Joy Buolamwini and Timnit Gebru

### Reading and Viewing
* [This is how AI bias really happens—and why it’s so hard to fix](https://www.technologyreview.com/s/612876/this-is-how-ai-bias-really-happensand-why-its-so-hard-to-fix/) by Karen Hao
* Video: [Analyzing & Preventing Unconscious Bias in Machine Learning](https://www.infoq.com/presentations/unconscious-bias-machine-learning) by Rachel Thomas
* Video: [Data visualization for machine learning](https://vimeo.com/304131671)

## Session B: Training the Model

### Objectives:
* Learn steps to construct a vanilla neural network and train a classification model with ml5.js.
* Review Neural Network architecture
    * Activation Functions
* Review the terminology of the training process
    * Training
    * Learning Rate
    * Epochs
    * Batch size
    * Loss
* Understand the difference between training and inference

### Color Classifier
* [Full Coding Train Video Series using TensorFlow.js](https://youtu.be/y59-frfKR58?list=PLRqwX-V7Uu6bmMRCIoTi72aNWHo7epX4L), 7.1-7.5 cover how the data was collected and cleaned
* [Crowdsourcing Colors website](https://codingtrain.github.io/CrowdSourceColorData/index.html), [Crowdsourcing Colors source code](https://github.com/CodingTrain/CrowdSourceColorData)

### ml5.js examples
* [ml5 temporary build template](https://editor.p5js.org/ima_ml/sketches/A7vSIICpf)
* [Color Classifer](https://editor.p5js.org/ima_ml/sketches/WOLz4pub3)

### Assignment 5 Due Sunday October 11

1. Find a dataset that interests you. Some ideas:
    * Something you find online. For example, take a look at [Kaggle](https://www.kaggle.com/) and you can find a list of datasets we've compiled on the [dataset wiki](https://github.com/ml5js/Intro-ML-Arts-IMA/wiki/Datasets).
    * Find a dataset that you collect yourself or is already being collected about you. For example, personal data like steps taken per day, browser history, minutes spent on your mobile device, sensor readings, and more.
    * A dataset that you collect by crowdsourcing data. One way to approach this is to create a google form with questions and ask friends and fellow students to complete the form.
2. After you have found or collected your dataset, write a blog post that addresses these questions:
    * What is (are!) the data?
    * What format is the data in? (CSV, JSON, PDF, or . . )
    * What are the dimensions of the data (rows and columns)?
    * What are the "variables" (also known as "data items"). In a CSV these would be the column headings. Do you recognize the data types (numbers, strings, images, etc.)?    
    * Is there missing, incorrect, or otherwise problematic data?
    * How and why was this data collected?
    * For whom is this data accurate or useful? What is this data *unrepresentative* of? (Who is missing and left out of the data?)
    * Knowing what you know now about machine learning, what will a model trained on this data help you do? Are there are alternative (non-machine learning) methods you could use instead?
3. Coming soon!