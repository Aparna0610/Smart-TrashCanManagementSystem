# Smart-TrashCanManagementSystem
### Executive Summary
###### 
This project designs a computer-based information system for Smart Trash Can Management, analyzing existing system and business situations by requirements gathering and also using object-oriented design principles and methodologies, some of which includes the BPMN diagram, Context diagram, Use Case diagram etc.

In some places, it has been observed that the trash cans are overflowing with trash, and they stay full until their designated cleaning time. As a result, this problem leads to pollution and sometimes the spread of diseases.
Therefore, our group introduces the Smart Trash Can Management System, which is a cost effective and efficient automated IOT based system whose main objective is to resolve problems for trash collection and management by using ultrasonic sensors to monitor the fill capacity percentage of every trash can. Moreover, the system also provides recommendations for where there is a need of a new trash can so as to minimize the cost and human effort.

The Smart Trash Can Management System will allow users and members to view the amount of trash that is present in a trash can near their location by accessing the website. The user can then decide where to dispose their trash based on the amount of trash they have by looking at the system which will provide the information about the trash can fill capacity. As a result, a user will save a lot of time and effort.

The smart trash cans consist of an ultrasonic sensor that measures the level of trash in the trash can. These sensors are interfaced with a Node Microcontroller unit that transfers the trash fill capacity data to the trash can data file of the system. The Smart Trash Can Management System will automatically send a notification to the trash management if the fill capacity percentage of the trash can reaches the threshold of 80% or above. As a result, the trash cans can be prevented from getting overflowed.

The Smart Trash Can Management system also provides recommendations for new trash can placement by analyzing the trash collection frequency data of the current and past 6 months. The system calculates the current 6 months’ cost for each trash can and that cost is compared to its cost of the last 6 months. Afterwards, the system selects the top 3 most costly trash cans from all of the trash cans that have a current individual cost that is 1.5 times more than their cost of the last 6 months. The locations of these top 3 trash cans are sent to trash management as a recommendation for a new trash can to be placed near their locations. By placing a new trash can, the system can reduce the cost incurred by trash management for sending their janitors an excessive number of times. 

### Problem Statement
######
#### Problems:
The current trash collecting system has no way to track if a trash can is filled or not, which causes the janitor to personally go around checking each trash can. This process is thus inefficient and time consuming.

The current system does not have a way to allow residents who need to throw trash away see which trash can is full or not. As a result, some trash cans are barely used while others are overflowing with trash.

The current system does not have a platform available to determine the best location for future trash can placement.

#### Objectives:
Trash Management will be notified if a trash can is full or empty through the platform so that they can work more efficiently.

The residents can view the percentage of the trash in the trash can that’ll help them to save time and energy. 

The platform will collect data about how frequently the trash can gets full so that the system can send out a recommendation to help with determining which location to place future trash cans. This process will save money as placing a new trash can will be less costly than having a janitor empty a trash can an excessive number of times

#### Scope:
The goal of this project would be to improve a company’s trash collection, trash disposal, and trash can placement.

This new system can be implemented in many other locations such as schools and malls.

This project requires manpower to install sensors into the trash cans and develop a website.

This system requires database servers to store each member’s information and each trashcan’s information.

#### Future Enhancement: 
We can add sensors and other hardware components to the recyclable trash cans so that we can check their fill capacity and compress the trash every time it nears a fill capacity of 80% to make more room in the trash can.

We can use solar powered batteries in the sensors, which will reduce the cost of powering the sensors as we have an eco-friendly and renewable source of energy.

AWS IoT Core Services such as AWS IoT Greengrass, RTOS etc., can be incorporated that lets AWS extend to edge devices. Edge devices in our proposed system are the trash cans fixed with sensors. Benefits of using AWS IoT Core services ranges from connecting and managing devices, securing device connections and data, processing and acting upon device data, reading and setting device state at any time etc.

Click link to watch the project presentation
https://www.youtube.com/watch?v=jhJgJRRoB_E&feature=youtu.be

Link to Project Report:
https://docs.google.com/document/d/1QcbJLM_NiFrVoF9i_BPdGy6PzdPONUGNeqgI3h5Y2Kw/edit?usp=sharing
