# LightWaveRFSmartthingsLocalDeviceCreator
Note requires https://github.com/adamclark-dev/smartthings-lightwave-node-server

This is a Groovy SmartApp for SmartThings that interogates the LightwaveRF Connect server (Gen 1 devices) and then creates devices using Adam Clark's device handlers for each LightwaveRF device

Notes doesn't work for Gen 2 device. Doesn't work for legacy accounts with a pin unless that account has been used at the new conect portal at manager.lightwaverf.com. Only works for switches, dimmers and open/close/stop (relay) devices

Copy and paste the code into a new smartapp in the Smartthings api.

When you install the app you will be prompted for your LightWaveRF Connect username and password and the address of the Node.js server (from Adam's code) and the LightwaveRF link on your network. You can safely ignore the prompt for Assign A Name and Set for Specific Modes. Tapping Done and Installing the app creates the devices

If you are having issues setting up Adam's server then please refer to the smartthings community thread,

https://community.smartthings.com/t/lightwave-rf-integration-uk/23875/447

If there are issues with the code, then please raise an issue on github. As Adam says on his repository an issue with the code is not that you are incapable of setting it up :-)
