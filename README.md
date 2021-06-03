# Yolov4 trained on IDD Detection Dataset

IDD Detection YOLOv4 Model

Install https://github.com/AlexeyAB/darknet

Download IDD pretrained model from [here](https://drive.google.com/file/d/1z4CjabgRiFXMXatBPDHvZiTdw3cSgBBM/view?usp=sharing)

```
Val data scores:-

$ ./darknet detector map idd.data idd.cfg idd_best.weights

detections_count = 751335, unique_truth_count = 126060  
class_id = 0, name = bicycle_0, ap = 54.27%      (TP = 287, FP = 136) 
class_id = 1, name = bus_1, ap = 76.93%          (TP = 3446, FP = 830) 
class_id = 2, name = traffic sign_2, ap = 46.60%         (TP = 1900, FP = 1153) 
class_id = 3, name = train_3, ap = 0.00%         (TP = 0, FP = 0) 
class_id = 4, name = motorcycle_4, ap = 71.09%           (TP = 16910, FP = 6051) 
class_id = 5, name = car_5, ap = 75.11%          (TP = 17403, FP = 5700) 
class_id = 6, name = traffic light_6, ap = 38.58%        (TP = 284, FP = 117) 
class_id = 7, name = person_7, ap = 61.08%       (TP = 10155, FP = 3737) 
class_id = 8, name = vehicle fallback_8, ap = 9.87%      (TP = 571, FP = 1466) 
class_id = 9, name = truck_9, ap = 67.98%        (TP = 4535, FP = 2081) 
class_id = 10, name = autorickshaw_10, ap = 76.69%       (TP = 5460, FP = 1404) 
class_id = 11, name = animal_11, ap = 30.32%     (TP = 397, FP = 287) 
class_id = 12, name = caravan_12, ap = 0.00%     (TP = 0, FP = 0) 
class_id = 13, name = rider_13, ap = 59.80%      (TP = 14084, FP = 6145) 
class_id = 14, name = trailer_14, ap = 0.00%     (TP = 0, FP = 0) 

 for conf_thresh = 0.25, precision = 0.72, recall = 0.60, F1-score = 0.65 
 for conf_thresh = 0.25, TP = 75432, FP = 29107, FN = 50628, average IoU = 57.32 % 

 IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
 mean average precision (mAP@0.50) = 0.445554, or 44.56 %
Total Detection Time: 410 Seconds

```
