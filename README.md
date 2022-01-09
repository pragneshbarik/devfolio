# Computer Vision aided Driver Management System

A completely automated and seamless system to manage drivers.

## Motivation 

Often times it happens that multiple persons drive a single vehicle (mainly in truck and taxi industry) and distance travelled by each person need to be tracked so we made a solution that can track the distance driven by the person using facial recognition.

The distance data linked to the driver face can be used in multiple purposes such as :

* To levy fare of travel on the driver.
* In case of Truck-Taxi industry is can be used to process payment according to the distance travelled.
* Use Facial Landmark detection to build a driver road attentiveness profile.


## Features of the Python Script

* Track persons driving the vehicle.
* Track distance traveled by them. 
* Geofence a particular driver.
* Fetch real time fuel prices for that particular location and calculate fare levied on the driver.
* Build a driver road attentiveness profile, for discriminating good drivers from bad drivers. 

## Tech Stack

* Dlib
* OpenCV
* Radar.io
* Pandas
* Facial Recognition

## Installation

I will also post a video tutorial about how to operate, stay tuned.

1. Install [Anaconda.](https://www.anaconda.com/)
2. Install all dependancies using **anaconda prompt**, its necessary to follow the order given below.
```
pip install numpy pandas radar-python opencv-python geopy
```
```
conda install -c conda-forge dlib
```
```
pip install face-recognition
```
```
pip install lxml html5lib bs4
```
4. Clone the Driver Management folder.
5. Copy all driver faces to be recognized to the folders named "Face Data".
6. Run the .ipynb script. 

## Recommended Deployment Environments

This program is built keeping performance limitations of mobile single board computers in mind, as it uses high performance machine learning library **DLib**, it is intended to run the program on :

* Raspberry Pi 4.
* Nvidia Jetson Systems.

## Demo Video

[Youtube Video](https://youtu.be/fBEFWTpiCLo)

