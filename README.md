# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 
DART studio screen shots for linear interpolation 
![WhatsApp Image 2024-04-15 at 14 31 22_3d77fb71](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/9a744d6e-5f69-4135-b267-d46f49c2f711)









DART studio screen shots for joint interpolation 
![WhatsApp Image 2024-04-22 at 10 52 44_78ce86e3](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/1401945a-2017-4419-be3e-a903389339e6)








### Robot movements 

![WhatsApp Image 2024-04-22 at 10 52 43_428fcc5f](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/87c672a5-9aeb-42a5-8dcb-877140c68999)

![WhatsApp Image 2024-04-22 at 10 52 43_b765c722](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/544a1317-ddf8-4660-a11e-8341065ca557)
![WhatsApp Image 2024-04-22 at 10 52 44_5e209430](https://github.com/AshwinAkash24/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979248/200f8758-edc0-42ba-95b5-0d9f5b168727)












### Results:  
Hence,the Linear and joint interpolation of industrial manipulator is successfully executed.
