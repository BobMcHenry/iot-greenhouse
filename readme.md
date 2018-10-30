# IOT-Greenhouse

## The plan
- Set up a system of http enabled sensors to report temperature, relative humidity, and lighting conditions
- Create a central hub to recieve sensor data and control relays attached to humidifiers, lights, and heat source
- Set up a database to store climate information, sensor errors, and IO control logs
- Set up pi camera to take regular photos of greenhouse conditions
- Set-up timelapse generation from photos
- Create a dashboard to display visualized climate data and timelapsed greenhouse activity (Web & PiTouchscreen)

![SysDiag Img] 
(https://github.com/BobMcHenry/iot-greenhouse/MycoLab_systemdiagram_v1.png)


## The stuff
- NodeMCU/ESP8266 for sensor control
- DHT22 Temp/RH sensors
- LDR/Photoresistors for light measurement
- Relays for humidifier, humidifier tank heater, and main lighting
- Rasp Pi 3 modelB for hub
- Raspberry Pi IR Camera
- ArduinoC for ESP8266 control
- NodeJS for piGPIO, db, dash, and sensor rest api
- SQLite for local DB
- react for web dash & Electron/Benja for pi touchscreen dashboard
- ffmpeg for image->timelapse video generation

## Nice to haves
- Email/SMS/Push alerts for sustained undesired conditions & sensor errors
- Power usage monitoring/visualization

## Todos
- Physical wiring and sensor placement mockup
- UI mockups
- System diagrams
- DB Schemas
- research relevant node packages
