# Counting-Problem
![image](https://user-images.githubusercontent.com/108604868/177925956-aa47bf00-eef5-4dab-999b-7784b58b8441.png)


In this exercise, we implement the vehicle counting problem by mainly referring to [1]. We first transform each frame from RGB domain to grayscale. With the aid of gaussian blur, the frame can be smooth than before, which curbs the noise. Then, we employ gaussian mixture-based background/foreground segmentation algorithm to achieve the detection of non-stationary object and its shadow. Through morphology, we can readily filter the apparent noise by applying dilation. Next, we identify the contours made by the successive pixel points. Once the center of contour pass the detecting line, we can count the vehicle on the highway. Therefore, the counting problem in the case of vehicles on the highway is resolved by a simple geometric method.




# Reference
[1] CodeWithKiran's Tutorial- Vehicle Detection And Counting using OpenCV: https://www.youtube.com/watch?v=6kZftXunlTY&ab_channel=CodeWithKiran  
[2] Pakorn KaewTraKulPong and Richard Bowden. An improved adaptive background mixture model for real-time tracking with shadow detection. In Video-Based Surveillance Systems, pages 135–144. Springer, 2002.

