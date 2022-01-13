# Home Assistant Samsung TV scripts, automation for HomeKit Remote Widget and Lovelace cards
Samsung TV scripts, automations, lovelace

I'm using HomeAssistant - SamsungTV Smart Component from HACS: https://github.com/ollo69/ha-samsungtv-smart

In the files you can find the relevant parts of the configuration:
- configuration.yaml
  - how you can include the below files to your configuration (how to split configuration.yaml to multiple files)
- scripts.yaml
  - multiple scripts, each for one "remote" button press / TV function
- automations.yaml
  - one automation which listens to events from HomeKit and call the appropriate scripts to do the actions on the TV. You can use the Remote Widget in the Control Center from your iOS device to quickly control the TV
- lovelace-card-full.yaml
  - one grid card with all scripts in use, screenshot:
    
    ![lovelace-card-full](https://user-images.githubusercontent.com/35877348/149411249-3bd92f48-f348-4cd3-8ef6-7df1c64cab6b.JPG)
- lovelace-card-brief.yaml
  - one grid card with selected script in use, screenshot:

    ![image](https://user-images.githubusercontent.com/35877348/149412057-8a2d817a-b34f-4191-be39-22ff5ed60e7e.png)
- lovelace-popup.yaml
  - I use this code for the Livingroom TV entity popup which I've set in the Dwain's Dashboard

    ![image](https://user-images.githubusercontent.com/35877348/149412368-665c543c-d139-4334-91fd-2b12ad580147.png)

