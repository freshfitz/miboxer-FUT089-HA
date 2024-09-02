# miboxer-FUT089-HA
Add miboxer FUT089 Rgb remote to home assistant zibgee2mqtt

First install zigbee2mqtt plugin : Settings -> Add-on -> add on store <br><br>
Add the code from configurtaion.yaml to your main configuration.yaml, Do not overwrite append this to the bottom of it !!!!!  <br><br>
Restart HA: Developer Tools -> Restart <br><br>
add the blueprint.yaml <br><br>
Goto Settings -> Automations and Scenes -> Blueprints -> import blueprint and put https://github.com/freshfitz/miboxer-FUT089-HA/blob/main/blueprint<br><br>
Create an automation with the remote, sensors and a light or light group ad the light device <br>
