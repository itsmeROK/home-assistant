# Hue temperatures correction

It seems Hue motion sensor seems get low temperatures by some reason, so there is small help for get more correct temperatures.


Brief instructions: 

- Open Settings and Devices & Services section and then Helpers tab.
- Press button create helper and choose template and then Template a sensor
- Add each option in correct place from what found on room hue sensor file.
- Change about sensor state content real hue sensor entity id to your custom.
- Then Submit this sensor and sensor will start collect history data. 


## My custom Hue temperatures corrections

- olkkari
olkkari_hue_motion_sensor_2_lampotila
fix +0.9

- makkari
hue_motion_sensor_1_lampotila
fix +1.9

- mi*
hue_motion_sensor_4_lampotila
fix +1.1

- ra*
hue_motion_sensor_3_lampotila
fix +1.5

- outdoor
sensor.hue_outdoor_motion_sensor_1_lampotila
fix -0.4

