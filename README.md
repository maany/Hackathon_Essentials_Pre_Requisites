# Hackathon Essentials Cookbook

## Android Studio
1. Install the latest Android Studio for your OS from https://developer.android.com/studio/ 

1. Open Android Studio IDE, start a new Blank Project. Then go to **Tools -> SDK Manager**

1. If you have an Android Phone, note the version of the Android OS installed on your phone. In the **SDK Platforms tab**, download Platform for **Android P Preview** and for the **version of Android OS installed on your phone**.
    p.s. If you do not have an Android Phone, you can work with a friend who has it. Hackathons are about team work after all!

    ![SDK_PLATFORMS](./images/sdk_platforms.png)

1. Head over to the **SDK Tools tab** and ensure that SDK Tools ver 26.1.1 is installed. If not, install them.
    ![SDK_TOOLS_TAB](./images/sdk_tools.png)

## Driver for the Android Device

1. If you want to use your android device during the session, you **might** have to install drivers to allow your computer's OS to install and debug your device directly.

1. First things first, enable 'Developer Mode' on your Android Device. For most devices, you can head to Settings -> About Phone and then tap Build Number list item multiple times. Use Google to find out how to enable developer mode on your device.

1. Before we try to find and install the correct driver for your device on the PC, let's check whether your OS (mostly Linux/Mac) support it out of the box.
    1. Connect your device via the USB cable to your PC.
    1. Click the run button (green play button) next to your project name in the toolbox ribbon located at the top right hand side of the IDE.
    ![RUN_BUTTON](./images/android_run.png)
    1. If you see your device in the list of connected devices, you are good to go and can move on to the next section.
    ![deployment_target](./images/deployment_target.png)
    1. So, I assume if you are readind this, you do not see your device in the 'Select Deployment Target' dialog. Well, Try to search Google for "{Your device's Manufacturer/Model} " + "driver" +  "{OS installed on your PC}". If everything fails, open an issue in this repository and we can try to investigate a bit further.

1. All set!! \m/

## Arduino and Esp8266
