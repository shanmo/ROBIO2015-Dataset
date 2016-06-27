'uavpose.log' records the measurement by GPS/INS with its columns following the sequence as below: 

System time in Mastermind  (s)
System time in Gumstix (s)
Image index
x (position in North direction: m/s)
y (position in East direction: m)
z (position in Downward direction: m)
a (roll angle: rad.)
b (pitch angle: rad.)
c (yaw angle: rad.)
u (velocity in body front direction: m/s)
v (velocity in body right direction: m/s)
w (velocity in body downward direction direction: m/s)
acx (acceleration in body front direction: m/s^2)
acy (acceleration in body right direction: m/s^2)
acz (acceleration in body downward direction: m/s^2)
latitude
longitude

The 'images' folder contains the recorded images with file names indexed. To synchronize the data, use the 3rd column (image index) of 'uavpose.log'. 
