---
layout: post
title: Architecture flow
date: 2019-06-08
categories: model
author: Iván Huelves Illas
---
![_config.yml]({{ site.baseurl }}/images/model-sensorvariablefont-flow.png)

¹ In the basic model only one sensor, one font and one axis are considered to facilitate comprehension. However, several sensors, fonts and axes can be combined to make the projects more complex.

² The axes depend on the selected font.

³ The Normalizing function allows us to establish a relationship between two ranges of values to transform the recorded data to its equivalent in the axis.

⁴ The minimum and maximum values of the sensor and the axis in the Normalizing function do not necessarily correspond to their actual minimum and maximum values, but they do have to be within that range.

⁵ They’re just a sample. The designer has to select the ones he needs to communicate a specific meaning.

First of all, the input is the data collected by a sensor to modify the axis of variation of a typography through a normalization process (model normalization function), in which minimum and maximum values must be selected for the sensor and the axis of variation. These values must be contained within the predefined range for the sensor and the axis, and it is the designer’s decision to make them coincide with those default values or to establish others to reflect the communicative intention.

Once the value of the normalized variation axis is available, it is subjected to a process of significance (by means of the model’s Significant Function) from one or more design principles. Next, an expression and/or sentence must be designed through operators that transforms the normalized value.

Finally, it is decided whether the value of the axis of variation, now transformed into an instrument with greater semantic capacity, will be applied to all the glyphs or only to specific ones.

Note: During the evaluation of the model, it has been verified that the flow doesn't have to follow a specific order. For example you could start by defining the Significant Function. This is just a suggestion of the different steps.
