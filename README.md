![SysUpdate API](assets/sysupdatelogo.jpg)
A simple service for getting system update data for gaming consoles



## Important things first
This service connects to other servers, in order to gather information. These are:
- Nintendo's japanese support pages
- SONY's official update servers

I am not affiliated with both companies in any way, regarding this project.
If either SONY or Nintendo want this project to be closed, please notify me about it (and provide a proof of beeing a real employee of the company in charge). I carefully checked this project and can state, that this project doesn't contain URLs of update data and other confidential information, just the version number and the date it was published.

## Description
SysUpdate is an API gathering data on system updates from variopus platforms.
It collects them from official sources and encodes them as a JSON array, ready to be used within other services and apps.
The recieved data contains the firmware version (for example 11.9.0-42) and the date, the update was published.

## Usage
Use this URL scheme to use this service:
https://sysupdate.stvs.me/v1/platform (replace platform with your desired platform)
You can get data for the following platforms:
  - Nintendo Switch (switch)
  - Nintendo 3DS (3ds)
  - Playstation 4 (ps4)
  - Playstation VITA (psvita)
