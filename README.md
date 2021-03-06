# [Smart Home](https://ecen-smart-home.herokuapp.com/)

[Smart Home](https://ecen-smart-home.herokuapp.com/) is a full-stack web app that gives full control to all home lights, outlets, and appliances from any device connected to the internet.

The home is controlled through a Raspberry Pi micro-controller. The Raspberry pi sends requests to the web app to update the status of the sensors (temperature, light, people counters, etc...) and get requests from the app to update the state of lights, devices, and outlets (by controlling Raspberry Pi pins).
**[Learn How to Use](https://ecen-smart-home.herokuapp.com/learn)**
<br>
## Smart Home Features
- Display Home teamperature from temperature sensor
- Fetch city weather from real time API
- Count people inside each room and turn off lights automatically if there is no people inside
- Control each room's light, outlets and devices from any device that has internet access
- Control all doors
- Control garage's gate
- Monitor the parking slot availability 
- Irrigate all home plants automatically and show if plants are moistured or not.
- Display notifications if the home bell rang
- Calculate power consumption (under construction)
- Image processing to turn of the tv automatically if the user fall asleep

<br>

**Technologies used in this project**

- Raspberry Pi:
  - Python
  - Raspy-os (linux disrto from Raspberry Pi)
  - SSH (secure shell was used to control the Raspberry Pi without connecting it to a monitor

- Front-end:
  - HTML
  - CSS
  - JS 
  - Bootstrap
  
- Back-end:
  - Node.Js
  - Express
  - MongoDB
  - Mongoose
  - EJS
  - Heroku hosting service
  - Atlas for MongoDB


- Hardware:
  - Raspberry Pi 3 B+
  - IR sensor (x2)
  - Servo motor (x2)
  - Water pump
  - Soil moisture Sensor
  - Relay
  - Buzzer
  - Push button
  - Breadboard
  - Temperature sensor

<br>

### Hardware Connection

![image info](https://raw.githubusercontent.com/hossamhamzahm/smart_home/main/Smart%20home%20frtzing%20diagram.png)

<br>

### To be done next
- Implement users model
- Add authentication and authorization
- Refactor python code
- Implement image processing feature
- Implement power consumption feature
