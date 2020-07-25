# object_detection_with_yolo_tiny_v3

Performed real time object detection in videos using YOLO algorithm by using openCV to process the video frame by frame .
Each frame is forward passed through a pretrained YOLOv3-tiny model to detect multiple objects in the frame .
Certain boxes are eliminated on the basis of low confidence scores and then used non_max_supression to eliminate overlapping boxes which detect the same object by using an iou_threshold. 
Finally bounding boxes are drawn around the detected object along with confidence scores using openCV . 
