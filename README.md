# Speed-Monitoring-using-YOLO


## Prerequisite

Since we're using YOLO algorithm whose pretrained model is available in darknet.

`https://pjreddie.com/darknet/yolo/
`
Download darknet and yolo pretrained weights.

## Run
`cd darknet`

`python3 framedivide.py` to extract frames from the video.

Put frame to be detected in `data` folder of `darknet` folder.

`./darknet detect cfg/yolov3.cfg yolov3.weights data/frame%d.jpg`
