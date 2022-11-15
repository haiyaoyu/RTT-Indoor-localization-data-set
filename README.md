# Indoor-localization-data-set
The data sets are collected in 7 different real world scenarios, which include the round trip time(RTT), the received signal strength (RSS), the Inertial Measurement Unit(IMU) data as well as the floor plan.

In each scenario, there will be variable circle folders and a excel file includes the access point (AP)location and index.The floor plan with and without the AP location and the trajectory is also provided. In each circle folder, the first two excel files are the raw data collected in the two cellphones, which contains the RTT, RSS from all APs and the IMU data from themselves. The next two excel files are the data sets, which are cleaned and filtered from the first two excel files. The last excel contain the RTT and RSS information between the two cell phones.


As shown in Table below, a sample between a cellphone and all APs consists of a time stamp, RTT, standard deviation (std) of RTT, RSS, IMU measurements, and ground truth of the cellphone’s location. The RTT is converted into distance, which is half of the ratio between the round-trip time and the velocity of light in vacuum. Similarly, a sample between two cellphones consists of RTT, std of RTT, RSS, the number of FTM requests, and the number of successful measurements.


The IMU information includes the output of 3-axis accelerators, gyroscopes and magnetometers rcorded during each  time interval. (Accx	Accy	Accz	Gyrox	Gyroy	Gyroz	Magx	Magy	Magz), we also provide the Azimuth, Pitch and	Rollbased on the IMU output.

![image](https://user-images.githubusercontent.com/118267135/201909285-7ef9c8e6-7872-4749-8bb6-1c753493c1ac.png)

