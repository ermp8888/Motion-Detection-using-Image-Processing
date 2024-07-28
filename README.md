# Motion-Detection-using-Image-Processing
## Table of contents
* [Project's Brief Description](#project's-brief-description)
* [Technologies](#technologies)
* [Setup](#setup)

## Project's Brief Description
To address concerns about theft and unauthorized gate entries, organizations can rely on this advanced motion detection model. This system is designed to identify any movement, whether from living beings or inanimate objects. It delivers motion-detected frames with precise timestamps, ensuring accurate monitoring and record-keeping. Furthermore, these frames can be live-streamed directly to a web browser, providing real-time surveillance and immediate alerts.
	
## Technologies
Hardware Interface:
* Raspberry Pi 4
* Camera : Digital cameras are used in image acquisition stage. They are primarily used in obtaining images or video footage.
* Memory Card

Operating Environment:
* Python 3.5
* OpenCV 3
* Database Server
* MYSQL
* Numpy 
* Flask 1.1.2
* Werkzeug 1.0.1
	
## Setup
To run this project:
* Install Raspbian operating system on Raspberry pi 4.
* Make virtual environment and install OpenCV 3 and project related libaries.
* To stream motion detected frame on web brower as well as save frame with time in database run this command 

```
../python new_live_database.py --config/config.json

```

