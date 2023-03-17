---
layout: post
title: Sensor Variable Font model
date: 2019-12-14
categories: prototype
author: Iván Huelves Illas
---
![_config.yml]({{ site.baseurl }}/images/model-sensorvariablefont.png)

## This project presents a model that sets the groundwork for establishing a significant relationship between variable fonts and its application in graphical interfaces from data collected by different sensors. The intention is to give to graphic interfaces a connoted meaning that can be translated into more significant experiences for their users.

First the needs of the model are identified, and later the architecture of the model is explained, including the components. On a following post will be explained the architecture flow.

### Model Requirements

According to the need raised in this post, the model to be developed must have the following characteristics:

- **Flexible** The model must have parts of a higher level of abstraction that allow it to be applied to interactive projects of various kinds.
- That it **contributes meaning**. The model must return a result that transmits a certain communicative intention.
- That communicates through **typography**. The means of communicating the connoted sense must be the axes of variation of the variable typography.
- **Based on IoT** and human-machine interaction.

### Basic architecture

- **Sensor:** It is in charge of recording a certain phenomenon and returning data in real time.
- **Variable font:** It is in charge of reproducing, through the values adopted by its axes (which are determined by the font used), the sensor data.
- **Normalizing function:** Allows an equivalence **to be established between two ranges of values**: the minimum and maximum values selected for the sensor and the axis.
The Function transforms the data recorded by the sensor (input) to the equivalent of the axis. For example, if the sensor registers a value of 60 centimetres of distance between the sensor and a person, this could be equivalent to a value of 400 of the axis of variation weight.
- **Significant function:** It is in charge of **giving semantic value to the graphical interface** transforming the normalized data received by the sensor to fulfil the communicative objective. In order to achieve it the designer can **rely on design principles** such as equilibrium, contrast, repetition, randomness … which must be **defined through operators, expressions and / or sentences** able to relate the significant intention with the sensor data and the axis of the font.
