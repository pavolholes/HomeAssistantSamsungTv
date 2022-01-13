# HomeAssistantSamsungTv
Samsung TV scripts, automations, lovelace

I'm using HomeAssistant - SamsungTV Smart Component from HACS: https://github.com/ollo69/ha-samsungtv-smart

In the files you can find the relevant parts of the configuration:
- configuration.yaml
  - how you can include the below files to your configuration (how to split configuration.yaml to multiple files)
- scripts.yaml
  - multiple scripts, each for one "remote" button press / TV function
- automations.yaml
  - one automation which listens to events from HomeKit and call the appropriate scripts to do the actions on the TV. You can use the Remote Widget in the Control Center from your iOS device to quickly control the TV
