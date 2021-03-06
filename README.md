# SpotMenu ![demo](https://github.com/kmikiy/SpotMenu/blob/master/SpotMenu/Assets.xcassets/AppIcon.appiconset/spotmenu%20(5)-1.png)
Spotify in your menu bar

## About

![demo](https://github.com/kmikiy/SpotMenu/blob/master/demo.gif)

SpotMenu is a combination of [TrayPlay](https://github.com/mborgerson/TrayPlay) 
and [Statusfy](https://github.com/paulyoung/Statusfy) written entirely in swift. 

## Notes

+ The default behavior is to only show the SpotMenu icon in the menubar. Right click -> Preferences to customize.    
+ The animated gif currently demonstrates the functionality of version 1.4   

## New Features in Version 1.4.2

+ Customization
  - Open at login

[List of all features](https://github.com/kmikiy/SpotMenu/blob/master/FEATURES.md)

Easy Install
------------

Download the zip file [version 1.4.2](https://github.com/kmikiy/SpotMenu/releases/download/v1.4.2/SpotMenu.zip). Unarchive it. Run SpotMenu.app.
In case of unidentified developer follow these [steps](https://support.apple.com/kb/PH21769?locale=en_US)!

You can find all releases [here](https://github.com/kmikiy/SpotMenu/releases).


How to Build
------------

First, you'll need Xcode 8. You can download this at the [Mac App Store](https://itunes.apple.com/us/app/xcode/id497799835?mt=12).
Second, you'll need [CocoaPods](https://guides.cocoapods.org/using/getting-started.html). 

Now, use [Git](http://git-scm.com/) to clone the repository.

```sh
git clone https://github.com/kmikiy/SpotMenu.git
cd SpotMenu
pod install
```

Finally, open up the SpotMenu.xcworkspace. Set the "Scheme" to build the "SpotMenu" target for "My Mac". Then Product > Run (or the shortcut ⌘R).

Note: 
+ Version 1.2 has been updated to swift 3.0 therefore Xcode 8 is required.
+ In some cases it might be required to select the "Spotify" scheme and build it before selecting "SpotMenu".

Help
----
+ Star and Fork
+ Post any issues you find
+ Post new feature requests
+ [![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=NL4KDG65UYQB6) Help me get that new Tesla Model X 🚗 or a cup of coffee ☕️, anything helps 💸💰💵
