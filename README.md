# WiFi-captive-portal-for-ESP8266-Fake-upgrade

## Disclaimer
This project is for testing and educational purposes. Use it only against your own networks and devices. I don't take any responsibility for what you do with this program.

## About this project
WiFi captive portal for the NodeMCU (ESP8266 Module) with DNS spoofing. It asks the user for a password for a fake firmware upgrade , in order to "get connected to the internet".

The built-in LED will blink 5 times when some credentials are posted.

<b>Warning!</b> Your saved credentials will disappear when you restart/power off the ESP8266.

<b>Note:</b> If you want to see the stored credetials go to <a>"**http**://</a>yourcurrentwebsite.com<a>/creds</a>" or "**172.0.0.1**<a>/creds</a>"

# Screenshots

<table>
  <tr>
    <th>172.0.0.1/index</th>
    <th>172.0.0.1/post</th> 
    <th>172.0.0.1/creds</th>
  </tr>
  <tr>
     <td><img src="https://github.com/H4cksploit/WiFi-captive-portal-for-ESP8266-Fake-sign-in-/blob/main/src/index.jfif" title="Index">
     <td><img src="https://github.com/H4cksploit/WiFi-captive-portal-for-ESP8266-Fake-sign-in-/blob/main/src/post.jfif" title="Post">
     <td><img src="https://github.com/H4cksploit/WiFi-captive-portal-for-ESP8266-Fake-sign-in-/blob/main/src/creds.PNG" title="Creds">
  </tr>
</table>





# Installation (Arduino IDE)

1. Open your <a href="https://www.arduino.cc/en/main/software">Arduino IDE</a> and go to "File -> Preferences -> Boards Manager URLs" and paste the following link:
``http://arduino.esp8266.com/stable/package_esp8266com_index.json``
2. Go to "Tools -> Board -> Boards Manager", search "esp8266" and install esp8266
3. Go to "Tools -> Board" and select you board"
4. Download and open the sketch "<a href="https://github.com/H4cksploit/WiFi-captive-portal-for-ESP8266-Fake-sign-in/blob/main/ESP8266_WiFi_Captive_Portal"><b>ESP8266_WiFi_Captive_Portal</b></a>"
5. You can optionally change some parameters like the SSID name and texts of the page like title, subtitle, text body...
6. Upload the code into your board.
7. You are done!
