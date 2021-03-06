# Bridged LM4780 amplifier

A while ago I came up with the idea of making some simple but high quality amplifier modules as a bit of a step up from popular LM3886 implementations.

The design is based around TI’s AN1192 application note for a BPA200 design but with a couple of tweaks:

Firstly, I am going to be using 2 amplifiers in bridged mode rather than 4 in bridged-parallel. This should give it the ability to drive some power hungry speakers.

Secondly, I am using slightly different resistor values, 20k & 21k instead of 20k5 and 21k5 which are easier to source in the tolerance I wanted.

I am using a mixture of surface mount parts to improve performance but keeping some through hole parts for the power supply. The surface mount parts have a 0.5% tolerance, so they are fairly well matched. They are a huge pain to work with unless you are using flux. I make mine the do-it-yourself way from solid rosin flux smashed into a powder and mixed with a little isopropyl alcohol until it becomes a paste. Works a treat and it’s very cheap.

As for the buffer I have picked OPA1641 which is a JFET input opamp, so it should have a nice sound to it hopefully.

I’ve made a little zener based series shunt regulator for supplying power to the opamp. In case you are wondering the reason for raising the zeners from the board is so they are easier to test – no it isn’t shoddy soldering!

That’s it for now, case and transformer are to be ordered… to be continued…

Some images:

![alt text](https://github.com/thequirky/diyaudio/blob/master/lm4780_br100/images/01.jpg)
![alt text](https://github.com/thequirky/diyaudio/blob/master/lm4780_br100/images/02.jpg)
![alt text](https://github.com/thequirky/diyaudio/blob/master/lm4780_br100/images/03.jpg)
