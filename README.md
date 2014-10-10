Screen Filter
=============

Description
-----------

Screen Filter is a Xposed module that put a transparent view on top of the window manager in order to darken the whole screen.

Once activated, the mod adds a toolbox below the header of your expanded status bar where you can easily switch ON or OFF the filter and set its transparency using the seek bar (only if the filter is active).
A settings activity is also available to control the filter and other settings (such as tuning or hiding the toolbox).

Screen Filter is mostly designed to lower you screen's luminosity and allow you to use your device in the dark without killing your eyes, but you can also use it as a screen privacy guard!
Also, on AMOLED screens, reducing the luminosity improves your battery's lifetime!

Compatibility
-------------

Screen Filter has been tested with Android 4.0.3 to 4.4.4 (ICS, JB, KK).
It should work well on any AOSP based ROM, but may also work on some stock ROM.

Come on the [XDA support thread](http://forum.xda-developers.com/xposed/modules/mod-screen-filter-t2893936) for more information!

Installation
------------

1. You need the [Xposed framework](http://forum.xda-developers.com/xposed/xposed-installer-versions-changelog-t2714053) installed and working
1. Find and install Screen Filter in the *Download* tab of Xposed Installer
	* Alternatively you can download it from the [Xposed repository](http://repo.xposed.info/module/com.tonymanou.screenfilter)
1. Enable Screen Filter in Xposed Installer's *Modules* tab
1. Reboot your device

Translations
------------

Current:

1. Spanish (es)
1. French (fr)
1. Turkish (tr)
1. Japanese (ja)
1. Dutch (nl)

You are welcome if you want to add a new translation or update an existing one.

* First, get the english strings from *[strings.xml](https://github.com/tonymanou/ScreenFilter/blob/translations/res/values/strings.xml)* and translate them
* Do not translate lines with **translatable="false"**!
* Put the translated strings in ```res/values-xx/strings.xml``` (replace 'xx' with your locale code, create the folder if it does not exist)
* Create a pull request with your changes

Source code
-----------

The entire source tree of Screen Filter will soon be available, I just need to clean it out a bit and pick a suitable license before...
