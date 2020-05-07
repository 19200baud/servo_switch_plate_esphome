# servo_switch_plate_esphome

This yaml file for use with ESPHome is setup to be used with Servo Switch Plate Mount by carjo3000 (https://www.thingiverse.com/thing:1156995) or any derivatives of this item.

## Mandatory Changes:
### Under the esphome section:
  Change the name to the desired name to be shown in ESPHome (eg. living_room_light)
###  Under the wifi section:
  Set wifi_ssid and wifi_pass to match your entries in your secrets.yaml or replace "!secret wifi_ssid" and "!secret wifi_pass" with your SSID and password in quotes. You will also need to edit the SSID and password for the backup AP.
 ### Under the switch section:
  Change the name of your switch. (eg. Living Room Light)

## Optional Changes:
### Webserver:
  Uncomment the lines begging with web_server and port.
### Arm Movement:
  Change the 40% and -40% to the correct values needed to turn the light switch on and off without hitting the end of travel or stalling the motor.
