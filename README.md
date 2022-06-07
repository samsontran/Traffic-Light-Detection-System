# Traffic-Light-Detection-System

With autonomous vehicles becoming a thing of the present, it is important to research and develop ways to improve their performance for the safety of passengers and pedestrians. For this project, I explore how these vehicles can use live-stream videos to recognize traffic lights and understand when to stop or continue moving when they approach an intersection. 



This project explores using a deep learning model called YOLOv5 to detect and classify 
A deep learning approach using the YOLOv5 model to detect and classify traffic lights in photos and videos as red, yellow, green, and black (ie. not illuminated.

![alt text](https://github.com/samsontran/Traffic-Light-Detection-System/blob/main/traffic_light_detect.jpg)

[![]https://github.com/samsontran/Traffic-Light-Detection-System/blob/main/traffic_light_detect.mp4](https://user-images.githubusercontent.com/90397706/172431838-4272df76-5f9e-40ef-a2ed-527bdf66aa1e.mov)

To do this, I implement a deep-learning model called YOLOv5 model, developed by Ultralytics (https://github.com/ultralytics/yolov5). This model is used widely to solve image detection problems because of its rapid processing, detection, and classification time. Its algorithm works by dividing each image into N grids, each having an equal dimensional region of SxS. Each of these N grids is responsible for the detection and localization of the object it contains. Correspondingly, these grids predict B bounding box coordinates relative to their cell coordinates, along with the object label and probability of the object being present in the cell. This process greatly lowers the computation as both the detection and recognition can be done simultaneously in one-stage. 
