# PythonSeleniumTests
Automated Testing using Selenium and Python for OpenProject

## Overall Installation Instructions

These instructions are based on a Debian Stretch/Buster System. Robot Framework will be installed using pip

 * sudo apt-get install python3-pip
 * pip3 install robotframework (sudo is not needed here)
 * pip3 install robotframework-seleniumlibrary
 * wget https://bitbucket.org/robotframework/webdemo/downloads/WebDemo-20150901.zip
 * unzip WebDemo-20150901.zip
 * cd WebDemo
 * python demoapp/server.py & (python2 application)
 
The WebDemo is a simple python Demo Application, with a login page, used as an example of interaction
between RobotFramework and a Web Application.
