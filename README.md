# myFourSquare_IVAN

This is the repository for my course IOS Basic using google maps SDK. The full overview is on [Google](https://developers.google.com/maps/documentation/ios-sdk/start)

[![Google Maps SDK](https://lh3.googleusercontent.com/5fJ3bTOM07tpNKSMMillemWCCBBl969q4dyWL4gHUDeHHzStO5_Mkdxg_VBFlASW5CUAldMlrh_78AwIYArTOpg2xpVz2A=s688)](https://developers.google.com/maps/documentation/ios-sdk/map-with-marker)

Learn how to use Google Maps SDK
## Instructions

## Branches

## Documentation

## Installing
- Make sure you have these installed Google Maps SDK for iOS is available as a CocoaPods pod.
Create a Podfile for the Google Maps SDK for iOS and use it to install the API and its dependencies:

- If you don't have an Xcode project yet, create one now and save it to your local machine. (If you're new to iOS development, create a Single View Application.)
Create a file named Podfile in your project directory. This file defines your project's dependencies.
Edit the Podfile and add your dependencies. Here is an example which includes the dependencies you need for the Google Maps SDK for iOS and Places API for iOS (optional):
```
source 'https://github.com/CocoaPods/Specs.git'
target 'YOUR_APPLICATION_TARGET_NAME_HERE' do
  pod 'GoogleMaps'
  pod 'GooglePlaces'
end
```


- Save the Podfile.
- Open a terminal and go to the directory containing the Podfile:

- cd <path-to-project>
- Run the pod install command. This will install the APIs specified in the Podfile, along with any dependencies they may have.

- pod install
- Close Xcode, and then open (double-click) your project's .xcworkspace file to launch Xcode. From this time onwards, you must use the .xcworkspace file to open the project.
## More Stuff
