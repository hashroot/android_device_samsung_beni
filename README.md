Device configuration for beni GT-S5670
--------------------------------------

Getting Started
---------------

To get started with Android for Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the MoltenMotherBoard trees, use a command like this:

    repo init -u https://github.com/MoltenMotherBoard/platform -b aosp-ics

Then to sync up:

    repo sync 

Build your device:

    source build/envsetup.sh
    lunch full_beni-userdebug
    make -j# otapackage

Flash ZIP:

    out/target/product/beni/full-VERSION-DEVICENAME.zip
