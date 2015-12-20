# About the project #
This is a community project.


# License #
Majority of the project components with a few exceptions are functioning base on Apache License 2. For more details please see individual component's license.

# Project goal #

The goal of the project is to provide a quick and systematic way of controlling all types of the sensors and regulators over internet.

# Short description #

The idea is very simple. Everyone who has ever written a piece of code to communicate with a simplest device sooner or later would dream about being able to read or control it over the internet.
As the pushing readings from sensors nowadays is not a big issue the problem with both ways communication still remains. The most trivial implementation of the internet controlled relay switch usually demands setting up a simple web server with access to a public IP and many other things that can make the solution too complex, to temporary and after all entirely unreliable.

JHUB1Online makes the process of communicating with your devices as simple as reading and saving files. All of them can be seen on the web based admin panel where they can be configured and controlled. Comprehensive RESTful API will help easily implement custom applications. The only thing needs to be done is to install small agent software.

# Architecture #
The system architecture from bird's eye view:

![http://jhub1online.googlecode.com/svn/wiki/Jhub1OnlineArch.png](http://jhub1online.googlecode.com/svn/wiki/Jhub1OnlineArch.png)

# Project's elements #

Project's elements with progress to final testing stage and importance for go live stage:
  * HUB1Online [Agent](https://code.google.com/p/jhub1online-agent) (90%) essential
  * HUB1Online [Server](https://code.google.com/p/jhub1online-server) (60%) essential
  * HUB1Online [RESTful Web Service](https://code.google.com/p/jhub1online-webservice) (80%) essential
  * HUB1Online [Web Application](https://code.google.com/p/jhub1online-webapp) (10%) essential
  * HUB1Online [Android Application](https://code.google.com/p/jhub1online-androidapp) (0%) optional