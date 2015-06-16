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
	- [TCP, UDP, Server, Client, RESTful](#tcp-udp-server-client-restful-api)
	- [MQTT](#mqtt)
		- [Server](#mqtt-server)
			- [ติดตั้งเอง](#แบบติดตั้งเอง)
			- [แบบสำเร็จรูป Online Services](#แบบ-online-serviceser)
		- [Client](#mqtt-client)
	- [อื่นๆ](#อื่นๆ)
- [รวมไลบรารี](#ไลบรารีอื่นๆ)
	- [Libs AT Command](#at-command-library)
	- [Libs ArduinoIDE (C++)](#arduinoide-c-library)
	- [Libs Lua Script (NodeMCU)](#lua-script-library)
- [เว็บไซต์ไว้ติดตาม](#เว็บไซต์ไว้ติดตาม)

---
### ข้อมูลทั่วไป
*รวมข้อมูลพื้นฐานที่ควรรู้ทั้งหมดของ ESP8266*

คำอธิบายแบบยาวๆ (รอเติม)

* [ESP8266 ชิป Wi-Fi ความหวังใหม่ของคนทำคอมพิวเตอร์ฝังตัว Blognone](https://www.blognone.com/node/60187)
* [ESP8266 ตอนที่ 1 รู้จักกับ ESP และรุ่นที่นิยมใช้งาน](http://www.ioxhop.com/article/esp8266-ตอนที่-1-รู้จักกับ-esp-และรุ่นที่นิยมใช้งาน)


*ภาษาอังกฤษ*

* [รายละเอียด Spec จาก Electrodragon](http://www.electrodragon.com/w/ESP8266)
* [รายละเอียด Spec จาก Nurdspace.nl](https://nurdspace.nl/ESP8266)
* [ESP8266_WiFi_Module_Quick_Start_Guide_v_1.0.4.pdf](http://rancidbacon.com/files/kiwicon8/ESP8266_WiFi_Module_Quick_Start_Guide_v_1.0.4.pdf) - อันนี้เขาอธิบายคร่าวๆว่าคืออะไรแล้วการใช้งาน AT Command
* [ESP8266_Specifications_English.pdf](https://drive.google.com/file/d/0B_ctPy0pJuW6Y0FHcDlVY09Xdjg/view)
* [เว็บ esp8266.com](http://www.esp8266.com/)

---
### การติดตั้ง
การใช้งานเบื้องต้นการ Flash Firmware ต่างๆ

* [มา Flash Firmware ให้ ESP8266 ด้วย ESPTool กัน (Linux, Mac)](http://thaiopensource.org/มา-flash-firmware-ให้-esp8266-ด้วย-esptool-กัน)

#### AT Command
* [ESP8266 วิธีทดสอบและใช้งาน โดย Ayarafun](http://www.ayarafun.com/2014/09/esp8266-at-command-tutorial/)
* [สอน วิธี ใช้งาน Arduino Wi-Fi Module ESP8266 โดย Arduinoall](www.arduinoall.com/article/สอน-วิธี-ใช้งาน-arduino-wi-fi-module-esp8266)
* [การอัพเกรด Firmware โดย Thaieasyelec](http://www.thaieasyelec.com/downloads/EWLM107/Update_Firmware_ESP8266.pdf)

*Video*

* [รอเพิ่ม]()

*ภาษาอังกฤษ*

* [การใช้งาน AT Command จาก Electrodragon](http://www.electrodragon.com/w/ESP8266)
* [การใช้งาน AT Command v0.9.2.2](http://www.pridopia.co.uk/pi-doc/ESP8266ATCommandsSet.pdf)


#### ArduinoIDE
* [ตอนที่ 1 ติดตั้ง Arduino IDE ลงบน ESP8266 NodeMCU โดย Thaieasyelec](http://www.thaieasyelec.com/article-wiki/embedded-electronics-application/getting-started-with-esp8266-nodemcu.html) - ตอนอื่นๆไปตามอ่านเอาเองนะครับ
* [เพิ่มบอร์ด ESP8266 ใน Arduino IDE](http://thaiopensource.org/เพิ่มบอร์ด-esp8266-ใน-arduino-ide)
* [มาเริ่มต้นกันกับ NodeMcu v.2 ตอนที่ 1 Getting start](http://robotics-za.blogspot.com/2015/05/esp-12e-nodemcu-v2-writing.html)
* [Review : Arduino IDE 1.6.4 มีอะไรใหม่มาดูกัน](http://www.appstack.cc/2015/05/review-arduino-ide-1-6-4-มีอะไรใหม่มาดูกัน)


*Video*

* [เริ่มติดตั้งบอร์ดNode MCU ESP8266 by wisdomgoody](https://www.youtube.com/watch?v=ocsjRYQhuZQ)

*ภาษาอังกฤษ*

* [ESP8266 Thing Hookup Guide - sparkfun](https://learn.sparkfun.com/tutorials/esp8266-thing-hookup-guide/all)

*Main Repositoty*

* [ArduinoIDE](https://github.com/esp8266/Arduino)

#### Lua Script
* [มาเล่น NodeMCU devkit กัน](http://thaiopensource.org/มาเล่น-nodemcu-devkit-กัน)
* [การใช้งานบอร์ด NodeMCU v2](http://cpre.kmutnb.ac.th/esl/learning/index.php?article=nodemcu_v2)
* [ESP8266 Update NodeMCU Firmware โดย electronic hobby](http://db4linq.blogspot.com/2015/02/esp8266-update-nodemcu-firmware.html)
* [เครื่องมือที่ใช้ในการพัฒนา NodeMCU ด้วยภาษา Lua](http://db4linq.blogspot.com/2015/02/nodemcu-lua.html)

*Video*

* [รอเพิ่ม]()

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
* ESP รีเซตเองบ่อยๆ ลองต่อไฟนอก

* [เมื่อ NodeMCU Firmware มีปัญหา!](http://db4linq.blogspot.com/2015/05/nodemcu-firmware.html)
* [แก้ปัญหา ESP8266 โปรแกรมไม่เข้า , เสีย](http://www.elec-za.com/esp8266-โปรแกรมไม่เข้า)
* [[NODEMCU] - Install CH340 usb to serial driver on OSX Yosemeti](http://www.codenuke.net/2015/01/nodemcu-install-ch340-usb-to-serial-for-yosemite.html)

*Driver สำหรับตัว NodeMCU*

* [CH340 Windows](http://www.wch.cn/download/CH341SER_EXE.html)
* [CH340 Mac](http://www.wch.cn/downloads.php?name=pro&proid=178)

---
### ตัวอย่างการใช้งาน

#### Wifi
อธิบายการใช้งาน WIFI กับ ESP8266

* [รอเพิ่ม]()

#### TCP UDP Server Client and RESTful API
อธิบายการใช้งาน ESP8266 ในการส่งค่ารับค่าด้วย TCP UDP Server, TCP UDP Client

*AT Command*

* [Arduino Nano + ESP8266](http://blog.tui2tone.me/arduino/esp8266/2015/02/07/arduino-wifi-esp8266-control.html)
* [esp8266-กับการควบคุมหลอดไฟ](http://www.elec-za.com/arduino-esp8266-กับการควบคุมหลอดไฟ)

*ArduinoIDE*

* [มาเล่น NodeMCU กับ ThingSpeak](http://thaiopensource.org/มาเล่น-nodemcu-กับ-thingspeak)
* [NodeMcu v.2 กับ ThingSpeak](http://robotics-za.blogspot.com/2015/05/nodemcu-thingspeak.html)
* [NodeMcu v.2 web server กับการควบคุม relay](http://robotics-za.blogspot.com/2015/06/nodemcu-v2-4-web-server-relay.html)

*Free RESTful API*

* [thingspeak.com](https://thingspeak.com/)

#### MQTT
*อธิบายเกี่ยวกับโปรโตคอล MQTT*

* [MQTT](http://csmju.jowave.com/applications/csmju_km/documents_km/20150605113736_KM_MQTT_ESP8266.pdf)

*ภาษาอังกฤษ*

* [MQTT Essentials: Part 1 – Introducing MQTT](http://www.hivemq.com/mqtt-essentials-part-1-introducing-mqtt) - รับรองอ่านหมดเข้าใจแน่นอน
* [MQTT Essentials Part 2: Publish & Subscribe](http://www.hivemq.com/mqtt-essentials-part2-publish-subscribe)
* [MQTT Essentials Part 3: Client, Broker and Connection Establishment](http://www.hivemq.com/mqtt-essentials-part-3-client-broker-connection-establishment)
* [MQTT Essentials Part 4: MQTT Publish, Subscribe & Unsubscribe](http://www.hivemq.com/mqtt-essentials-part-4-mqtt-publish-subscribe-unsubscribe)
* [MQTT Essentials Part 5: MQTT Topics & Best Practices](http://www.hivemq.com/mqtt-essentials-part-5-mqtt-topics-best-practices)
* [MQTT Essentials Part 6: Quality of Service 0, 1 & 2](http://www.hivemq.com/mqtt-essentials-part-6-mqtt-quality-of-service-levels)
* [MQTT Essentials Part 7: Persistent Session and Queuing Messages](http://www.hivemq.com/mqtt-essentials-part-7-persistent-session-queuing-messages)
* [MQTT Essentials Part 8: Retained Messages](http://www.hivemq.com/mqtt-essentials-part-8-retained-messages)
* [MQTT Essentials Part 9: Last Will and Testament](http://www.hivemq.com/mqtt-essentials-part-9-last-will-and-testament)
* [MQTT Essentials Part 10: Keep Alive and Client Take-Over](http://www.hivemq.com/mqtt-essentials-part-10-alive-client-take-over) - จบแล้วครับหวังว่าจะเข้าใจโปรโตคอล MQTT มากขึ้น

* [Introducing the MQTT Security Fundamentals](http://www.hivemq.com/introducing-the-mqtt-security-fundamentals) - ไปตามอ่านหัวข้อเกี่ยวกับ Security กันได้ที่ [http://www.hivemq.com/blog](http://www.hivemq.com/blog) นะครับ


##### MQTT Server

###### แบบติดตั้งเอง
*อธิบายการใช้งานหรือติดตั้ง MQTT Broker*

* [รอเพิ่ม]()

*ภาษาอังกฤษ*

* [รอเพิ่ม]()

*Repository*

* [Mosquitto](http://mosquitto.org)
* [Mosca MQTT Broker](http://www.mosca.io) - Javascript Broker
* [Ponte MQTT Broker By eclipse](https://eclipse.org/ponte) - Javascript Broker
* [GnatMQ - MQTT Broker for .NET and WinRT](https://mqttbroker.codeplex.com) - .NET and WinRT
* [Erlang MQTT Broker](http://emqtt.io) - Erlang

###### แบบ Online Services
*วิธีใช้งานหาดูในส่วนของ client นะครับ*

* [CloudMQTT](http://www.cloudmqtt.com)
* [The MQTT Dashboard](http://mqtt-dashboard.com/info/broker)

##### MQTT Client
รวมวิธีใช้งาน ESP8266 กับ MQTT Broker ต่างๆ

*AT command*

* [รอเพิ่ม]()

*ArduinoIDE*

* [การใช้งาน MQTT บน ESP8266 + Arduino IDE และทดสอบเชื่อมกับ cloudmqtt](http://www.cmmakerclub.com/2015/06/1595)

*Lua Script*

* [รอเพิ่ม]()

*ภาษาอังกฤษ*

* [MQTT Essentials Special: MQTT over WebSockets](http://www.hivemq.com/mqtt-essentials-special-mqtt-over-websockets)
* [The Seven Best MQTT Client Tools](http://www.hivemq.com/seven-best-mqtt-client-tools)

*Repository*

* [hivemq-mqtt-web-client](https://github.com/hivemq/hivemq-mqtt-web-client) - Web Client MQTT
* [ESP8266 network client (mqtt, restful) for Arduino](https://github.com/tuanpmt/espduino) - ไว้สำหรับใช้ Arduino Uno ต่อกับ ESP แล้วเขียนโค้ดลง Uno คุยกับ MQTT Broker โดยใช้ SLIP protocol ผ่าน Serial port
* [MQTT client library for ESP8266 Soc](https://github.com/tuanpmt/esp_mqtt) - MQTT client library สำหรับ ESP8266 เขียนลง Firmware เลย
* [MQTT.js](https://github.com/mqttjs/MQTT.js) - Javascript Client
* [Paho By Eclipse](https://eclipse.org/paho) - มีหลายๆภาษาครับทั้ง Java, JavaScript, Python, Android, C/C++, .NET and WinRT

---
## อื่นๆ
*Work on SDK*
* [esp-open-sdk](https://github.com/pfalcon/esp-open-sdk)
* [esp8266-gpio-mqtt-stdout](https://github.com/terenceang/esp8266-gpio-mqtt-stdout)

*AT Command*

* [รอเพิ่ม]()

*ArduinoIDE*

* [การใช้ ESP8266 อ่านค่า Analog (ADC) อย่างง่าย](http://www.cmmakerclub.com/2015/06/1626) 
* [ทดสอบใช้ PWM บน ESP8266 เขียนด้วย Arduino IDE + dw.EspMini](http://www.cmmakerclub.com/2015/06/1549)
* [การอ่านค่า DHT22 ด้วย ESP8266 Native + Arduino IDE](http://www.cmmakerclub.com/2015/06/1707)
* [การอ่านค่า DS18B20 ด้วย ESP8266 Native + Arduino IDE](http://www.cmmakerclub.com/2015/06/1734)

*Lua Script*

* [มาเล่น NodeMCU กับ DHT22 กัน](http://thaiopensource.org/มาเล่น-nodemcu-กับ-dht22-กัน)
* [รวมตัวอย่าง](https://github.com/db4linq/lua)


---
## ไลบรารีอื่นๆ
รวมไลบรารีต่างๆ นอกเหนือจากหัวข้อด้านบนสำหรับใช้งานกับ ESP8266

### AT Command Library
รอเพิ่ม

### ArduinoIDE C++ Library
* [A client library for the ESP8266 support for MQTT](https://github.com/Imroy/pubsubclient)
* [A simple library that implements a REST API for Arduino & the ESP8266 WiFi chip.](https://github.com/marcoschwartz/aREST)

### Lua Script Library
รอเพิ่ม

## เว็บไซต์ไว้ติดตาม
* [cmmakerclub](http://www.cmmakerclub.com/tag/esp8266-2)
* [thaiopensource](http://thaiopensource.org/tag/esp8266)
* [db4linq](http://db4linq.blogspot.com)

# Contributing

เนื่องจากข้อมูลของ ESP8266 เยอะมากๆ ท่านใดอยากเพิ่มเติมหรือแก้ไขอะไรตรงไหนผมยินดีมากเลยครับ สามารถส่งโดยการกด Fork แล้ว Pull Request มาได้เลยหรือ จะกดที่ Issue แล้วเพิ่มในนั้นก็ได้เลยครับแล้วผมจะรีบลงให้เพื่อให้หลายๆท่านที่มาใหม่จะได้ไม่หลงทางครับ

- [การ Pull Request](https://guides.github.com/activities/contributing-to-open-source) - ลองอ่านในส่วนของ Pull Request นะครับ

Facebook Group: [ESP8266 THAILAND](https://www.facebook.com/groups/465468593611712)
