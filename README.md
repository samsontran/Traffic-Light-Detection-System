# Traffic-Light-Detection-System

With autonomous vehicles becoming a popular technology in our society, it is important to research and develop ways to improve their performance for the safety of passengers and pedestrians. For this project, I explore how these vehicles can apply computer vision techniques through incoming videos to recognize traffic lights. This can eventually help these systems learn when to stop or continue moving as they approach an intersection with a green, red or yellow light. 

![00244_1](https://user-images.githubusercontent.com/90397706/173420269-3ac644c4-f30d-499e-878e-7e8fc30c67dc.jpg)

[![]https://github.com/samsontran/Traffic-Light-Detection-System/blob/main/traffic_light_detect.mp4](https://user-images.githubusercontent.com/90397706/172431838-4272df76-5f9e-40ef-a2ed-527bdf66aa1e.mov)

To do this, I implement a deep-learning model called YOLOv5 model, developed by Ultralytics (https://github.com/ultralytics/yolov5). This model is used widely to solve image detection problems because of its rapid processing, detection, and classification time. Its algorithm works by dividing each image into N grids, each having an equal dimensional region of SxS. Each of these N grids is responsible for the detection and localization of the object it contains. Correspondingly, these grids predict B bounding box coordinates relative to their cell coordinates, along with the object label and probability of the object being present in the cell. This algorithm greatly lowers the computation as both the detection and recognition can be done simultaneously in one-stage. 
