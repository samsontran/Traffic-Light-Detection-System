# Traffic-Light-Detection-System

A deep learning approach using the YOLOv5 model to detect and classify traffic lights in photos and videos as red, yellow, and green.



This approach first performs a segmentation task, where all traffic lights are detected with bounding boxes. For all illuminated traffic lights, the model then identifies their color as red, green or yellow. This project will be beneficial for autonomous driving vehicle applications 

I implement the YOLOv5 model (developed by ultralytics - https://github.com/ultralytics/yolov5), because it can processes images, detect objects and classify objects rapidly. Its algorithm works by dividing each image into N grids, each having an equal dimensional region of SxS. Each of these N grids is responsible for the detection and localization of the object it contains. Correspondingly, these grids predict B bounding box coordinates relative to their cell coordinates, along with the object label and probability of the object being present in the cell. This process greatly lowers the computation as both detection and recognition can be done simultaneously. 
