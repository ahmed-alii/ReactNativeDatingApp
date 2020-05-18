# ReactNativeDatingApp
If you have Homebrew installed, go to next step, else: 

$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Install node
$ brew install node

Install React Native CLI
$ npm install -g react-native-cli

Go to the project folder and install dependencies
$ cd PROJECT_DIR

$ npm install
Link native modules

$ react-native link

$ cd ios

$ pod install

# Useful doc https://facebook.github.io/react-native/docs/getting-started

Install Android SDK http://www.androiddocs.com/sdk/installing/index.html

Set ANROID_HOME on MAC https://stackoverflow.com/questions/19986214/setting-android-home-enviromental-variable-on-mac-os-x

Set ANDROID_HOME on Windows https://www.360logica.com/blog/how-to-set-path-environmental-variable-for-sdk-in-windows/

# Run Android app
Please connect android device or run emulator

$ react-native run-android

# Run iOS app

Please install Xcode https://medium.com/@LondonAppBrewery/how-to-download-and-setup-xcode-10-for-ios-development-b63bed1865c

It appears to be a problem with the location of Command line tools. In Xcode, select Xcode menu, then Preferences, then Locations tab. Select your Xcode version from the dropdown and exit Xcode.

$ react-native run-ios
