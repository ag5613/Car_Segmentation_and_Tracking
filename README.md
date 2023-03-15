# Car_Segmentation_and_Tracking
Real time Segmentation and Tacking on Car and Truck

Trained Yolov7 image segmentation model for car and truck vehicle. Along with segmentation object-tracking using ClassySORT is also implemented. 


To execute the code and perform the inference on video run the following command:

```
python predict.py --source traffic_video.mp4 --weights yolov7-seg.pt --nosave --view-img --trk
```

use 0 for input using webcam. 

nosave is used to restrict the video to be saved 
view-img is used to show the output on the screen
trk is used to perform the tracking using ClassySORT 















Source :  https://github.com/WongKinYiu/yolov7