## Creating Use Case Diagrams in StarUML
### CSC 2310 Spring 2021

In this lab you will learn how to create diagrams using the StarUML environment. You will use the information contained in the **Problem Description** shown below as well as the work done in class as context for creating the relevant diagrams(s).

#### Pre-work
* Installation of StarUML - if you have not completed the installation of StarUML, follow the instructions provided in Lab 00.
* Download the lab source files using the following command:
```text
% git clone https://gitlab.csc.tntech.edu/csc2310-sp21-students/%userid%/%userid%-lab-02.git
```
replacing ``%userid%`` with your own TNTech issued userid.

### Problem Description
#### Concept

We are creating a carpooling application for the students and faculty of Tennessee Tech that enables them to get to and from campus in a timely manner without having to worry about searching for a parking spot. It will allow students or faculty to travel to and from campus by hailing a ride and informing other users of their desired destination. Another feature will allow the driver to post information about where they are planning to travel so that other users can request to join them. After a ride has been completed, users will have the ability to rate their rider or driver to ensure that the user experience remains safe and enjoyable. Unlike other applications for similar services, the drivers will not be paid directly but rather through other forms of compensation. This service will only be available to students and faculty of Tennessee Tech so that it can foster safety and community of its users.

#### Elevator Statement

For students and faculty at Tennessee Tech who seek a solution to the parking problem on campus, the carpooling app is a tool that will make it easier to get to and around campus while also providing incentives to those who use it. Unlike other ride sharing apps, our solution will be designed to provide a service that is only available to students and faculty of participating universities so that it can ensure the safe delivery of users to their destination while also not requiring a direct transfer of money.

[Link to Eagle Ride Description](https://tennesseetechuniversity.sharepoint.com/:b:/r/sites/CSC2310Spring2021/Shared%20Documents/General/Laboratory/RideShare.pdf?csf=1&web=1&e=2lzFs1)

#### Activity
Create a use case diagram based on the user stories found in the Eagle Ride description. You may limit your scope to just the features identified in the user stories. In your diagram, you should do the following:
* Create a use case diagram for the _Rider_ features, using three different _Rider_ types: _Potential Rider_ (for riders that are either seeking or scheduling a ride), _Current Rider_ (for riders that have requested a ride or are currently riding in car), and _Past Rider_ (for riders that have completed a ride).
* Partition the interfaces as you see fit based on your analysis of the kinds of features requested

#### Turn-in
You must include the following meta-data in your diagram as a text annotation (Toolbox &#8594; Annotations &#8594; Note):
* Your name
* T-Number
* Lab Section

Save your project file with the following name as follows: ```userid_lab02.mdl``` in the directory created when you executed the ```git clone``` command above. For example, ```jgannod_lab02.mdl```. 

Submit your ```.mdl``` file to iLearn using the appropriate link and by using the following commands:
```text
% git add userid_lab02.mdl
% git commit -m "Completed assignment"
% git push origin master
```

This laboratory is worth 20 points.