# torchvideoclf

Video classification using pytorch

The code in this repo is largely a reuse of the pytorch vision video classification code from here https://github.com/pytorch/vision.git

The vision/references/video_classification/train.py in the pytorch repo uses PyAV to process the videos

This repo does not use PyAV but instead use a sequence of image files to create the training dataset.

The downloader downloads videos from youtube as a collection of images and also prepares an annotation file.

The train.py uses the image collections to prepare the training dataset.
