# Object Detection Lab

![](assets/clip.gif)

In lab:

* Use *MobileNets* and separable depthwise convolutions.
* Use the SSD (Single Shot Detection) architecture used for object detection
* Use pretrained TensorFlow object detection inference models to detect objects
* Use different architectures and weigh the tradeoffs.
* Apply an object detection pipeline to a video.


### Requirements

Install environment with [Anaconda](https://www.continuum.io/downloads):

```sh
conda env create -f environment.yml
```

Change TensorFlow pip installation from `tensorflow-gpu` to `tensorflow` if you don't have a GPU available.

The environment should be listed via `conda info --envs`:

```sh
# conda environments:
#
carnd-advdl-odlab        /usr/local/anaconda3/envs/carnd-advdl-odlab
root                  *  /usr/local/anaconda3
```

Further documentation on [working with Anaconda environments](https://conda.io/docs/using/envs.html#managing-environments). 

Particularly useful sections:

https://conda.io/docs/using/envs.html#change-environments-activate-deactivate
https://conda.io/docs/using/envs.html#remove-an-environment

### Resources

* TensorFlow object detection [model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)
* [Driving video](driving.mp4)

### Tips
- Some users have reported the driving video as playable only in Jupyter Notebook operating in Chrome browser, and not in media player or Jupyter Notebook operating in other browsers.  In contrast the post-segmentation video appears to be operating accross players and browsers.

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/sbatururimi/object-Detection-mobileNet-ssd/blob/master/LICENSE.md)
