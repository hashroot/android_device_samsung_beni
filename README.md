Device configuration for beni GT-S5670
--------------------------------------

Getting Started
---------------

To get started with Android for ARMv6/CyanogenMod, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u https://github.com/MoltenMotherBoard/platform -b aosp-ics

Then to sync up:

    repo sync 

Build your device:

    source build/envsetup.sh
    brunch beni

Flash ZIP:

    out/target/product/beni/cm-VERSION-DEVICENAME.zip
