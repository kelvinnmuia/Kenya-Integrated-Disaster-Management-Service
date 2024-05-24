# Kenya Integrated Disaster Management Service (KEIDMS)


Kenya Integrated Disaster Management Service (KEIDMS) is an innovative web application designed to streamline disaster management processes. Our platform serves as a comprehensive solution, integrating essential functions to enhance coordination and effectiveness in disaster response. Currently, in its MVP phase, KEIDMS offers robust features including user authentication, disaster event management, and a donation system. It also provides a vital communication link for disaster victims to request assistance. As we continue to develop, our goal remains steadfast: to deliver a platform that not only meets but exceeds the demands of efficient disaster management.


## Table of Contents

* [Features](#Implemented features so far)
* [Installation](#installation)

## Implemented features so far

**User Authentication:** Provides login and registration functionalities to ensure secure access to the platform.
**Disaster Event Management:** Functionality to record and track disaster events.
**Donation Functionality:** Allows donors to contribute items, aiding in the logistical support of disaster relief efforts.
**Aid Request Mechanism:** Permits disaster victims to request necessary items, ensuring efficient aid distribution.

## Getting Started
Clone this repository
```sh
git clone https://github.com/asad1996172/Disaster-Management-System
```

To enable administrator acces in VScode for Windows run ```Set-ExecutionPolicy Unrestricted```

### Setting up Server-side
1) Install NodeJS
2) Install XAMPP: ```https://sourceforge.net/projects/xampp/files/XAMPP%20Mac%20OS%20X/8.0.2/```
3) Run mysql server and apache server from Xampp Control Manager
4) Go to server directory and run ```npm install``` to install node modules
5) Run ```npm run server``` to start backend server
6) Run ```npm run test``` to run tests and generate coverage report

### Setting up Client-side
1) Go to client directory and create virtualenv using Python 3.6.5 ```virtualenv -p python3 env```
2) Activate virtual environment ```source env/bin/activate``` For Mac and ```.\env\Scripts\activate``` For Windows
3) Install required python libraries ```pip install -r requirements.txt```
4) Run client server ```python app.py```
7) Run python tests and generate coverage report ```pytest --cov=app --cov-report=html:coverage -s```

