1. Introduction
This utility CardEasy.exe is a tool to let users to evaluate smart cards 
(e.g. memory cards, MCU cards, etc) on ACS readers through COM/USB ports. It 
works for both ACS proprietary and PC/SC interface. Furthermore,it only runs 
on 32-bit window environment (e.g. Win95/NT/98/ME/2K). Readers ACR10, ACR20 
and ACR30 are supported. Please note that PC/SC operation can only be 
activated/selected if both PS/SC and ACS proprietary drivers are installed 
on the same system.

To run this application, connect a reader to a COM/USB port with a smart card 
inserted in the opening slot. Then click on the icon CARDEASY.EXE in the Window 
environment. Depending on the port/setting selection, setting can be made by 
selecting tag "VIEW"=>"Hardware Configuration" and select the proper
setting on the device interface option. There are 7 options: 
- "COM1, COM2, COM3, COM4, USB, keyboard" are for ACS proprietary drivers;
- "PC/SC" are for the standard PC/Sc interface.

To get more operation information, select "help topic" from the main menu "HELP"
when application is up.




2. Installation
There are two things needed to be installed: Utility application and drivers.

2.1 Utility Installation
Copy all files in this folder into a temporary directory or any folder you want.

2.2 Driver installation
* For ACS Proprietary drivers Installation:
  It is described in folder "\ACSProprietary\readme.txt" .
* For PC/Sc driver installation: 
  - Run the \PCSC\INSTPAN.EXE in window environment;
  - Click the button "Install" to let system to install all necessary PC/SC 
    drivers automatically. This would actually de-install all the previously 
    existed drivers (if any) and install all over again.







