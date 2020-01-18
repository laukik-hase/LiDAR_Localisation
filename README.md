# Lidar_Localisation

Navigating a bot with respect to the polar coordinate system using LIDAR (Light Detection and Ranging) sensor and magnetometer HMC5883L.

Implements Wemos D1 Mini and/or ATMega 16-32.

The 'θ' coordinate is traversed using the data from the magnetometer (HMC5883L). (Sent directly to AtMega)

The 'r' coordinate is traversed using the data from the LiDAR. (Sent to ATMega through Wemos D1 Mini)
