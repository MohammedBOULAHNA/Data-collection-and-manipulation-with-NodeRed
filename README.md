# Data-collection-and-manipulation-with-NodeRed

In this File we will describe a project that I worked on to make a Dashboard in order to do the visualization of several indicators in real-time.

### 1.	Objective:
The overall aim of this project is:
- The implementation of an OPC server
- The manipulation of the data of a production installation
- The creation of a Dashboard to display the variation of the data in real-time
- Apply additional actions to facilitate the processing of this data
***The data that concern us in this project are Temperature (°C), Mass Flow (Kg/s), and Pressure (Pa).***

### 2.Tool Used :
  - ***Serveur OPC : KepServerEX*** is a Kepware communication technology representing an advanced solution of OPC communication servers on the market, certified by the OPC foundation. 
The KEPServerEX communication platform has a wide range of communication interfaces (OPC DA, UA, AE, .Net, HDA, SNMP Agent, ...).

![image](https://user-images.githubusercontent.com/124175118/221309179-07091ba7-e9af-44db-b54a-9e46bba0aab2.png)

- ***OAS : Open Automation Software** OAS is a software that provides access to industrial operations and enterprise data for connectivity, monitoring, analysis etc. It allows direct connection to APIs, OPC servers, files, databases and IoT platforms to create world-class SCADA, MES or industrial automation solutions.

![image](https://user-images.githubusercontent.com/124175118/221310264-b5553abd-9100-469f-8e7b-71f7a4e2b57b.png)

- ***Node-Red*** Node-RED is a programming tool for connecting hardware devices, APIs and online services in new and interesting ways.
It provides a browser-based editor that makes it easy to wire flows using the wide range of nodes in the palette that can be deployed in its runtime with a single click.

![image](https://user-images.githubusercontent.com/124175118/221310822-b844bcb8-da05-4e00-b55a-ced3680ae910.png)

- ***PhpMyAdmin*** It is a web management application for MySQL and MariaDB database management systems.
- ***XAMPP*** It is a set of software allowing to set up a local Web server, an FTP server and an e-mail server. It is a free software distribution offering a good flexibility of use, known for its simple and fast installation.

### 3.The final result of the Dashboard : 
The following picture shows the final result of the Dashboard :
![image](https://user-images.githubusercontent.com/124175118/221361152-b2425f19-9a7b-44c2-a006-2dde9d04e9b5.png)


### 4.Data Storage : 
The Data that concerns Temperature (°C), Mass Flow (Kg/s), and Pressure (Pa) can be stored in a csv file in real time and also in a SQL database.
![image](https://user-images.githubusercontent.com/124175118/221361435-7f5ebb8e-341c-439b-b4d6-55e36d2f0205.png)
![image](https://user-images.githubusercontent.com/124175118/221361507-95637c7f-83cf-4703-ae63-5160e3a3e205.png)

### 5. More features : 
This project gives the possibility to send the captured values via Email to an aother user. This feature is showen in the following picture :
![image](https://user-images.githubusercontent.com/124175118/221362139-087be05b-6cc8-40e3-9b00-c83f0b755171.png)





