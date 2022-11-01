# Object detection in an urban environment

In this project, you will learn how to train an object detection model using the [Tensorflow Object Detection API](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/index.html) and [AWS Sagemaker](https://aws.amazon.com/sagemaker/). At the end of this project, you will be able to generate videos such as the one below. 

<p align="center">
    <img src="data/animation.gif" alt="drawing" width="600"/>
</p>

## Installation

<INSERT SAGEMAKER LAUNCH INSTRUCTIONS>

Once you have accessed the Sagemaker console, you can launch a notebook instance and clone this repository. The `conda_tensorflow2_p38` kernel contains most of the required packages for this project. The notebooks contain lines for manual installation when required.

## Usage

This repository contains two notebooks:
* [1_train_model](1_model_training/1_train_model.ipynb): this notebook is used to launch a training job and create tensorboard visualizations. 
* [2_deploy_model](2_run_inference/2_deploy_model.ipynb): this notebook is used to deploy your model, run inference on test data and create a gif similar to the one above.


## Useful links
* The Tensorflow Object Detection API tutorial is a great resource to debug your code. This [section](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html#configure-the-training-pipeline) in particular will teach you how to edit the `pipeline.config` file to update
your training job.

* [This blog post](https://aws.amazon.com/blogs/machine-learning/training-and-deploying-models-using-tensorflow-2-with-the-object-detection-api-on-amazon-sagemaker/) teaches how to label data, train and deploy a model with the Tensorflow Object Detection API and AWS Sagemaker.
