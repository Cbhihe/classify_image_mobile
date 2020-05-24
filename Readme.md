# classify_image_mobile

Source:
https://codelabs.developers.google.com/codelabs/tensorflowjs-teachablemachine-codelab/index.html#0


## Introduction:
We  build a simple "teachable machine", a custom image classifier that
can be trainsed  on the fly in the browser using TensorFlow.js, a powerful
and flexible machine learning library for Javascript.  We first load and
run a popular pre-trained model called MobileNet for image classification
in the browser. we then use "transfer learning" to bootstrap NN training
with the pre-trained MobileNet model and customizes it.

If you need an introduction or refresher, consider watching:
 - a video by 3blue1browns:
     https://www.youtube.com/watch?v=aircAruvnKk
 - a video on Deep Learning in Javascript by Ashi Krishnan.
     https://www.youtube.com/watch?v=SV-cgdobtTA

## To know more
 - about tensorflow applications based on inference, derived from (pretrained)
 transfer models ported to mobile platform, check out:
https://beta.observablehq.com/@nsthorat/how-to-build-a-teachable-machine-with-tensorflow-js

## Objective
 - load pretrained MobileNet model and make a prediction on new data
 - make predictions through the webcam
 - use intermediate activations of MobileNet to do transfer
   learning on a new set of classes you define on the fly with the webcam

## Requirements:
if you want to modify the code, you will need:
 - a text editor, either running locally on your machine or terminal
 - some knowledge of HTML, CSS, JavaScript, and your browser's devtools
 - a high-level conceptual understanding of Neural Networks

## Trials:
To run the webpage, simply open 'index.html' in a Web Browser. If you use
the cloud console, simply refresh the preview page.

Downloading the model may take a few seconds.

