---
layout: post
title: install Android Studio on CentOS 7
description: Tutorial how to install Android Studio on CentOS 7
summary: How to install Android Studio on CentOS 7?
tags: android, linux
---
![](https://wpcademy.com/wp-content/uploads/2019/05/Android-Studio-on-CentOS-7.jpg)

To install Android Studio on CentOS 7, you can follow these steps:

1. Install Java Development Kit (JDK) by running the following command:
```
sudo yum install java-1.8.0-openjdk-devel
```

2. Download the latest version of Android Studio from the official website: https://developer.android.com/studio.

3. Extract the downloaded file using the following command:
```
tar -xf android-studio-ide-*.tar.gz
```

4. Move the extracted folder to /opt directory:
```
sudo mv android-studio /opt/
```

5. Create a symlink to make it easier to run Android Studio:
```
sudo ln -s /opt/android-studio/bin/studio.sh /usr/local/bin/android-studio
```

6. Start Android Studio by running the following command:
```
android-studio
```

That's it! You have successfully installed Android Studio on CentOS 7.
