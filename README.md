# MobileAutomation


## Appium

bundle identifier com.apple.test.WebDriverAgentRunner-Runner


## Appium Prep
### Simulator

* install WDA 
* launch WDA

### Device for Mac

* resign
* make WDA to ipa 
* install WDA to iPhone
* launch WDA and get port

### Device for Linux/Windows

* resign
* make WDA to ipa 
* install WDA to iPhone
* launch WDA and get port

## Test Client

* query WDA 
    ** which port
    ** simulator or real device?
* install testing ipa
* run test


## Documents

https://stackoverflow.com/questions/31179706/how-can-i-launch-the-ios-simulator-from-terminal
https://www.iosdev.recipes/simctl/#:~:text=The%20simctl%20command%20controls%20iOS,see%20the%20built%2Din%20help.
https://appium.readthedocs.io/en/latest/en/drivers/ios-xcuitest-real-devices/


```shell
xcrun simctl launch booted <app identifier>
xcrun simctl uninstall booted <app identifier>

# install
xcrun simctl install booted /Users/ST22956/Desktop/MobileAutomationTest/Tools/WebDriverAgentRunner-Runner.app

# launch 
xcrun simctl launch E4907C51-50D7-4E83-8CD1-41EE868F02F1 com.apple.test.WebDriverAgentRunner-Runner

```
