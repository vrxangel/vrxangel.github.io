---
layout: post
title: install Android Studio on Ubuntu
description: Tutorial how to install Android Studio on Ubuntu
summary: How to install Android Studio on Ubuntu?
tags: android, linux
---
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSUpznYh8l_SLyxvrXfKhr7b2ZgkoX4TSwQSA&usqp=CAU)

Here's how you can install Android Studio on Ubuntu:

1. Download the latest version of Android Studio from the official website: https://developer.android.com/studio.
2. Extract the downloaded .zip file to a folder of your choice using the following command in the terminal:
```
unzip ~/Downloads/android-studio-ide-*.zip -d ~/android-studio
```
3. Install the required dependencies by running the following command in the terminal:
```
sudo apt-get update
sudo apt-get install openjdk-8-jdk
```
4. Open the Android Studio directory and run the `bin/studio.sh` script to launch Android Studio:
```
cd ~/android-studio/bin
./studio.sh
```
5. Follow the on-screen instructions to complete the installation process.

That's it! You should now have Android Studio up and running on your Ubuntu machine.
