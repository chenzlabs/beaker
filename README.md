# beaker
Barebones example using https://github.com/chenzlabs/react-native-ibeacon-simulator

NON-TRIVIAL PREREQUISITE: 
- Install react, react-native and react-native-cli.
- For iOS, install XCode and XCode Command Line Tools.
- For Android, install an Android build environment.

THEN:
- `git clone https://github.com/chenzlabs/beaker.git`
- `cd beaker`
- `npm install`
- `react-native link`
- to run on iOS: `react-native run-ios --device="Your iPhone's device name"`
-- NOTE: you may need to open `ios/beaker.xcodeproj` in XCode and select a valid development team.
- to run on Android: `react-native run-android`
