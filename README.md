To simulate:
install mavproxy and dronekit-sitl
run dronekit-sitl copter
run mavproxy.py --masster tcp:127.0.0.1:5760
run simulatedSurvey.py

note: you may need to comment out the picamera2 import and creation in utils.py because it requires libcamera
