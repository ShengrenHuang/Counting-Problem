# Counting-Problem
![image](https://user-images.githubusercontent.com/108604868/177925956-aa47bf00-eef5-4dab-999b-7784b58b8441.png)


In this exercise

在本程式中，我們主要參考[1] 的方法，首先針對每一幀將其從RGB轉到灰階，利用高斯模糊平滑圖片，以此去除雜訊，接著利用基於混合高斯分佈 [2] 做運動物體偵測與其shadow偵測，透過形態學膨脹與侵蝕，將顯著的雜點消除。偵測多點像素所連接的輪廓，設置一條偵測線，當輪廓中心通過偵測線，則代表有物件通過，因此就能實現利用幾何方法的counting problem。



# Reference
[1] CodeWithKiran's Tutorial- Vehicle Detection And Counting using OpenCV: https://www.youtube.com/watch?v=6kZftXunlTY&ab_channel=CodeWithKiran  
[2] Pakorn KaewTraKulPong and Richard Bowden. An improved adaptive background mixture model for real-time tracking with shadow detection. In Video-Based Surveillance Systems, pages 135–144. Springer, 2002.

