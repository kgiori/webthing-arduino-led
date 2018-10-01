# webthing-arduino-led
Specific example using PlatformIO to build a web thing controllable LED on an MCU board. Forked from [webthing-arduino](https://github.com/mozilla-iot/webthing-arduino) which has even more examples.

This repo is intended to reduce the complexity for developers who want to build simple web things. Using the webthing-arduino library, this example lets a developer build and test a specific "web thing LED" example. It is a simple first test, much like the usefulness of the Arduino sketch "Blink.ino". It lets you know your setup is working before you try something more complex. 

Using this example, if a supported MCU board successfully connects to a Mozilla Things Gateway, then the onboard LED can be turned on and off using the Things Gateway GUI. (See https://github.com/mozilla-iot/gateway for more info on the gateway.)

To try this repo, you may benefit from following this [tutorial](https://github.com/kgiori/webthing-arduino-led/blob/master/Mozilla%20Project%20Things_%20SAMW25%20Tutorial.pdf). It was originally written for a hands-on workshop where attendees were given a Microchip (Atmel) SAMW25 Xplained Pro board, but the goal is to expand it to support a wide range of boards.
