# **Finding Lane Lines on the Road** 

## Writeup



---

**Finding Lane Lines on the Road**

The goals of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report
---

### Reflection

### 1. Steps used to create pipeline
 1. Read in and grayscale the image
 2. Used gaussian smoothing to blurred the image
 3. Used **Auto Canny Edge Detection** algorithm which saved time required for parameter tuning
 4. Masked only area of interest on the image
 5. Used hough transformation 
 6. Drew detected line on image




### 2. Potential shortcomings with your current pipeline
Major shortcoming of my algorithm pipeline is robustness. It only detects lane lines in ideal conditions such as when lane lines are starting form bottom of image. When lane is curving and image dynamics changes, my pipeline detects lane line where contrast in the image is changing such as guderails of roads. 

### 3. Possible improvements to your pipeline
1. I was not able to use **Auto Canny Edge Detection** algorithm in challenge quetion, being able to implement Auto Canny Edge Detection might improve results
2. Parameters tuning technique
3. Used advanced algorithm
