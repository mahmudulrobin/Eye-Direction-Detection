# Eye-Direction-Detection-

Problem Description:

Eye Direction Detection is basically a part of human life because while we talk with other person we have to eye contact with them. Without that in case of suspicious movement one basic symptom is frequently movement of iris. So, for identifying that one have to detect the eye first and then the direction of that eye.
This paper is concerned with the reliable detection and detection of Eye and its direction.



Dataset Description:

Eye Direction Detection from image

1.	Number of instances: There are total 5 images containing face.
2.	Dimensions: The dimension of each images are 1000 x 1500, 2250 x 1500, 3642 x 3344, 1000 x 1500, and 1000 x 1500.


Description of the Process:

There are various ways to detect the direction that one person is looking at. First of all, we took an input image, then made a gray scale image. Then we have applied Viola Jones Method which crop out the pair of eyes from a particular picture. Then we applied Hough transformation method which crop out a single eye from the pair of eye. Finally we have calculated the distance from the center of the pupil to identify whether the person is looking at right or left. If not then the person is described as he’s staring straight.


Process
Input Image:
We have taken High resolution input of images.

Gray Scale image: 
A grayscale (or gray level) image is simply one in which the only colors are shades of gray. The reason for differentiating such images from any other sort of color image is that less information needs to be provided for each pixel. We have used rgb2gray function for this process.


Direction Detection:

•	We have taken the center of Iris. 
•	From the center we have calculated the distance of left and right from the center.
•	Finally checking whether left distance is bigger than right or right distance is bigger than left.
•	If left distance is larger than right then we declared the person is staring at right and vice versa.


Discussion
The goal of this project is to identify the direction of the eye. We have successfully identified the direction. We have also spotted if the person is staring at straight. Finally we have plotted all the images.
		















