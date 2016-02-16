<div align="center"><img src="http://i.imgur.com/gbbeJFH.png"/><br><br>[![Platform](https://img.shields.io/badge/platform-iOS-lightgrey.svg?style=flat)](http://www.apple.com/ios/)&nbsp;&nbsp;&nbsp;[![License (MPL)](https://img.shields.io/badge/license-MPL-lightgrey.svg?style=flat)](http://opensource.org/licenses/MPL-2.0)</div><h4>_Q: What is Open Source Selfie Stick?_<br>A: A free open source iOS app which allows you to pair any two iOS devices, using one as a camera and the other as a remote control. Just tap the button on the remote control, and the device designated as the camera will snap a photo (thus the software is acting as a sort-of "virtual" selfie stick.<br><br>_Q: How does this app work?_<br>A: This app leverages the [Multipeer Connectivity Framework](https://developer.apple.com/library/ios/documentation/MultipeerConnectivity/Reference/MultipeerConnectivityFramework/) to allow the devices to communicate over WiFi or Bluetooth.<br><br>_Q: Does it work over Bluetooth?_<br>A: Yes, but Bluetooth is much slower; it can take 10-20 seconds to send a photo over Bluetooth, while over WiFi this process takes 2-3 seconds.<br><br>_Q: Can I contribute to the development of this app?_<br>A: Yes! Feel free to fork this repo, look at the to-do list, and make a pull request.<br><br>_Q: Can I download this app from the App Store?_<br>A: This app is currently pending review/release with the App Store. For now, you can download this project on any Mac, open it with Xcode 7.2.1, and build it on any Apple mobile device with iOS v8.1 or higher via USB.<br><br>_Q: I found a bug. How do I report it?_<br>A: Create a [new issue](https://github.com/RF-Nelson/open-source-selfie-stick/issues/new) on GitHub's issue tracker. Please provide as much detail as possible so we can attempt to reproduce the error you're experiencing.

### TO DO
- [x] Give user the option to save photos on either or both devices
- [x] Add an optional timer
- [x] Add file transfer progress bar if remote control device is receiving a file
- [ ] Viewable gallery of photos from current/most recent session
- [ ] Make a more aesthetically pleasing UI
- [ ] Share your newly taken photos on Facebook and Twitter with SocialKit
- [ ] Allow the recording and sharing of video clips
- [ ] Allow the device acting as the remote control to receive a live video feed
- [ ] Allow multiple devices to act as cameras or remotes
- [ ] Refactor
- [ ] Come up with a better name than "Open Source Selfie Stick"
- [ ] Add support for multiple languages

<br><br>
__*License*__<br>
This software is licensed under the [MPL version 2.0](http://mozilla.org/MPL/2.0/).<br>

__*Logo credits*__<br>
Logo created with <a href="http://logomakr.com" title="Logo Maker">Logo Maker</a>. The camera, person, and phone icons seens within the logo are from <a href="http://www.freepik.com/">Freepik</a> from <a href="http://www.flaticon.com/">Flaticon</a>. They are licensed under <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0">CC BY 3.0</a>.

__*Special Thanks*__<br>
Thanks to [Joystick Interactive](https://github.com/joystickinteractive/), [Alex Konrad](https://github.com/alexkonrad), [Ralf Ebert](https://www.ralfebert.de/tutorials/ios-swift-multipeer-connectivity/), [Ray Wenderlich](http://www.raywenderlich.com/), and my wife. Without them this project may not exist.
