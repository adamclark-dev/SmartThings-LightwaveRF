# SmartThings LightwaveRF Integration

This integration allows you to turn control your [LightwaveRF](http://lightwaverf.com/) devices from the [SmartThings](http://www.smartthings.com/) mobile and web applications.

I haven't checked but am sure this will be against the LightwaveRF terms of service, so please use at your own risk.

## Installation
For video instruction of how to install a device wathc this [Youtube video](https://www.youtube.com/watch?v=THVWnSFZSI0).

1. Create a new device type (https://graph.api.smartthings.com/ide/devices)

2. Click the select from code tab at the top of the page and paste the contents of [onOffDevice.groovy](https://github.com/adamclark-dev/smartthings-lighwaverf/blob/master/onOffDevice.groovy) into it. Then click create.

3. Create a new device (https://graph.api.smartthings.com/device/list)
    * Name: Your Choice
    * Device Network Id: Your Choice (needs to be unique)
    * Type: Lightwave Lights (should be the last option)
    * Location: Choose the correct location
    * Hub/Group: Choose your hub
    
4. Update device preferences
    * Click on the new device to see the details.
    * Click the edit button next to Preferences
    * Fill in your information.
