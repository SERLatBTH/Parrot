# Parrot BEBOP 2 FPV
Parrot Drone - guide, instructions, assembly, and sdk

Please follow the instructions.

## Content
* [Where To Find](#where-to-find)
* [In The Box](#in-the-box)
* [How To Make It Works](#how-to-make-it-works)
  * [Assembly](#assembly)
  * [Charging The Batteries](#charging-the-batteries)
  * [Powering Up](#powering-up)
* [Device's Functionalities and Features](#devices-functionalities-and-features)
* [Safety Guidelines](#safety-guidelines)
  * [Environmental Consideration](#environmental-consideration)
  * [Operation](#operation)
  * [Pre-Flight Checklist](pre-flight-checklist)
* [Accessories](#accessories)
  * [DJI Goggles](DJIGoggles)
  * [Mavic 2 Fly More Kit](#mavic-2-fly-more-kit)
* [Putting The Device Back](#putting-the-device-back)
* [More Documentations](more-documentations)



### Charging the Batteries

There are two charges provided with the Parrot BEBOP 2 FPV. One to charge the drone battery and the other to charge the remote controller.

#### Charging the Parrot BEBOP 2Battery
1. Select the plug (provided) for your country and put it
on the charger.
2. Connect the supplied cable to the charger.
3. Connect the battery to the charger's cable, and then plug the charger into the mains.
   * The warning light is red while charging and then turns green when the battery is charged. The battery charge time is approximately 80 minutes. Flying time is approximately 30 minutes.
#### Charging the Parrot SkyControlller 2 Battery
1. Take the adapter appropriate to your country and fix it on the charger.
2. Connect the charger cable to Parrot Skycontroller 2, then plug the charger into the mains.

### Powering Up
1. To start the drone press the white button on the back of the drone.
2. The button will blink red for color indicating the boot process in progress.
3. When it turns steady red then it is ready to be used.

### Connecting a Smartphone
1. Download FreeFlight Pro app that correspond to your mobile device OS. You can get it from [google play](https://play.google.com/store/apps/details?id=com.parrot.freeflight3&hl=en) Or [app store](https://apps.apple.com/se/app/freeflight-pro/id889985763)
2. Switch the Parrot Bebop 2 on.
3. On your smartphone, carry out a search for Wi-Fi® networks available:·if you are using an iPhone or an iPad, select Settings > Wi-Fi;·if you are using an Android™ smartphone, select Settings > Wireless and networks> Wi-Fi.
4. Select the network: Bebop2_xxxxx.
5. Wait for your smartphone to connect to the Wi-Fi network of the Parrot Bebop 2. This connection is generally represented by the Wi-Fi logo appearing on the smartphone screen.
6. Launch the FreeFlight Pro application.> The connection between your smartphone and the Parrot Bebop 2 is established automatically.

### Connecting the Parrot SkyControlller 2
1. Place the Parrot Bebop 2 on a flat surface.
2. Switch on your Parrot Bebop 2.
3. Press the ON/OFF button on the Parrot Skycontroller 2 to turn it on.
4. Wait until the warning light is solid green.
   * Now you are connected to the Parrot Bebop 2 Power, you can control it.

### Using the Parrot SkyControlller 2 With A Smartphone
1. Screw the smartphone holder onto the Parrot Skycontroller 2.
2. Press the right button on the holder to fully open it.
3. Position your smartphone on the holder.
4. Tighten the holder on your smartphone.
5. Turn on Parrot Skycontroller 2 and your drone
6. Using your smartphone's USB cable, connect your smartphone to the Parrot Skycontroller 2's USB port.
   * The FreeFlight Pro app starts automatically. You are connected.

### Using The Parrot Cockpitglasses 2
FreeFlight Pro in FPV mode must be enabled before placing the smartphone in the Parrot Cockpitglasses 2.
1. Plug one end of your smartphone's USB cable into the Parrot Skycontroller 2 and the other end into your smartphone.
   * If this has not yet been done. The FreeFlight Pro app will launch automatically on your smartphone.
2. In the FreeFlight Pro app, go to Fly & Film and press the FPV icon.
   * FPV mode launches on your smartphone.
3. Unfold the Parrot Cockpitglasses 2.
4. Connect the Parrot Skycontroller 2 to the drone.
5. Open the front cover of the Parrot Cockpitglasses 2.
6. Place the smartphone in the center point of the height and length of the Parrot Cockpitglasses 2.
7. Close the front cover to hold the smartphone in the Parrot Cockpitglasses 2.

## SDK
Parrot has a [developer website](https://developer.parrot.com/) that can be accessed [here](https://developer.parrot.com/)

### Ground SDK Mobile
Parrot Ground SDK Mobile is available as a ready-to-compile source code, an iOS CocoaPods and an Android AAR. Ground SDK Mobile allows any developer to create its own application for ANAFI. All the features of the ANAFI (control, video, settings) are accessible through an easy-to-use and fully documented API set. The code is released under BSD-3 license, along with a quick start guide, full API documentation, and a ready-to-use demo application implementing all the available APIs.

* Ground SDK iOS: [quick start guide](https://developer.parrot.com/docs/groundsdk-ios/), [API documentation](https://developer.parrot.com/docs/refdoc-ios/)
* Ground SDK Android: [quick start guide](https://developer.parrot.com/docs/groundsdk-android/), [API documentation](https://developer.parrot.com/docs/refdoc-android/)


### PDrAW
Video player and metadata
+ PDrAW (pronounced like the name Pedro) is a video viewer for medias created by Parrot drones, like ANAFI. The viewer supports both streamed (RTP/RTSP) and recorded (MP4) videos, on Linux, macOS, Android and iOS platforms.
+ PDrAW is the video pipeline implementation of Parrot Ground SDK Mobile, used in Parrot’s FreeFlight6 application, both on iOS and Android.
+ Full documentation can be accessed [here](https://developer.parrot.com/docs/pdraw/).

### OLYMPE
Python framework for drone and simulation
+ Olympe provides a Python controller programming interface for Parrot Drone.
+ The main purpose of Olympe is to be used with Parrot's simulation environment, Sphinx, but it can also be used to control physical drones from a remote computer.
+ Full documentation can be accessed [here](https://developer.parrot.com/docs/olympe/).


###  SPHINX
Full simulation environment
+ Parrot Sphinx is a simulation environment for Parrot Drones, based on the Gazebo engine. It was developed for prototyping and testing drone software.
+ You will also be able to test your Ground-SDK application with Sphinx, before using it on a real drone.
+ Full documentation can be accessed [here](https://developer.parrot.com/docs/sphinx/).


###  3D Model
Create, Simulate, Print
+ You can download the blender 3D model of Parrot ANAFI to integrate in your project, or create and print add-ons and accessories!
+ The application can be downloaded from [here](https://developer.parrot.com/downloads/Parrot-Anafi.blend.zip)
