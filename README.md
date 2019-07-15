# QRScanner_OpenCV_Python


Make sure to change in drone.py or the other files to the source of your camera
for example:
change that vs = cv2.VideoCapture('rtsp://192.168.0.40:1026/live.sdp')
to vs = cv2.VideoCapture(0) #this will use your own webcam

#to start 

virtualenv venv &&
source venv/bin/activate &&
pip install requirements.txt


# to run

python drone.py