---
layout: post
title: Significant Function – random expression
date: 2019-12-16
categories: prototype
author: Iván Huelves Illas
---
![_config.yml]({{ site.baseurl }}/images/random-function.gif)

In order to show different possibilities of the Significant Function, I prototyped a more joyful application of the model.

In this case the scenario is a shop with a variable identity. Each time a customer is detected by presence sensor the logotype will variate.

For this purpose I designed a specific variable font with Glyphs App which axe rotate 360º the glyphs.
![_config.yml]({{ site.baseurl }}/images/glyphs - random rotation.png)

To make each letter rotate randomly I use the JS expression:

`return Math.floor(Math.random() * (max - min + 1) ) + min;`

Here you can see the prototype working: [Significant Function – random expression]()
