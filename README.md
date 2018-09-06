# Solar-Beacon
A work in progress Bluetooth Beacon project

Appliances Bluetooth solution
Keep in mind  this project was a put together under some time pressure, so it’s actually just a bare bones, working proof of concept. Here you will find sufficient information to flash and operate the devices.
The projects are written using PlatformIO, you can learn more about it from Platform.io
NB: All devices needs to be flashed with fresh firmware. You will find a link to the correct Github Repo in each corresponding section.

Beacon


![The Beacon](https://d2mxuefqeaa7sj.cloudfront.net/s_0E6F65BF6D9DACD3E9DB665A93A1D8F9B54E7C10C982D281FF46A388F12AC47A_1536239745604_Bluetooth+boxes.jpg)


The bacon it the box with the switch on top. When ON, the Beacon will advertise a Bluetooth network called “Solar Beacon”. If the switch is toggled again, the network will turn off.

The blue tape-mark indicates where the negative connection should go. It would be best to double check this with a continuity test from the connection point to GND on the ESP32, just to make sure, since its very much is a quickly put together project.

To flash it, connect it to you PC and load up Visual Studio Code, with the PlatformIO extension installed. You can also use the Arduino IDE, but i used PlatformIO for ease of use.

Now you are pretty much done with the Beacon, just make sure to power it up and test if it works properly.

You can find the source code for the Beacon right here: github.com/thogul/Solar-Beacon
