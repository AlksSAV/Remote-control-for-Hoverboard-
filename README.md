# Remote-control-for-Hoverboard-
Radio control of the hoverboard using the ESP-NOW protocol. This repository contains code for 3 channel  transmitter and receiver. **The board must be under PWM mode.**\

Радиоуправление ховербордом с использованием протокола ESP-NOW. Это хранилище содержит код для 3-канального передатчика и приемника. **Плата должна быть прошита под режим PWM.**

----------

**Receiver \ Приемник**
![Screenshot](Receiver.jpg)

**Transmitter \ Передатчик**
![Screenshot](Transmitter.jpg)

----------
Настройки в Arduino IDE\
In the Arduino IDE, add to the board manager - https://dl.espressif.com/dl/package_esp32_index.json

-----------
First you need to determine the MAC address of the receiver. To do this, use "GetMacAddress.ino" Then proceed to the firmware of the transmitter and receiver.\
Сначала вам нужно определить MAC-адрес приемника. Для этого воспользуйтесь "GetMacAddress.ino", затем перейдите к прошивке передатчика и приемника.

Ссылка на прошивку. https://github.com/EFeru/hoverboard-firmware-hack-FOC.git \ 
Description of the firmware of the hoverboard boards

An example of the work on my channel\
Пример работы https://youtu.be/sdt3OQeafr4
