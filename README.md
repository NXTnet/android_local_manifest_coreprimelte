Repositories that are needed to build CyanogenMod 12.1

How to build:
-------------

Initialize repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-12.1
    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/NXTnet/android_local_manifest/cm-12.1/local_manifest
    repo sync

Compile:

    .build/envsetup.sh
    brunch
