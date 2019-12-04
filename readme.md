## Drone Stabilization
- Everybody knows drone are cool but there is a stability issue. It is hard to keep your drone at one stable position.
- So, we tried to solve this problem using computer vision methods.
- First we find corner points and compare to consecutive frame to find displacement in each axis(pitch, roll, yaw).
- Then we smooth our output using  moving average filter. This all were great.
- But our main objective was to take IMU sensor data and try to remove noise from that so our drone won't drift.
- For that we come up with Kalman filter. As we don't have sensor data, so we haven't come up with result instead we give summary and code which we can use to filter noise from sensor data. You can easily pass sensor data if you have any and ready for amaze.
![Test Image 1](./data/drone.jfif)   
---  
