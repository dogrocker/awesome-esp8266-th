# Awesome ESP8266 Thailand

รวมข้อมูลการใช้งานโมดูล ESP8266 ทั้งหมดภาษาไทย อาจมีภาษาอังกฤษได้ 

- [ข้อมูลทั่วไป Spec](#ข้อมูลทั่วไป)
- [การติดตั้ง Firmware](#การติดตั้ง)
	- [AT Command](#at-command)
	- [ArduinoIDE (C++)](#arduinoide)
	- [Lua Script (NodeMCU)](#lua-script)
- [การแก้ปัญหาเบื้องต้น](#แก้ปัญหาเบื้องต้น)
- [ตัวอย่างการใช้งาน](#ตัวอย่างการใช้งาน)
	- [Wifi](#wifi)
	- [TCP, UDP, Server, Client](#tcp-udp-server-client)
	- [RESTful](#restfull)
		- [Server](#restful-server)
			- [ติดตั้งเอง](#restful-server)
			- [แบบสำเร็จรูป Online Services](#restful-server)
		- [Client](#restful-client)
	- [MQTT](#mqtt)
		- [Server](#mqtt-server)
			- [ติดตั้งเอง](#mqtt-server)
			- [แบบสำเร็จรูป Online Services](#mqtt-server)
		- [Client](#mqtt-client)
- [รวมไลบรารี](ไลบรารี)
	- [Libs AT Command](#libs-at-command)
	- [Libs ArduinoIDE (C++)](#libs-arduinoide)
	- [Libs Lua Script (NodeMCU)](#libs-lua-script)
	
---
### ข้อมูลทั่วไป
*รวมข้อมูลพื้นฐานที่ควรรู้ทั้งหมดของ ESP8266*

คำอธิบายแบบยาวๆ (รอเติม)

* [ESP8266 ชิป Wi-Fi ความหวังใหม่ของคนทำคอมพิวเตอร์ฝังตัว Blognone](https://www.blognone.com/node/60187)


*ภาษาอังกฤษ*

* [รายละเอียด Spec จาก Electrodragon](http://www.electrodragon.com/w/ESP8266)
* [รายละเอียด Spec จาก Nurdspace.nl](https://nurdspace.nl/ESP8266)
* [ESP8266_WiFi_Module_Quick_Start_Guide_v_1.0.4.pdf](http://rancidbacon.com/files/kiwicon8/ESP8266_WiFi_Module_Quick_Start_Guide_v_1.0.4.pdf) - อันนี้เขาอธิบายคร่าวๆว่าคืออะไรแล้วการใช้งาน AT Command
* [ESP8266_Specifications_English.pdf](https://drive.google.com/file/d/0B_ctPy0pJuW6Y0FHcDlVY09Xdjg/view)
* [เว็บ esp8266.com](http://www.esp8266.com/)

---
### การติดตั้ง

#### AT Command
* [ESP8266 วิธีทดสอบและใช้งาน Ayarafun](http://www.ayarafun.com/2014/09/esp8266-at-command-tutorial/)
* [สอน วิธี ใช้งาน Arduino Wi-Fi Module ESP8266 arduinoall](www.arduinoall.com/article/สอน-วิธี-ใช้งาน-arduino-wi-fi-module-esp8266)
* [การอัพเกรด Firmware โดย Thaieasyelec](http://www.thaieasyelec.com/downloads/EWLM107/Update_Firmware_ESP8266.pdf)

*Video*

สำหรับ vdo

*ภาษาอังกฤษ*

* [การใช้งาน AT Command จาก Electrodragon](http://www.electrodragon.com/w/ESP8266)
* [การใช้งาน AT Command v0.9.2.2](http://www.pridopia.co.uk/pi-doc/ESP8266ATCommandsSet.pdf)


#### ArduinoIDE
รอ

*Video*

* [เริ่มติดตั้งบอร์ดNode MCU ESP8266 by wisdomgoody](https://www.youtube.com/watch?v=ocsjRYQhuZQ)

*ภาษาอังกฤษ*

* [ESP8266 Thing Hookup Guide - sparkfun](https://learn.sparkfun.com/tutorials/esp8266-thing-hookup-guide/all)

*Main Repositoty*

* [ArduinoIDE](https://github.com/esp8266/Arduino)

#### Lua Script
รอ

*Video*

สำหรับ vdo

*ภาษาอังกฤษ*

* [วิธีลง Firmware แล้วทดลองใช้งาน](http://benlo.com/esp8266/esp8266QuickStart.html)

*Main Repositoty*

* [nodemcu download firmware](https://github.com/nodemcu/nodemcu-firmware)
* [nodemcu-flasher](https://github.com/nodemcu/nodemcu-flasher)
* [ESPlorer editor for Lua](http://esp8266.ru/esplorer)
* [nodemcu.com](http://nodemcu.com)

---
### แก้ปัญหาเบื้องต้น
* Flash เจ้ง ทำให้เข้าใจว่า Hardware พัง (มีวิธีแก้ไข)
* ปัญหาที่มาจาก USB To Serial อันนี้เจอกับตัวว่า Flash แล้วค้างเปลี้ยนตัวให่มหาย Flash ได้ตามปรกติ ส่วนตัวเก่าก็ Flash ไม่ได้เหมือนเดิมแต่ใช้งานอื่นได้ปรกติ
* สาย USB ก็มีส่วนเปลี่ยนแล้วหาย ก็งงเหมือนกัน

---
### ตัวอย่างการใช้งาน

#### Wifi
อธิบายการใช้งาน WIFI กับ ESP8266

รอเพิ่ม

#### TCP UDP Server Client
อธิบายการใช้งาน ESP8266 ในการส่งค่ารับค่าด้วย TCP UDP Server, TCP UDP Client

รอเพิ่ม

#### RESTful
เนื้อหาส่วนนี้จะอธิบายเกี่ยวกับ RESTful Web services

###### RESTful Server

###### แบบติดตั้งเอง

###### แบบ Online Services

###### RESTful Client

#### MQTT

##### MQTT Server

###### แบบติดตั้งเอง
*อธิบายการใช้งานหรือติดตั้ง MQTT Broker*


*Repository*

* [Mosquitto](http://mosquitto.org)
* [Mosca MQTT Broker](http://www.mosca.io) - Javascript Broker
* [Ponte MQTT Broker By eclipse](https://eclipse.org/ponte) - Javascript Broker
* [GnatMQ - MQTT Broker for .NET and WinRT](https://mqttbroker.codeplex.com) - .NET and WinRT
* [Erlang MQTT Broker](http://emqtt.io) - Erlang



###### แบบ Online Services
วิธีใช้งานหาดูในส่วนของ client นะครับ

* [CloudMQTT](http://www.cloudmqtt.com)
* [The MQTT Dashboard](http://mqtt-dashboard.com/info/broker)

##### MQTT Client
รวมวิธีใช้งาน ESP8266 กับ MQTT Broker ต่างๆ

*AT command*

รอเพิ่ม

*ArduinoIDE*

* [การใช้งาน MQTT บน ESP8266 + Arduino IDE และทดสอบเชื่อมกับ cloudmqtt](http://www.cmmakerclub.com/2015/06/1595)

*Lua Script*

รอ

*ภาษาอังกฤษ*

* [The Seven Best MQTT Client Tools](http://www.hivemq.com/seven-best-mqtt-client-tools)

*Repository*

* [ESP8266 network client (mqtt, restful) for Arduino](https://github.com/tuanpmt/espduino) - ไว้สำหรับใช้ Arduino Uno ต่อกับ ESP แล้วเขียนโค้ดลง Uno คุยกับ MQTT Broker โดยใช้ SLIP protocol ผ่าน Serial port
* [MQTT client library for ESP8266 Soc](https://github.com/tuanpmt/esp_mqtt) - MQTT client library สำหรับ ESP8266 เขียนลง Firmware เลย
* [MQTT.js](https://github.com/mqttjs/MQTT.js) - Javascript Client
* [Paho By Eclipse](https://eclipse.org/paho) - มีหลายๆภาษาครับทั้ง Java, JavaScript, Python, Android, C/C++, .NET and WinRT

##### อื่นๆ
* [การใช้ ESP8266 อ่านค่า Analog (ADC) อย่างง่าย](http://www.cmmakerclub.com/2015/06/1626) 
* [ทดสอบใช้ PWM บน ESP8266 เขียนด้วย Arduino IDE + dw.EspMini](http://www.cmmakerclub.com/2015/06/1549)
* [การอ่านค่า DHT22 ด้วย ESP8266 Native + Arduino IDE](http://www.cmmakerclub.com/2015/06/1707)
* [การอ่านค่า DS18B20 ด้วย ESP8266 Native + Arduino IDE](http://www.cmmakerclub.com/2015/06/1734)

---
## ไลบรารีอื่นๆ
รวมไลบรารีต่างๆ นอกเหนือจากหัวข้อด้านบนสำหรับใช้งานกับ ESP8266

### AT Command Library
รอเพิ่ม

### ArduinoIDE C++ Library
รอเพิ่ม

### Lua Script Library
รอเพิ่ม

# Contributing

เนื่องจากข้อมูลของ ESP8266 เยอะมากๆ ท่านใดอยากเพิ่มเติมหรือแก้ไขอะไรตรงไหนผมยินดีมากเลยครับ สามารถส่งโดยการกด fork แล้ว pull request มาได้เลยหรือ Inbox มาที่ fb.com@0x53756e ได้เลยครับแล้วผมจะรีบลงให้เพื่อให้หลายๆท่านที่มาใหม่จะได้ไม่หลงทางครับ

- [การ Pull Request](https://guides.github.com/activities/contributing-to-open-source) - ลองอ่านในส่วนของ Pull Request นะครับ

Facebook Group: [ESP8266 THAILAND](https://www.facebook.com/groups/465468593611712)
