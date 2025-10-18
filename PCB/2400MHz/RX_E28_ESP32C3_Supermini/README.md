# Solder Friendly 2.4GHz ESP32-C3 ExpressLRS Receiver

## 🚀 The Easiest DIY ExpressLRS Receiver in the World

This project is **super easy to make** and **ultra low cost**.  
You only need **two modules** — no SMD soldering, no extra components
No FTDI needed, use type-C integrated:

- 🧠 **ESP32-C3 SuperMini**
- 📡 **E28 2.4GHz LoRa Module (SX1280)**

Just solder these two modules on a PCB, flash the firmware, and you have a working ExpressLRS 2.4GHz receiver!

---
## Video

https://youtu.be/4iFyOv_jBPY?si=ccF2sKkLWnAkUwgd

## Features

* 20x30 footprint
* No SMD components (for easy soldering)
* Components are placed for ease of soldering (easy iron access)
* Use ESP32-C3 Supermini developerment board (LDO, LED already solded)
* 2.4G LORA Module E28

### Wiring Diagram

You can hand made use this wiring diagram, or use PCB below

<img src="img/ESP32_C3_RX_wire.jpg" alt="ESP32-C3 RX Wiring" width="600">

## Editing

* The PCB has been developed in EasyEDA.
  
<img src="img/ESP32_C3_RX_PCB_Top.jpg" alt="ESP32-C3 RX Wiring" width="300">   <img src="img/ESP32_C3_RX_PCB_2layper.jpg" alt="ESP32-C3 RX Wiring" width="300">

### Schematic

<img src="img/ESP32_C3_Schematic_1.jpg" width="600">

## Ordering

* I've had good results using JLCPCB.

## BOM

* ESP32-C3 Super Mini
* Ebyte E282G4M12S Module

## Flashing

Plug in usb cable to computer, use web-flasher, choose BAYCKRC 2.4G ESP32-C3 RX

![image](https://github.com/user-attachments/assets/e8b2ca33-af9f-4754-87e6-f21ab62a8a76)

## Config

Change output 5 and 6 to Serial RX & TX

goto 10.0.0.1/hardware.html

RGBLED to none
LED pin to 8
RED LED pin to 8
Check RED LED inverted

![alt text](image.png)


## RX

<img src="img/RX.jpg" width="600">
<<<<<<< HEAD

## Resources

E28 datasheet
https://www.cdebyte.com/pdf-down.aspx?id=2264

ESP32-C3 datasheet
https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf


=======
>>>>>>> cb007112ee4e6174a68fdcb63059d0fb015118df
