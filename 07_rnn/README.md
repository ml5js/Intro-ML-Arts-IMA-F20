# Recurrent Neural Network (RNN)

- [Week 7 RNN Slides](https://docs.google.com/presentation/d/1ujIuPSKzeDLK-D6FRJlVHDsMmWU0Sy8RYZ7_kq3FLVA/edit?usp=sharing)

### Objectives:

- 💡 Learn about Sequential Data and Markov Chains
- 💡 Learn about Recurrent Neural Network architectures
- 💡 Become familiar with use cases for RNNs
- 💡 Learn ml5’s RNN functions and underlying pre-trained models

### Markov Chains

- 🔗 [Markov Chains](http://setosa.io/blog/2014/07/26/markov-chains/) by Victor Powell and Lewis Lehe
- 🔗 [ITP Course Generator by Allison Parrish](http://static.decontextualize.com/toys/next_semester)
- 🔗 [N-Grams and Markov Chains by Allison Parrish](http://www.decontextualize.com/teaching/rwet/n-grams-and-markov-chains/)
- 🔗 [Markov Chains from A2Z](https://shiffman.net/a2z/markov/)
- 🎥 [Markov Chain video tutorial Part 1](https://youtu.be/eGFJ8vugIWA), [Markov Chain video tutorial Part 2](https://youtu.be/9r8CmofnbAQ)
  - 💻[Markov Chain p5.js example](https://editor.p5js.org/ima_ml/sketches/FW9u9zhz0)

### RNNs

- 📚 [The Unreasonable Effectiveness of RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) and [Visualizing and Understanding Recurrent Networks](https://skillsmatter.com/skillscasts/6611-visualizing-and-understanding-recurrent-networks) by by Andrei Karpathy
- 📚 [Rohan & Lenny #3: Recurrent Neural Networks & LSTMs](https://ayearofai.com/rohan-lenny-3-recurrent-neural-networks-10300100899b)

### Related Projects:

- 🍿 [Sunspring](https://arstechnica.com/gaming/2016/06/an-ai-wrote-this-movie-and-its-strangely-moving/)
- 🎨 [Double Agent](http://littlepig.org.uk/installations/doubleagent/index.htm) by Simon Biggs (Drawing)
- 🎨 [Four Experiments in Handwriting with a Neural Network](https://distill.pub/2016/handwriting/) (Drawing)
- 📖 [10 things artificial intelligence did in 2018](http://aiweirdness.com/post/181621835642/10-things-artificial-intelligence-did-in-2018) by Janelle Shane (Text)
- 📖 [Writing with the Machine](https://www.robinsloan.com/notes/writing-with-the-machine/)
- 🎶 [Magenta: Make Music and Art Using Machine Learning](https://magenta.tensorflow.org/)
- 🎨 [Handwriting Generation with RNN and p5.js](http://blog.otoro.net/2017/01/01/recurrent-neural-network-artist/)
- 🎶 [RNN for generating Baroque Music video](https://www.youtube.com/watch?v=SacogDL_4JU)
- 📖 [Let's Read a Story](https://medium.com/ml5js/lets-read-a-story-talking-to-books-using-semantic-similarity-f283168b4264) by Itay Niv

### SketchRNN

- 🎥 [Generating Drawings with SketchRNN code video](https://thecodingtrain.com/CodingChallenges/128-sketchrnn-snowflakes)
  - 💻 [Generating Drawings with SketchRNN code](https://editor.p5js.org/ml5/sketches/SketchRNN_basic)
- 🎥 [Interactive Drawings with SketchRNN video](https://thecodingtrain.com/CodingChallenges/153-interactive-sketchrnn.html)
  - 💻 [Interactive Drawing with SketchRNN code](https://editor.p5js.org/codingtrain/sketches/hcumr-aua)
- 🎥 [RDP Line Simplification](https://thecodingtrain.com/CodingChallenges/152-rdp-algorithm.html)

### charRNN

- 📋 [charRNN reference](https://learn.ml5js.org/#/reference/charrnn)
- 💻 [charRNN examples](https://learn.ml5js.org/#/reference/charrnn?id=examples)
  - 💻 [charRNN generate](https://examples.ml5js.org/p5js/charrnn/charrnn_text/)
  - 💻 [charRNN interactive](https://examples.ml5js.org/p5js/charrnn/charrnn_interactive/)
  - 💻 [charRNN stateful](https://examples.ml5js.org/p5js/charrnn/charrnn_text_stateful/)\_

### LSTM

- 📚 [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) by Christopher Olah

### Assignment 7 Due Sunday October 25

#### Reading

- [What Can Machine Learning Teach Us About Ourselves?](https://medium.com/processing-foundation/what-can-machine-learning-teach-us-about-ourselves-65b268431890), Interview with Emily Martinez, ml5.js Fellow 2020
- [The Subtext of a Black Corpus](https://medium.com/ml5js/the-subtext-of-a-black-corpus-4440de02eb32), In conversation with ITP research fellows Nikita Huggins & Ayodamola Okunseinde by Ashley Lewis

#### Reflection

Emily Martinez proposes a set of questions to ask related to working with a corpus of text data. Pick one (or two) of the questions to reflect on as you respond to the above two readings:

- How can we be more intentional about what we build given the current limitations, problems, and constraints of ML algorithms?
- How do we prepare datasets and set up guidelines that protect the bodies of knowledge of our communities, that honors lineage, that upholds ethical frameworks rooted in shared, agreed-upon values?
- How do we work in consensual and respectful ways with texts by marginalized authors that are not as well-represented, and by virtue of that fact alone, much more likely to be misrepresented, misappropriated, or misunderstood if we are not careful?
- How well can we ensure that the essence of these texts doesn’t dissolve into a word-soup that gets misconstrued?
- Given that so many of the existing “big data” language models are trained with Western texts and proprietary datasets, what does it even mean to try to decolonize AI?
- Who do we entrust to do this work?
- How do we deal with credit and attribution of our new creations?
- How do we really do ethics with machine learning?
- How do we get through this whole list of concerns and still build AI that is fun, respectful, tender, pleasurable, kind?

#### Coding Exercise

Pick from one of the following options (or invent your own) related to working with sequential data and recurrent neural networks.

- Text generation

  - Generate text with [a markov chain](https://editor.p5js.org/ima_ml/sketches/FW9u9zhz0).
  - Generate text with one of the provided [pre-trained charRNN models](https://github.com/ml5js/ml5-data-and-models/tree/main/models/charRNN). Reminder: these examples do not run in the p5 web editor! This [workflow series](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zu_uqEA6NqhLzKLACwU74X) may help! [Download the charRNN code examples here](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/tree/main/07_rnn/charRNN-examples).
  - Train your own model! [Instructions can be found in the training-charRNN](https://github.com/ml5js/training-charRNN/blob/main/README.md) repo, however proceed with caution! There are so many errors that can arise due to python versions and other configuration settings required. You are also welcome to email me (Dan) your text file and I will train the model for you.

- Doodle generation

  - Experiment with generating doodles with the [sketchRNN](https://ml5js.org/reference/api-SketchRNN/) model. What kinds of interactions result from [drawing with the model](https://editor.p5js.org/codingtrain/sketches/hcumr-aua)?

- Music generation!

  - We did not cover this in class, but recurrent neural networks can also be used the generate musical sequencies (melodies, beats, etc.). You can find examples for [musical markov chains](https://luisaph.github.io/the-code-of-music-2018/#Markov) and [musical recurrent neural networks](https://luisaph.github.io/the-code-of-music-2018/#NN) as part of Luisa Pereira's [Code of Music materials](https://luisaph.github.io/the-code-of-music-2018/).

Complete a blog post with your reading reflection and documentation of your code exercise. [Link from the homework wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Assignment-7).
