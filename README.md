# project_self_driving_car
Welcome to the Project "Self Driving Car" , where we will create a prototype of the real world self driving car where it can detect lanes and steer accordingly, detect the signs and obstacles. Let's venture through the journey of creating this electronics and machine learning project. We will be using a Raspberry Pi and its camera, Arduino and normal car chassis and motors for creating this project.


First we need to setup the Arduino Uno.

We will attach the motors to the chassis as shown in the image below: 

![image](https://user-images.githubusercontent.com/47684759/87856947-5aff6b80-c940-11ea-9531-4ca22fff2804.png)


After that for setting up the Raspberry Pi we will use the Raspbian OS that can be downloaded from here: https://www.raspberrypi.org/downloads/raspberry-pi-os/

Setting up the Raspberry Pi using the Raspbian OS will take quite a time. After that we will setup the OpenCV and the other environments that are required to run the project.


We will be always connecting the Raspberry Pi using the Remote Desktop Connection either through LAN or through WIFI (If it is that speed enough to process data)

![image](https://user-images.githubusercontent.com/47684759/87856997-baf61200-c940-11ea-91d1-16b4ebac2073.png)

The following methods are used to detect the lanes that is captured from the Raspberry Pi Camera:
1.	Determining Region of Interest.
2.	Perspective Wrap.
3.	Applying Threshold. 
4.	Canny Edge Detection.
5.	Finding Lane Position.
6.	Creating Result Function.


![image](https://user-images.githubusercontent.com/47684759/87857218-a74bab00-c942-11ea-9d20-eecc510a6c46.png)



![image](https://user-images.githubusercontent.com/47684759/87857223-aca8f580-c942-11ea-8198-e89bd041377f.png)



1. REGION OF INTEREST

![image](https://user-images.githubusercontent.com/47684759/87857237-d104d200-c942-11ea-80e1-ca590c7cb48f.png)

2. PERSPECTIVE WARP

![image](https://user-images.githubusercontent.com/47684759/87857247-e548cf00-c942-11ea-95f7-a24cdb20fac1.png)

3. APPLYING THRESHOLD 

![image](https://user-images.githubusercontent.com/47684759/87857256-f7c30880-c942-11ea-9cbe-7466ee5f234b.png)

4. CANNY EDGE DETECTOR

![image](https://user-images.githubusercontent.com/47684759/87857271-09a4ab80-c943-11ea-978b-37309ebe705b.png)

5. FINDING LANE POSITION

![image](https://user-images.githubusercontent.com/47684759/87857280-17f2c780-c943-11ea-81ea-ac2281d33f7e.png)

6.CREATING RESULT FUNCTION:

![image](https://user-images.githubusercontent.com/47684759/87857286-2345f300-c943-11ea-878b-082d2daa1636.png)

RESULT = LANE CENTER (GREEN COLOR) - FRAME CENTER (BLUE COLOR)


RESULT FUNCTION DISPLAYING ZERO

![image](https://user-images.githubusercontent.com/47684759/87857298-54bebe80-c943-11ea-84ed-c7254aaedff8.png)

RESULT FUNCTION SHOWING TO GO RIGHT WHEN SHIFTED TO LEFT

![image](https://user-images.githubusercontent.com/47684759/87857330-93ed0f80-c943-11ea-98d9-870a8a87533b.png)



For more details about the project and the detail code mail me. 





















