# DETA-Switches
Esphome templates for deta switches


These are some ESP-home templates for the 1 2 3 and 4 gang switches.

ihave all these tempaltes working and use manual method to upload.
use and modify as you see fit

if you want to use the switch for exhaust fan you can change light to fan and will show up as fan
eg
light:
  # Top button
  - platform: binary
    name: "En-suite Light"
    output: relay1
    id: light1

fan:
  # Bottom button (delete for single switch)
  - platform: binary
    name: "Ensuite Fan"
    output: relay2
    id: fan1
    
    
    if you need any more help drop me a message and will try to help
    
