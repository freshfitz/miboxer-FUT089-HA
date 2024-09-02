# miboxer-FUT089-HA
Add miboxer FUT089 Rgb remote to home assistant zibgee2mqtt

First install zigbee2mqtt plugin : Settings -> Add-on -> add on store 
Add the code from configurtaion.yaml to yuor main configuration.yaml, do not overwrite append this to the bottom of it.
Restart HA: Developer Tools -> Restart
add the blueprint.yaml.
Goto Settings -> Automations and Scenes -> Blueprints and create an automation with the remote, sensors and a light or light group ad the light device 
