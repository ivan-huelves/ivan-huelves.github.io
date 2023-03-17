---
layout: post
title: Model application to control panel car interface
date: 2019-12-14
categories: model
author: Iván Huelves Illas
---
![_config.yml]({{ site.baseurl }}/images/significant-function-sensorvariablefont.png)

In a previous post you can see the results of one of the prototypes to validate the model. I simulated the interface of the an on-board computer car, relating the distance of the car in relation to another object, car or person. The communication objective is to call the attention of the driver through the variable font in order to prevent an accident.

To conceptualize the project I put into practice the model. On the one hand, I have the distance recorded by the sensor, and in the other one I decide to use the weight of the font to represent that data.

Firstly I define the Significant Function. Because I want to call the attention of the driver I must to create a inverse correlation in the Normalizing Function. The less distance there are, the more weight the font has. So, the only thing I have to do is to create a relation among the minimum value of the sensor and the maximum value of the font weight, and among the maximum value of the sensor and the minimum value of the font weight.

Here you can see the model applied to this case:
![_config.yml]({{ site.baseurl }}/images/model-sensorvariablefont-flow-applied.png)
