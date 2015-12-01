Repositories that are needed to build CyanogenMod 12.1 for Samsung Galaxy Core Prime (SM-G360F)

How to build:
-------------

Initialize repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-12.1
    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/NXTnet/android_local_manifest_coreprimelte/cm-12.1/local_manifest.xml
    repo sync

Compile:

    source build/envsetup.sh
    brunch
