# Motion-Detection-using-Image-Processing
## Table of contents
* [Project's Brief Description](#project's-brief-description)
* [Technologies](#technologies)
* [Setup](#setup)

## Project's Brief Description
In case of thefts and unauthorized gate entries, organizations that want security can use this motion detection model for motion detection. This model will detect any motion, such as living object motion and non-living object motion. It provides motion-detected frames with time stamping to the organization. Motion detected frames could also be live-streamed on the web browser.
	
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
* Make virtual environment and install OpenCV 3.
* To stream motion detected frame on web brower as well as save frame with time in database run this command 

```
../python new_live_database.py --config/config.json

```

