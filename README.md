# Soft biometric trait based person identification

Following is a part of research work carried out at [BISAG](https://bisag-n.gov.in/), Gandhinagar.

## Introduction

The data was collected in conjunction with an experience-based long-run exhibition of video-based gait analysis at a research facility. The approved informed consent was obtained from all the subjects in this dataset. The dataset consists of 50 subjects (38 males and 12 females with age ranging from 20 to 22 years) from a single view angle (90°). Gait images of 1,280 x 720 pixels at 25 fps are captured by a network camera placed at  90-deg azimuth angle along a quarter of a circle whose center coincides with the center of the walking course. Its radius is approximately 10 m and height is approximately 2 m.  

The subject repeats forward (A to B) and backward (B to A) walking thrice of each, 6 gait image sequences (2 (forward and backward) x 3 (thrice)) can be captured per one subject. The view angle and experiment setup of the dataset is defined as follows. 

<img src="https://github.com/JUGALHKEDIA/Soft-biometric-trait-based-person-identification/blob/main/Experiment%20setup.png" alt="Experiment setup" style="width: 25%; height: 25%">

## Dataset: 

The entire dataset is private. Processed [binary silhouettes](https://drive.google.com/file/d/1xKyrxciKWBoV5CpcVe7Jv_NQSkrVdSg8/view?usp=share_link) are open source and freely available.

*Example(id-10): video gait to frame-by-frame processed binary*

<img src="https://github.com/JUGALHKEDIA/Soft-biometric-trait-based-person-identification/blob/main/example.gif" alt="example of video gait to frame-by-frame processed binary" style="width:100%">


Further these binary sillhouettes are processed capturing intended region "walking person" and size normalized to 88 x 122 pixel (Width x Height) dimension. These cropped silhouettes are available [here](https://drive.google.com/file/d/1dzgReYswXsfMLWeAf01fktpa6cxPe4Yg/view?usp=sharing).

<img src="https://github.com/JUGALHKEDIA/Soft-biometric-trait-based-person-identification/blob/main/silhouette2cropsilhouette.png" alt="silhouette2cropsilhouette" style="width:100%"> 

Once the cropped silhouettes are obtained, any model free gait representation method can be applied. Following is an example for generating Gait Energy Image (GEI) from the processed silouetttes.

<img src="https://github.com/JUGALHKEDIA/Soft-biometric-trait-based-person-identification/blob/main/toGEI.gif" alt="toGEI" style="width:100%">

