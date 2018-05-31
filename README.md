## DailyIOT
#### open IoT platform powered by openfaas targeted easy adaptation

## Overview if DailyIOT
> IOT Made Simple
   
    
> DailyIOT platform Stack 

![Platform Stack](https://farm1.staticflickr.com/886/42417890132_50ae4d91e7_b.jpg)

> DailyIOT Device Stack

<p align="center">
   <img src="https://farm2.staticflickr.com/1750/42468785871_f50f33d489_b.jpg">
</p>


##### TODO
- [x] API - Implement HTTP API [dailyiot-gateway]
- [x] Implement Alexa skill [dailyiot-alexa]
- [X] Implement HTTP Server at RaspberryPi as rasp_ctl [rasp_ctl]
- [x] API - Authtoken validation [dailyiot-gateway]
- [x] UI - Implement Glitchfree Switch Page [dailyiot-gateway]
- [x] UI - Implement Login Page with Cookie [dailyiot-gateway]
- [x] UI - Enable and Disable all switches [dailyiot-gateway]
- [x] UI - Ajax request to update/monitor state [dailyiot-gateway] 
- [ ] Create METRIC Service and find a way to Generate useful metrics based on API Request, Like:  
      - daily/weekly total active period,  
      - daily/weekly average active period etc
- [ ] Template and SDK for Writing different IOT Skill for both Platform (gateway, metric & alexa) and rasp_ctl
- [ ] Integrate with OpenFaaS-cloud [dailyiot]
- [ ] Automatic device registration on Startup [dailyiot-gateway] [rasp_ctl]
- [ ] Optional Automatic ngrok tunnel creation on Startup [rasp_ctl]
- [ ] Change password and token to secrets [dailyiot]
- [ ] UI/API - provide UI and API support to get the metric     
- [ ] Use minio as storage to keep device info [dailyiot] [dailyiot-gateway]
- [ ] Custom switch name [dailyiot-gateway]
- [ ] UI - Multiple Device Layout [dailyiot-gateway]
- [ ] Write Documentation [dailyiot-gateway] [rasp_ctl]
- [ ] Find a way to create Routine (without Alexa) [dailyiot]
- [ ] Device Setup via Wifi Hotspot like Alexa (Help Needed) 

## Overview Of Current Work

> Login Page

![login](https://farm1.staticflickr.com/897/41565051815_a44470fb4e_h.jpg)

> Switching Device

![Switching Device](https://farm2.staticflickr.com/1760/42467480791_c831254071_b.jpg)
