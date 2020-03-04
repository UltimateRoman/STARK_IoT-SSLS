# **Stark_IOT SSLS**

## Smart Street Light System

Project by team Apha_Codinators at HackStudio(our first hackathon).
The project is just a prototype for now and we are working to make it reach full operational capability soon. 

### The Problem 

Street lights, they're a necessity. But are they energy efficient?
Street lighting in conventional systems waste a humungous amount of electric power and consider this scenario in a huge and 
populous country. The electricity power board/organisation managing the street lights bear the expenses of this unnoticed
wastage. This also deprives valuable electric power which could be used in other significant instances.

### Our solution

We had a look into this problem and have designed the STARK Smart Street Light System(SSLS) for the purpose. It makes
use of an Arduino interfaced with a Bolt WiFi Module(ESP 8266) to create a dynamic optimised control system for energy efficient
smart street lights.

### How does Stark work?

The Stark module starts operation automatically at night with the help of sensor data. The sensors then try to detect the presence 
of a vehicle or pedestrian passing through the street. It then switches on the street lights with optimum timing and brightness 
saving electric energy and also satisfying the requirement of the incoming person/vehicle.

**STARK_IoT SSLS Module ver 1.01**
![STARK Module](https://storage.googleapis.com/devfolio/hackathons/dc5f01f119174b248375bc6e5d8c4964/projects/1d4be01bc5864583ad57b01334b92fd8/pico5fsfhskp.jpeg)



### What else can Stark do?

The number of pedestrians or vehicles which crossed through the street are recorded each night and this data is sent to the Bolt 
Cloud which sents this as an email to the user of the module.
The STARK Web App enables the user of a STARK module to view the traffic density data recorded on the Bolt Cloud in the form of a
graph and improve services accordingly.


#### Features under construction

Facial recognition to distinguish people from animals. <br/>
Speed sensing of the incoming vehicle/pedestrian and control the lights accordingly. </br>
ML implementation for polynomial regression and anomaly detection and sending alerts to the admin to resolve it. </br>
Unique Stark device login. </br>
etc.................

