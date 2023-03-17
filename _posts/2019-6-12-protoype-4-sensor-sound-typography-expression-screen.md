---
layout: post
title: Prototype Nº4. Sound sensor applied to the expressive capabilities of typography on a large format screen
date: 2019-06-12
categories: prototype
author: Iván Huelves Illas
---
<iframe src="https://player.vimeo.com/video/341422442?h=260114c0ea" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

## The fourth prototype developed proposes an application of variable typography more focused on sensations. Specifically, the music of a concert is related to the typography projected on the screen of the stage.

On the one hand the elements would be the sound sensor that records the frequency of the music with values between 7 and 50. These values, like those established for the prototype of the light sensor, have to be calibrated since they depend on the volume of the music and the level of noise detected by the sensor when there is supposedly silence. The recorded value is updated every 10 milliseconds. The sensor used is the so-called [SparkFun Sound Detector](https://www.sparkfun.com/products/12642) which has a signal amplifier and the ability to detect not only the audio, but also the presence of binary sound and the amplitude of the sound.

And on the other hand the variable typography [WHOA Spine](https://www.futurefonts.xyz/vectro/whoa). This typography has been selected for its expressive capacities using its three axes of variation: Horizontal, Vertical and Rotate. The first two limiting the values from 0 to 1,000 and the third from -45 to 45.

The significant function selected was rhythm and randomness. As mentioned previously, in this case the expressive capacity of the prototype has prevailed as it has defined a playful context. The typography varies according to the amplitude of the sounds recorded in real time, which creates a very dynamic typographic experience, as if the typography itself were dancing. The greater the amplitude recorded, the greater the value of the axis of variation. In order to keep the sensation of rhythm under control and not seem totally random, the axes of horizontal and vertical variation have been limited only to their positive values, i.e. above and to the right, while for the axis of variation Rotate, which makes the letters rotate, their values do follow the rhythm of the music but the sign of the value (positive or negative) is randomly modified in the direction of the rotation.

Once the significant intention has been established, the Normalizing Function is continued. As we have just described, the minimum and maximum values of the sound sensor correspond respectively to the minimum and maximum values of the variation axes.

Finally once the mapped value has been transformed from the process of significance it is decided to apply to all glyphs.

More info on [Github](https://github.com/ivan-huelves/Sensor-Variable-Font_sonido)
