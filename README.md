# ESP32-CaptivePortal

The captive portal code above works...sort of...it will create an Access point, run a web server and a DNS server. Once the user selects the Captive Portal SSID they wil get redirected to a log in page. After entering credentials the page will respind with "OK".
The issue is that the client is not redirected to differnet WiFi access point. This code is also supposed to demonstate how one can steal credentials and display them on the TFT or Serial monitor but I coudln;t get it working.

![IMG_5308](https://user-images.githubusercontent.com/5065324/225166733-a9fa3fbc-9be7-45d1-8dc9-f244a6211c19.jpeg)
