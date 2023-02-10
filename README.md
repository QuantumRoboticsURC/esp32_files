# ESP32 files repo

This repo contains the files that are uploaded in the esp32 board
and **THE OTA TEMPLATE FOR ANY OTHER FILE THAT WE WISH TO UPLOAD** 
**TO ESP32**, such template is called **arduino_ota_template.ino**
and contains within it comments that indicate the part of the code
where new code should be.

OTA is the API that we use to upload arduino code wirelessly, but any 
new file that we upload to ESP32 should contain the logic on the
OTA template if we whish to continue uploading new code wirelessly.
Therefore **you should always use the OTA template when you upload**
**new code**

## HOW TO UPLOAD NEW CODE

On your personal computer connect to the network called **QR_ESP32_Wifi**
the password for such network is **quantum_main_root**, then on your 
prefered browser type the IP address **1.1.1.1**. A login prompt will
appear, use the credentials:

- user: admin
- password: admin

Then, just use the browser UI to upload your new code 😀
