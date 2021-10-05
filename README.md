
#Basic MPU-9250 Arduino sketch of sensor function and transfer the data using Bluetooth module.

This sketch demonstrates MPU-9250 basic functionality including initialization, accelerometer and gyro calibration. 

Runs on Arduino mega ADK.

Install MPU9250 and softwareserial libraries in the first step,
after connecting the modules to the Arduino, upload the code.
I connected to the Bluetooth module using ardutooth app and received the data on my mobile phone.

This algorithm allows estimation of quaternions and relative orientation, allowing output of Yaw, Pitch, and Roll which is subject to Yaw
drift due to gyro bias drift.  

I have added code to run 6-axis sensor fusion using the Arduino mega adk, the MPU-9250 and HC-05 module.
