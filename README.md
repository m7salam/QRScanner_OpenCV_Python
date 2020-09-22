# QRScanner_OpenCV_Python

#GIF of it in action
![barcode scanner](https://user-images.githubusercontent.com/12870986/93849103-daf9d700-fcdd-11ea-8268-149a491b4f12.gif)

Make sure to change in drone.py or the other files to the source of your camera
for example:

```

change that vs = cv2.VideoCapture('rtsp://192.168.0.40:1026/live.sdp')
to vs = cv2.VideoCapture(0) #this will use your own webcam
```

#to start

```

virtualenv venv &&
source venv/bin/activate &&
pip install requirements.txt
```

# to run

```
python drone.py
```
