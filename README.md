# Bike-Alarm-System

A bike alarm system using Arduino Nano 33 BLE that includes the following function:

- Making loud alarming sound when the bike is being shaked or pushed.
- Tone of the alarm is customisable, alarm activation threshold can be adjusted using an app on phone via bluetooth-low-energy (BLE).
- Alarm can be activated and deactivated by the app via BLE.
- Having external LED arrays that can act as turn signal lights, controled by buttons on the bike handle.
- Alarming people nearby when the cyclist suddenly falls down.

The bike alarm system has the following design requirements:

- Having a battery that can at least last for 2 weeks.
- Having a solar panel that can charge the battery when there is light.
- Having a USB type-C port that can be used to charge the battery in emergency.
- The system should be built on a PCB board, inside a 3D-printed casing, and should be as small as possible or intergrated with other devices (e.g. bike turn signal lights) to avoid being noticed and removed easily by the thief.
- The system should be at least IP65 rated.
- User should be able to access the "Reset" button of the board from the casing, for example, through a small hole.
