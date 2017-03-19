# WebLamp
The project creates a web application to control a lamp (or anything connected to GPIO25 of Raspberry Pi 3) via a webapp.

## Connection
* A PowerSwitchTail II is connected to GPIO25 of Raspberry Pi 3 Model B.
* The web server is based on Flask: ```sudo pip install flask```

## Run the server

```
sudo python weblamp.py
```

## Turn on/off the lamp

* Connect to your Raspberry Pi's IP address
* Run ```ifconfig``` to find out the IP address.
* In a browser, type: ```http://ip_addres_of_raspberry_pi```
* See the demo [here](https://goo.gl/photos/4J8jKYWHMCc5BgjM6)
