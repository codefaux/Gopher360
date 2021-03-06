PLEASE NOTE
======
```diff
+I (@codefaux) am simply forking this for personal-ish use, but I'm open to reasonable modifications.
+At this time, @Tylemagne is responsible for 99% of the code. I've only done simple tweaks thusfar.
-I CANNOT GUARANTEE THE ACCURACY OF MOST OF THE INFORMATION ON THIS PAGE, ESPECIALLY REGARDING CONFIGURATION. Individual systems vary.
-(Previous author didn't update the documentation to keep up with the application. I'll correct what comes to my attention.)
```

I also have no real need to modify or improve this code. If you're using it and you enjoy it, feel free to provide feedback and/or feature requests via the Issues page.
If I have time, I might look into implementing ideas. My interests swing through a dozen different random things, I may or may not act on it.

Download
======

[![Github All Releases](https://img.shields.io/github/downloads/codefaux/Gopher360/total.svg?style=flat&label=Download%20Gopher360%20Standalone&logo=appveyor&colorA=00cc0a&colorB=000000)](https://github.com/codefaux/Gopher360/releases/download/v0.5.0/Gopher360_v0.5.0.zip)

Donate
======
```diff
- This is @Tylemagne's donation link. codefaux doesn't have one (yet).
```
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ETDWNUEJG2UY2)

Compatible Controllers
======
### Xbox 360
* [Official Wired Xbox 360 Controller for Windows](https://www.amazon.com/Microsoft-Wired-Controller-Windows-Console/dp/B004QRKWLA/)
* [Official Wireless Xbox 360 Controller](https://www.amazon.com/Xbox-360-Wireless-Controller-Glossy-microsoft/dp/B003ZSP0WW/)
* [A compatible wireless adapter](https://www.amazon.com/Microsoft-Xbox-Wireless-Receiver-Windows/dp/B000HZFCT2/) is required to get a standard controller to connect to a Windows PC)

### Xbox One
* [Offical Xbox One Wireless Controller](https://www.amazon.com/Xbox-Wireless-Controller-Black-one/dp/B01LPZM7VI/)
* [A bluetooth adapter/antenna](https://www.amazon.com/Bluetooth-Wireless-Headphone-Controller-Keyboard/dp/B0774NZNGX/) is needed for XBone controller Bluetooth mode. Many laptops and tablets will *already* have this. Read the manual!
* [A wireless adapter](https://www.amazon.com/Microsoft-Xbox-Wireless-Adapter-Windows-one/dp/B00ZB7W4QU/) is needed if you want wireless mode.
* [A decently long MicroUSB cable](https://www.amazon.com/Charger-Durable-Charging-Smartphones-Motorola/dp/B06XZTK2JL/) will be needed for comfortable direct wired mode usage. This is the cheapest option if you already have the controller and no Bluetooth antenna!

### DualShock
DualShock controllers are great, but you NEED to emulate Xinput for Gopher to see and understand them. Fortunately, Xinput emulation is a very popular thing, as there are just as many people with DualShock controllers as there are Xbox controllers. Listings coming soon.

### Third party
SOME third party controllers will most likely work as well. I haven't seen one not work, but I'd imagine some wouldn't. Research before buying, Gopher expects native Xinput devices, so the controller should as well. I won't be listing any for now until I know what ones will work. If I can find one that does the job and saves you from Microsoft's extreme profit margins, I'll list it.


Table of contents
=================

  * [About](#about-gopher)
  * [Default Controls](#default-controls)
  * [Requirements](#requirements)
  * [DualShock Controllers](#using-dualshock-controllers)
  * [Re-binding Controls](#config-file-instructions)
  * [Building](#build-instructions)
  * [License](#license)



About Gopher
======

Gopher is a utility for couch-oriented PC users that wish to entirely control their PC from the couch with a controller. Gopher works by transforming Xbox (or PlayStation, if using DS3Tool) controller input into traditional keyboard and mouse input that many applications and games still completely rely on with no controller-based alternative input options. The analog sticks move the mouse, the buttons click - it's very simple. Gopher completely skips this requirement and brings controller compatibility to ALL your applications and MOST of your games. Games like Runescape will be just fine. Crysis? Maybe not so much. It all depends on what amount of traditional input the game requires. Gopher is an excellent tool for PC gaming from the couch, as it's fully capable of web browsing, playing mouse-based games, controlling media players, and launching emulators. Don't stand up and waste calories, just download Gopher!

Gopher separates itself from the competition by being efficient, small, portable, free, and fully open. If you have something you'd like to see improved, added, or changed, please fill out the survey.

[![Github Releases (by Release)](https://img.shields.io/github/downloads/codefaux/Gopher360/v0.5.0/total.svg)]()

[![GitHub repo size in bytes](https://img.shields.io/github/repo-size/codefaux/Gopher360.svg)]()

[![GitHub last commit](https://img.shields.io/github/last-commit/codefaux/gopher360.svg)]()

[![GitHub top language](https://img.shields.io/github/languages/top/codefaux/gopher360.svg)]()

[![GitHub release](https://img.shields.io/github/release/codefaux/gopher360.svg)]()

[![Github commits (since latest release)](https://img.shields.io/github/commits-since/codefaux/gopher360/latest.svg)]()

Requirements
======
Gopher is incredibly great at being a standalone program, but with one major exception: it absolutely needs Visual C++ 2015 Runtimes to be installed. If you have run Windows Updates at least once in the lifetime of your computer, this really won't be an issue.

Using DualShock Controllers
======
DualShock controllers don't use typical xinput libraries like the X360 and Xbone controllers do, so you'll need something like InputMapper, SCP, DS4Windows, or DS3Tool to "emulate" an xinput device in order to get xinput-using applications like Gopher360 to understand it. Gopher360 DOES NOT automatically offer these emulation layers ( yet ;) ), so you'll need to use something to emulate it before Gopher can understand it.

Video Demonstration
======

https://vine.co/v/MYadBgWXuWY

[![Gopher Video 1](http://img.youtube.com/vi/UWYUodeontM/0.jpg)](https://www.youtube.com/watch?v=UWYUodeontM)

[![Gopher Video 2](http://img.youtube.com/vi/8APmA1ohPdM/0.jpg)](https://www.youtube.com/watch?v=8APmA1ohPdM)


Download Instructions
======
Download the latest release here: https://github.com/codefaux/Gopher360/releases

I recommend that you copy it somewhere outside of the ZIP and make a shortcut to it. Adding it to your startup folder in your HTPC can make bootups a lot more convenient!

Default Controls
======
Gopher360 automatically generates a config file, which will contain documentation information on all input types and key bindings.

**A**: Left Mouse-Click.

**X**: Right Mouse-click.

**Y**: Hide terminal.

**B**: Enter.

**D-pad**: Arrow keys.

**Right Analog**: Scroll up/down.

**Right Analog Click**: F2.

**Left Analog**: Mouse.

**Left Analog Click**: Middle mouse click.

**Back**: Browser refresh

**Start**: Left Windows Key

**Start + Back**: Toggle. Useful for when you launch emulators or open Steam Big Picture mode. Press again to re-enable.

**Start + DPad Up**: Toggle gopher vibration setting.

**LBumper**: Browser previous

**RBumper**: Browser next

**LBumber + RBummper**: Cycle speed (Multiple speeds)

**LTrigger**: Space

**RTrigger**: Backspace

Config file instructions
======
There is a configuration file (config.ini) that can be reconfigured for simple keybindings.

If you literally don't have a config file and in no other condition, Gopher will automatically generate a config file. The previous author (@Tylemagne) did not document all config entries, but I (think that I) have. We'll see.

You can set which controller buttons will activate the configuration events based on the official microsoft keys hexadecimal values.

Virtual Windows Keys:
https://msdn.microsoft.com/en-us/library/windows/desktop/dd375731

XInput Controller Buttons:
https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_gamepad%28v=vs.85%29.aspx

More instruction in the configuration file.


Build Instructions
======
Building is pretty straightforward (Visual Studio Community Edition seems to Just Work(tm) For Me(tm)), but you may get a "missing win32 include" error due to the solution targetting. Simply follow the instructions the error provides (Project -> Retarget solution) to ensure your project has a working link to the libraries it needs. (NOTE: Visual Studio Community 2019 prompts for this step when loading the solution.)

License
======
Gopher free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see http://www.gnu.org/licenses/.

![Controller GIF](https://thumbs.gfycat.com/ElasticUnrulyBighorn-max-1mb.gif)
