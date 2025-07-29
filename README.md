# ScienceEventBadge
This repository in set up process. It will finally provide all hardware design files (KiCad) for the ScienceEventBadge. The PCB design was originally created in 2025 for the "Jugend-forscht" state competition in Saxony-Anhalt in 2026.

## Hardware Description
- Main controller: ESP32-C6 (WiFi, BLE, ZigBee, Thread, Matter)
- Co-processor: ATTNY1617
- On-board sensors:
  - AHT20 - temperature and humidity
  - BMP388 - barametric pressure
  - SGP-40 - VOC-index (air quality) 
  - Light sensor (LDR)
  - LIS2DH12 - Accellerometer
- Data logging features:
  - highly-precise RTC module with backup battery
  - 4MB on-board flash memory
  - µSD-card slot
- Power supply
  - CR123A 3V Lithium battery
  - or USB-C
 
## Hardware Images
### Version 1 from March 2025
<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/090fab9f-3933-46d3-b6cf-7de57049fbcd" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/99dffc1a-d4d5-4ea0-ad15-8fa0ed605f88" width="400"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/d21ba79e-8631-402e-88ad-ed6c868e79de" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/3e153df6-ddbc-45c5-9e4b-07046590bdda" width="400"/></td>
  </tr>
</table>


### Version 2 from July 2025
<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/0eaa26ea-ccc8-47fd-8be7-e7ae5dca05b0" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/997f2e3d-0c81-4cea-ac36-75cfed9716dd" width="400"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/ae9034a7-65d9-4d8c-9305-f41a091c87d4" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/eea2973e-abd6-4b87-a865-75ed27db1ccb" width="400"/></td>
  </tr>
</table>

