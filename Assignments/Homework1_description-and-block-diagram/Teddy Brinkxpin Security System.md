# **Teddy Brinkxpin Security System**

A creepy talking teddy bear from the 80’s that makes people fear they’re in a horror movie upon unauthorized entry into your house.

## **Overview**

The goal of this system is mainly to prank my brother when he stops by to pick up the mail while I’m out of town, but theoretically it could be so disturbing that a burglar would think twice after breaking into a room with a creepy 80’s stuffed toy that wakes up and talks upon detecting motion (such as a door opening). This design could, in time, be expanded to allow a user to receive alerts, and also talk to an intruder using the stuffed toy. For now, the scope is limited to a closed system in the interests of time and resources.  



![](https://github.com/lklarsen/MakingEmbeddedSystems/blob/30a849090ca127ca218dd1a747b8f6161bf466f0/Assignments/Homework1_description-and-block-diagram/06qeh4bcc9mz.jpg)



## **Architecture**

The system will consist of a modified Teddy Ruxpin talking teddy bear. It will be equipped with a motion detector (new) as input, 2 servo motors (existing); one for the blinking eyes, and one for the moving mouth, and a speaker as the outputs. Initially this will require only a power supply, but future versions could be battery-powered. Using the input from the motion detector, the system will determine whether or not an intrusion has occurred, and if so, the bear will play a pre-recorded audio file while blinking its eyes and moving its mouth.  

![Hardware Block Diagram](https://github.com/lklarsen/MakingEmbeddedSystems/blob/04fa55ebd0a5deb44d31288bf1a8f768db618de7/Assignments/Homework1_description-and-block-diagram/HardwareBlockDiagram.PNG)

![SoftwareBlockDiagram](https://github.com/lklarsen/MakingEmbeddedSystems/blob/04fa55ebd0a5deb44d31288bf1a8f768db618de7/Assignments/Homework1_description-and-block-diagram/SoftwareBlockDiagram.PNG)

![SoftwareHierarchy](https://github.com/lklarsen/MakingEmbeddedSystems/blob/04fa55ebd0a5deb44d31288bf1a8f768db618de7/Assignments/Homework1_description-and-block-diagram/SoftwareHierarchy.PNG)

