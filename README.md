# Inception-Egocentric

This serves as my journey to utilize Inception v3 that's build on top of Google's TensorFlow for image classification.  The end objective of this work is to be able to automatically do a summarization of a person's daily routine through their egocentric (lifelogging) image captures.

The planned activities are (which are made as folder in this repository as that's how I will be processing the labelled images - in other words, the images for each label will be in their respective folder):

* Eating
* Meeting 
* Socializing
* Washing / Bathroom
* House Chores (At home with no other unexpected person)
* Playing
* Working

# TensorFlow

According to the documentation, TensorFlow should be built from scratch but I started with using the pip installed version.

# Inception v3

# Dataset
## TFRecord

Will need to know what is this format but there is a script provided to convert ImageNet data to TFRecord.

https://github.com/tensorflow/models/blob/master/inception/inception/data/download_and_preprocess_imagenet.sh

## Initial Dataset

Finding the Dataset that John See informed me about.

The initial dataset used is a 4k plus images from University of Barcelona (Bolaños, Marc, and Petia Radeva. "Ego-object discovery." arXiv preprint arXiv:1504.01639 (2015).)

I used the datasets from subject_1 and labelled (put into respective folder) them into two categories, "indoor" and "outdoor".  The total number of images for this test stage is slightly more than 1.3k images.

Using the instructions found on (https://github.com/tensorflow/models/blob/master/inception/README.md#how-to-construct-a-new-dataset-for-retraining)

Rearranged the folders accordingly.  Need to clean up this documentation.

