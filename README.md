# Skeleton_Portrait-collection
Intelligent interactive portrait capture system
**First, go to the utilits folder and check that readme * *
Gui. py is a graphical interface that can be run directly, but before running, you need to adjust the path according to the third point below.
Explanation:
1. When performing facial recognition (when opening an image in gui.xpy), it can only be done on real images and cannot be done on the RAF-DB dataset. The reason may be due to differences in image formats or other reasons, as it was not carefully studied.
2. confusion_matrix.py in line 25，the road director of the RAF-DB data collection.
3. Line 28 in image.exe, change the path here to the desired path of the image to be tested.
4. The model used in this article is RepVGG, and the code details can be seen https://github.com/DingXiaoH/RepVGG
5. The dataset used in this article is from RAF-DB, and the website can be found http://www.whdeng.cn/raf/model1.html
6. There is a small bug in the code that causes the program to crash when the face is too close to the camera. The specific reason is currently unclear
7. There is an error message when importing win32ui package in image.exe, but the program runs without any error message. I don't know what the reason is
