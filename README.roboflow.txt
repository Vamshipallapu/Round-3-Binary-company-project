
car dent detection - v10 2022-10-09 6:18pm
==============================

This dataset was exported via roboflow.com on October 9, 2022 at 12:49 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 197 images.
Dent are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Randomly crop between 0 and 24 percent of the image
* Random rotation of between -28 and +28 degrees
* Random shear of between -25° to +25° horizontally and -20° to +20° vertically
* Random brigthness adjustment of between -22 and +22 percent
* Random exposure adjustment of between -22 and +22 percent
* Random Gaussian blur of between 0 and 1.5 pixels
* Salt and pepper noise was applied to 2 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* 50% probability of horizontal flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -15 and +15 degrees
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically


