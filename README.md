## iOS 11 Photo library read/write Permissions Plugin for Apache Cordova

**Cordova / PhoneGap Plugin Permission Setting for NSPhotoLibraryUsageDescription in iOS 11 by adding a declaration to the Info.plist file**

## Install

#### Latest version from GitHub

```
cordova plugin add https://github.com/pgerlach/cordova-plugin-ios-photolibrary-readwrite-permissions.git --save
```

#### Customising the message prompts

On installation you can customise the prompts shown by setting the following variables on installation.

- PHOTOLIBRARY_USAGE_DESCRIPTION for NSPhotoLibraryUsageDescription (read/write access)

For example:
```
cordova plugin add cordova-plugin-ios-camera-permissions --variable PHOTOLIBRARY_USAGE_DESCRIPTION="your photo library usage message here" --save
```

## Usage

See http://cordobo.com/2269-cordova-plugin-for-nscamerausagedescription-in-ios-10/

For the changes to `plugin.xml` to take effect, you must refresh the `ios.json` file (inside the `/plugin` folder):
```
$ cordova platform rm ios
$ cordova platform add ios
```

## Platforms

Applies to iOS 10/11 only.

## License

[MIT License]
