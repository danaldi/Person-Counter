# Person-Counter
Custom tensorflow machine learning model used to detect,track and count human on frame. Created using yolov4 and deepsort.


# How to install
  1. Clone this repository
  2. Download checkpoint file :
  3. Unzip weight file on .\yolov4-custom-functions\checkpoints
  4. Install dependencies -> pip3 install -r requirements.txt

---
There is 2 model option to run the person counter. Yolov4 is more accurate but not suitable for developing on mobile and embedded devices due to large computing resources needed to run the model on decent fps. Yolov4-tiny is less accurate but requires small computing resources so that it becomes feasible for developing on mobile and embedded devices.

# Yolov4 demo

on image
![test_yolo jpgdetection1](https://user-images.githubusercontent.com/107688399/174437009-6c059de9-11b4-494e-b906-9579d079eee0.png)

  
on video
https://user-images.githubusercontent.com/107688399/174437016-bb9d0c39-b8e9-45be-a10a-4d8a36acfb0a.mp4


on webcam (without GPU 0.5--0.7 fps)
https://user-images.githubusercontent.com/107688399/174437813-95126db0-f7d0-4a29-80f9-69e014f3fe4e.mp4



# Yolov4-tiny demo : 

on image
![test-tiny jpgdetection1](https://user-images.githubusercontent.com/107688399/174437039-be50b2e7-3a8d-435b-b69a-0c738d93b523.png)

on video
https://user-images.githubusercontent.com/107688399/174437801-13a2c760-ee47-46b3-ba2f-be0e260ca5a0.mp4


on webcam (without GPU 7--8 fps )
https://user-images.githubusercontent.com/107688399/174437847-b3d2eb06-9964-4365-b67c-ff2386054029.mp4



This project would not be posible without these repositories. Huge shoutout to TheAIguysCode and AlexeyAB :
 - https://github.com/theAIGuysCode/yolov4-deepsort
 - https://github.com/AlexeyAB/darknet
  
