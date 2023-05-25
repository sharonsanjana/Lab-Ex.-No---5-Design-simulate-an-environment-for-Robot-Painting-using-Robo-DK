# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:
~~~
1.open the roboanalyzer software.
2.select the robot and its degrees of freedom.
3.change the values of X and Y wherever necessary.
4.simulate the model for inverse kinematics.
5.plot the graph between the joints.
6.update the DH parameters of the link configuration and end effector configuration.

~~~





### SIMULATION 
 ### RPR ROBOT:
 ![174305007-a5b24df5-117a-49f8-acdd-313cf22fa8c9](https://user-images.githubusercontent.com/94296221/201606294-2e8eb0e7-207a-4fad-87b8-f0305a29e7f5.png)

 ![174305368-06ac2d00-38b5-42fa-aaf9-3ad532e56503](https://user-images.githubusercontent.com/94296221/201606303-a360363b-5d84-4b78-bbab-434cb8680245.png)

 ### 3R ROBOT:
 ![174305070-80a5f0ed-3e4c-4a9f-af96-5f20c6014bb0](https://user-images.githubusercontent.com/94296221/201606349-5afe09bc-8366-4968-83b9-a6aa13806aff.png)
![174305404-886e4ddb-988a-44c7-9656-de86458da6a5](https://user-images.githubusercontent.com/94296221/201606377-25c4e0f3-f16f-4d4a-b2b5-994e500c86c1.png)

 
 
 ### PLOT 
 
 
 ### RPR ROBOT
 
 
 ![174305436-5a8f6338-a8db-4143-8362-4a080c3074b3](https://user-images.githubusercontent.com/94296221/201606493-e0d748be-9d94-4ef8-9ad1-1494521dff0b.png)

 ![174305460-626e119e-0d5a-4962-a14d-2c4f3f56dff9](https://user-images.githubusercontent.com/94296221/201606500-396b5f55-0025-4753-a07e-13b98d597db9.png)

 
 ### 3R ROBOT
 
 
 ![174305488-71b5cec7-3e25-4e2e-9ea3-5cac7667637e](https://user-images.githubusercontent.com/94296221/201606521-6e85a4d2-5b62-41b8-9326-115bda24342b.png)

![174305524-32aba2c4-f3b8-4cda-9cae-69acd66e0344](https://user-images.githubusercontent.com/94296221/201606531-266731b3-2559-4af7-a3da-87f0d394811b.png)

 
 

### RESULTS :
Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
