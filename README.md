# Vehicle simulator for Sekai 
 https://github.com/rsabir/Sekai

The purpose of this project is to simulate a vehicle for the project distributed geolocalisation system Sekai.
This project can also be handful to develop a client for Sekai.

***This project is totaly open source and is liscenced under MIT Liscence, which means you can use it freely and without restriction. We will be very glad to receive your contribution.***

##Installation:

###Prerequisites
Before installing the vehicle simulator, you’ll need to install  JRE  or JDK , Apache Tomcat and OSM Sekai Server:
```
# apt-get install default-jre
# apt-get install tomcat8
```
To install Sekai please refer to the following git:

> https://github.com/rsabir/Sekai

After that, you need to get client.war in the drive or generate it with the sources present in the git.
Here is the Drive containing the war file :

> https://drive.google.com/folderview?id=0BywXTC21h2yVa0M3UTJoUnpFZHM&usp=sharing

Then you have to rename client.war to ROOT.war and put it in **...\apache-tomcat-directory\webapps**

##Quick Start

To lunch Apache Tomcat you have execute **...\apache-tomcat-directory\webapps\startup.exe** for Windows or 
**...\apache-tomcat-directory\webapps\startup.sh** for linux.
 
After that, you have to configure your default server http://localhost:port/Config

Then you can use the vehicle simulator with http://localhost:port/

if you have any problem please contact us by zakariahili At gmail.com
