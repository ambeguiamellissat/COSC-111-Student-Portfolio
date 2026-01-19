# Laboratory Activity 7 – Controlling Arduino using FastAPI

### [📌 Folder: `Activity7_FastAPI`](.)

### Description
This activity adds an HTTP layer using **FastAPI** to control Arduino through web API.

### Key Features
- Uses same circuit as Activity 6
- FastAPI endpoints:
  - `/led/<color>` (red, green, blue)
  - `/led/on`
  - `/led/off`
- API sends commands to Arduino via serial

### Files Included
1. [Arduino sketch (.ino)](./Lab_Act7_BSCS4B_Arduino.ino)
2. [Python FastAPI script (.py)](./Lab_Act7_BSCS4B_Arduino.py)
3. [Header file](./LedController.h)
4. [Breadboard diagram](././Lab_Act7_BSCS4B_Arduino.png)
5. [Members’ grades](./lab7-controlling-arduino-using-fastAPI-Grades)

