# PoseNet Demos

## Contents

### Demo 1: Camera

The camera demo shows how to estimate poses in real-time from a webcam video stream and find most similar image among images defined in img and json folders. If you want to add more images, please add image and json file of poses to those folder. 

<img src="https://github.com/masa3141/move_mirror/move_mirror.gif" alt="cameraDemo" style="width: 600px;"/>


### Demo 2: Coco Images

The [coco images](http://cocodataset.org/#home) demo shows how to estimate poses in images. It also illustrates the differences between the single-person and multi-person pose detection algorithms.
Also you can download the json file of pose positions. If you want to add your images, please add those to img folder and write image name in coco.js. 

<img src="https://raw.githubusercontent.com/tensorflow/tfjs-models/master/posenet/demos/coco.gif" alt="cameraDemo" style="width: 600px;"/>


## Setup

Install dependencies and prepare the build directory:

```sh
yarn
```

To watch files for changes, and launch a dev server:

```sh
yarn watch
```
