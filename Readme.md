1.) A description of your circuit:<br/> What sensor you used, how you are reading the data from the circuit on the Photon. – I have used temperature sensor as input to photon to sense the temperature and send it on cloud. To send the data I have used spark.variable() and to get the data I have used spark.function().

This device uses the following components:<br/>
-	Particle Photon<br/>
-	One Wire Temperature sensor DS18B20<br/>
-	24 LED Neopixel Ring<br/>

2.) A description of your visualization: what libraries or techniques you used, and what differences (if any) there are from your code in the first assignment.<br/>
I have used jQuery Knob library which can be found at http://anthonyterrien.com/knob/ and GitHub repository at https://github.com/aterrien/jQuery-Knob this is different from my previous visualization as the previous one had multiple data entries and this is a single data entry. Previously I had used Google charts and Datamaps for visualization previously as location was one of the attributes of the data.

3.) A photograph of your completed circuit, clearly showing all of the elements and their connections. Annotations would be nice but are not required. :<br/> Photographs are in images folder.

Images:<br/>

![alt tag](https://raw.githubusercontent.com/nxp4195/Assignment-2/master/Images/IMG_8621.jpg)

![alt tag](https://raw.githubusercontent.com/nxp4195/Assignment-2/master/Images/IMG_8622.jpg)

![alt tag](https://raw.githubusercontent.com/nxp4195/Assignment-2/master/Images/IMG_8623.jpg)

![alt tag](https://raw.githubusercontent.com/nxp4195/Assignment-2/master/Images/IMG_8624.jpg)

Live site:(works only when Photon is connected)<br/>
https://rawgit.com/nxp4195/Assignment-2/master/photon_neopixel.html

Refrences:<br/>
https://community.particle.io/t/reading-spark-variables-with-your-own-html-file/4148<br/>

https://www.sparkfun.com/products/245<br/>

http://anthonyterrien.com/knob/<br/>

https://github.com/aterrien/jQuery-Knob<br/>

https://learn.adafruit.com/adafruit-neopixel-uberguide/arduino-library<br/>
