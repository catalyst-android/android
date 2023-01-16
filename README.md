# Project Catalyst

Catalyst OS is a minimal custom ROM with focus on sustained performance and creating a great combination of battery life and performance. We are not like 
any other ROM because, we go above and beyond and write original features to achieve our goals. With Catalyst OS you will be experiencing a closely tailored best experience for your device, given that you know what you are doing. 

Getting started
===============

To get started with Android/CatalystOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository using the Catalyst trees, use a command like this:
```
repo init --depth=1 -u https://github.com/catalyst-android/android.git -b 13
```
Then to sync up:
```
repo sync --current-branch --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j `nproc`
```

Building Catalyst
=================

```
  . build/envsetup.sh
  lunch catalyst_<devicecodename>-userdebug
  m bacon -j$(nproc --all)
```

Credits
=======

- [**AOSP**](https://android.googlesource.com)
- [**ArrowOS**](https://github.com/ArrowOS)
- [**LineageOS**](https://github.com/LineageOS)
- [**Superior OS**](https://github.com/SuperiorOS)
- [**crDroid**](https://github.com/crdroid-android)
