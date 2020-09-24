# Applications of Machine Learning models

## Session A: Other pre-trained models

### Objectives:
* Understanding how to use pre-trained models other than image classification.
* Ability to work with PoseNet and ml5.js
* Ability to work with Object Detection Models (CoCoSSD).
* Ability to work with Image Segmentation models (UNet and BodyPix) and ml5.js.
* [Week 3 Slides](https://docs.google.com/presentation/d/1kOjvIWjsCKYPEuS3lUjg3jYWGXiFIuCOvU6JUq_ESmo/edit?usp=sharing)

### Models
* [PoseNet](https://ml5js.org/reference/api-PoseNet/)
    * Read [Real-Time Human Pose Estimation in the Browser with TensorFlow.js](https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5) by Dan Oved, with editing and illustrations by Irene Alvarado and Alexis Gallo.
* Object Detection (documentation in progress)
* [UNet](https://learn.ml5js.org/#/reference/unet)
    * Trained by [Zaid Alyafeai](https://github.com/zaidalyafeai) using [mut1ny - Face/Head segmentation dataset](http://www.mut1ny.com/face-headsegmentation-dataset)
* [BodyPix](https://learn.ml5js.org/#/reference/bodypix)
    * [Introducing BodyPix: Real-time Person Segmentation in the Browser with TensorFlow.js](https://medium.com/tensorflow/introducing-bodypix-real-time-person-segmentation-in-the-browser-with-tensorflow-js-f1948126c2a0)

### ml5 video tutorials
* [ml5.js Pose Estimation with PoseNet](https://youtu.be/OIo-DIOkNVg?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y), [code](https://editor.p5js.org/codingtrain/sketches/ULA97pJXR)

### ml5 code editor examples
* [PoseNet Webcam Part Selection](https://editor.p5js.org/ml5/sketches/PoseNet_part_selection)
* [PoseNet Webcam Full Skeleton](https://editor.p5js.org/ml5/sketches/PoseNet_webcam)
* [PoseNet Single Image](https://editor.p5js.org/ima_ml/sketches/Gq9bIvoW1)
* [Object Detection - CoCoSSD](https://editor.p5js.org/ima_ml/sketches/5oQlIcPj2)
* [UNet Image Segmentation](https://editor.p5js.org/ml5/sketches/UNET_webcam)
* [BodyPix Image Segmentation](https://editor.p5js.org/ml5/sketches/5kF2Kokx9)

### Related Projects
* [Maya Man's PoseNet sketchbook](https://mayaontheinter.net/posenetsketchbook/), [Body, Movement, Language: A.I. Sketches with Bill T. Jones](https://mayaontheinter.net/bodymovementlanguage/)
* [PoseNet Whack a Mole](https://vibertthio.com/posenet-whack-a-mole/) by Vibert Thio
* [Sidewalk Orchestra](https://twitter.com/c_valenzuelab/status/979131716907536384) by Cristóbal Valenzuela
* [Pose Music](https://codepen.io/teropa/full/QxLrMp/) by Tero Parviainen
* [The Treachery of Sanctuary](https://www.youtube.com/watch?v=I5__9hq-yas&feature=youtu.be) by Chris Milk
* [Gait Analysis](https://www.runnersneed.com/expert-advice/gear-guides/gait-analysis.html) from runnersneed

## Session B

### Data and Model Biographies
* [Slides from Ellen Nickles](https://docs.google.com/presentation/d/1Ta8oen66-WgrShq4SdAl_hQ1DZnEWoOdC1wMGlIlswM/edit#slide=id.p)
* [The Future Is Here!](https://thephotographersgallery.org.uk/whats-on/digital-project/mimi-onuoha-future-here), a commission for The Photographers’ Gallery which examines the process of dataset creation by Mimi Ọnụọha
* [Feminist Data Set](https://carolinesinders.com/wp-content/uploads/2020/05/Feminist-Data-Set-Final-Draft-2020-0526.pdf) tool kit to interrogate every step of the AI process by Caroline Sinders
* [Ted Talk: The era of blind faith in big data must end](https://www.youtube.com/watch?v=_2u_eHHzRto) and Cathy O'Neil's [Risk Consulting & Algorithmic Auditing firm](https://orcaarisk.com/)

### Assignment 3, due Monday Sept 28:
2. Read [Mixing movement and machine](https://medium.com/artists-and-machine-intelligence/mixing-movement-and-machine-848095ea5596) by Maya Man
3. Read [Humans of AI](https://humans-of.ai/editorial) by Philipp Schmitt
4. Pick [one of the models described in Ellen Nickles slides](https://docs.google.com/presentation/d/1Ta8oen66-WgrShq4SdAl_hQ1DZnEWoOdC1wMGlIlswM/edit#slide=id.p) (PoseNet, UNET, BodyPix, CoCoSSD) and following the examples above and the [ml5.js documentation](http://learn.ml5js.org/) and experiment with controlling elements of a p5.js sketch (color, geometry, sound, text) with the output of the model. (You may also choose a ml5.js model not covered in Ellen's slides)
5. Read the [Model and Data Biography](https://docs.google.com/presentation/d/1Ta8oen66-WgrShq4SdAl_hQ1DZnEWoOdC1wMGlIlswM/edit#slide=id.p) for the model you picked and consider the following:
   * What questions do you still have about the model and the associated data? Are there elements you would propose including in the biography? 
   * How does understanding the provenance of the model and its data inform your creative process?
6. Document your response to the Data and Model biographies as well as your p5.js sketch in a blog post and add a link to the post / your p5 sketch on the [Assignment 3 Wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Assignment-3). In your blog post, include visual documentation such as a recorded screen capture / video / GIFs of your sketch.
