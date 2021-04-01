# SONYC Sensor Network Repair Findings

## Introduction to the SONYC Sensor Network
The SONYC (Sounds of New York City) project is a noise pollution research project run by scientists at New York University in collaboration with Ohio State University.

The sensors are deployed in various buildings throughout New York City to monitor the noise level outside of the building. These sensors contain a microphone that collects the loudness level in decibals (dB) over time. We are  able to access this information, as well as more statistics about the state and performance of the sensor. This is crutial for knowing when sensore need repairing or updating of components.

This is what a healthy sensor looks like when it is deployed. They are often placed outside of windows pointing at the street below.
![This](sensor_images/clean_sensor.jpeg) 

Some sensors are even placed in busier locations.
![](sensor_images/37th.jpg)
 

## Sensor Engineer 
As a sensor engineer, I am responsible for building, maintaining and repairing the sensor network. This includes making visits to these sensors and repairing them on site, as often-times, it is too difficult to remove the sensor from it's mounting to make a repair in the lab. 

These repairs include but are not limited to electronics failures, wifi failures, power unplugged from the wall, or even updating the physical condition of the sensors. 

Since the sensors are outside in all conditions, it is not foreign for them to collect dirt, fuzz or hair. This is an example of a sensor that has collected dirt over time.

![](sensor_images/dirty_sensor.jpeg)

It's not uncommon that birds will pick at the windscreen of the sensors. This results in pieces missing from the screens. 

![](sensor_images/JuanCarlos.JPG)
In this sensor's case, the bird spikes (designed to keep birds from picking at the foam) has been torn off, resulting in the windscreen ripping.

These sensors are exposed to all weather conditions. ![](sensor_images/snowy_sensor.png) 

## My Report

The contents of my report rely on the data collected about the state of the sensors. When an engineer goes to a location and makes a repair, we mark the repair down in a form. This wahy, we can keep track of which sensors are failing and how they are failing. This helps us both to develope a method for diagnosing sensore on site and for thinking of things that could increase the up-time of the network as a whole. 

I was able to analyze all of the sensor repair logs from June of 2019 through September of 2020 to see what the most common faults were throughout the network. This report describes the most common faults as well as proposed component updates. 