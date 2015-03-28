CarbonXtremeROM 9.2-Plus
===========

Getting Started
---------------

To get started with Android for ARMv6/CyanogenMod/Team CarbonXtreme, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/developing.html).


To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/TeamCarbonXtreme/carbonx.git -b cxr-ics

Then to sync up:

    repo sync

Build your device:

    ./build-cxr.sh (Device Codename)

Flash ZIP:

    out/target/product/DEVICENAME/CXR-VERSION-(Without Device Name).zip


Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) for building instructions.

