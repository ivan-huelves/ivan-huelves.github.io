---
layout: post
title: Prototype Nº3. Temperature and water sensor applied to the weight of the typography in an interactive informative panel
date: 2019-06-11
categories: prototype
author: Iván Huelves Illas
---
<iframe src="https://player.vimeo.com/video/341421909?h=aeeaeb9517" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

## The third prototype aims to explore the relationship between sensors that detect climatological phenomena and the expressive capacities of typography in the public space of cities.

For this purpose, a temperature and water level sensor (simulating a rain sensor) has been used in a electronic billboard or more commonly known in Spain as *mupi*.

On the one hand would be the temperature sensor, specifically the [LM35](http://johnny-five.io/examples/temperature-lm35/) model. In this case the values can be very wide, from temperatures below zero degrees to temperatures up to 50 degrees, so it has been considered appropriate for the purposes of the prototype to limit us between 20 º and 45 º. The recorded value is updated every 1000 milliseconds. The other sensor used, which detects the water level, records values ranging from 2 to 265.

And on the other hand the variable font [Source Sans Variable](https://github.com/adobe-fonts/source-sans/releases/tag/3.006R), both in its Roman version to reproduce the temperature, and the Italic version to represent the thickness of raindrops. In both cases the Weight variation axis has been used, with a minimum value of 200 and a maximum value of 900.

The Significant Function used has been sequentiality and continuity. The purpose has been to reflect in a progressive way and according to the meteorological phenomenon registered with the typography. If the temperature and/or rainfall values increase, the weight of the typography increases.

Once the significant intention has been established, the Normalizing Function continues, which establishes a relationship between the corresponding minimum and maximum values of the sensors and typography. Finally, once the normalized value has been transformed from the signification process, it is decided to apply it to all the glyphs.

More info on [Github](https://github.com/ivan-huelves/Sensor-Variable-Font_meteo)
