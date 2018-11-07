---
layout: post
title: Regensensor, erste Version
image_banner: steckbrett_banner.jpg
image_thumb: steckbrett_thumb.jpg
author: Matthias Müller
---
## Regensensor, erste Version

Die Spezifikation für unsere ersten 10 Mess-Systeme ist fertig:

* Regensammler (Pluviometer) von [Davis](https://www.davisinstruments.com/product/aerocone-rain-collector-with-flat-base-for-vantage-pro2/)   
* Temperatur- und Luftfeuchtesensor [Sensirion SHT31](https://www.sensirion.com/en/environmental-sensors/humidity-sensors/digital-humidity-sensors-for-various-applications/)
* Luftdrucksensor [Bosch BMP 280](https://www.bosch-sensortec.com/bst/products/all_products/bmp280)
* Neigungsschalter zur Lagekontrolle
* Stromsparendes Counter IC 74HC4024 für das Auslesen des Regensensors
* ELCO IoT-Board mit Mikrocontroller, GSM, RTC, GPS und Akku-Überwachung
* ... sowie ein optionales LoRa-Modul als sekundärer Übertragungskanal
* LiPo-Akku mit 10.000 mAh, optionales Solarmodul

Das Design wird derzeit von der Hardwarefertigung geprüft. Die ersten Exemplare erwarten wir noch
im September.

Diese ersten Exemplare dienen der Erprobung von Sensorik, Datenübertragung, Firmware und Konstruktion. Nach
der Erprobungsphase werden die verbleibenden Geräte angefertigt.
