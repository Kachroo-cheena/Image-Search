# Image Search
## Overview

* This model takes a input as an image and gives output the most/exactly similar video from the videos dataset(created on backend)


## Summary

* This code creates a dataset for all the video with their metdata
* Dataset contains vectors(numpy flattened array) of all the frames in a particular video
* Dataset stored in then "vectors.obj" using Pickle.
* "vectors.obj" is futher used for predicting the minimum distance(closely related) video's metadata.
