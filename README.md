# Intro

Welcome to my short github course on how to hack Android APK'S. I'll share tips and code on how to hack APK's like a pro.

Firstly what is an APK? APK stands for Android Package and includes all the code that is used for the app. The offical language for android development is java and all apks are built using java

In this short course ill teach you how to hook functions, analyze HTTP/HTTPS requests, and much more.

# Requirements

- Some prior knowledge of Java
- Burp Suite experience
- Javascript knowledge (for scripting)

# Setting Up Your Enviroment

Firstly You're going to need an Android Emulator. This emulator is going to be our host machine that has all the APK's we would like to analyze.

Here are some emulators i recommend:

- Genymotion (Best one from my experience)
- Memu

Once you have an Emulator of your choice we will cover how to set up FRIDA which is a toolkit that allows us to reverse and analyze APK's!

# Frida

Frida is a very useful toolkit. Frida helps out with reversing apks, security research, and development.

I will not precisely go over how to set up frida but here is their github page: https://github.com/frida

Here is the frida docs on getting started with frida: https://frida.re/docs/android/

Some tips on getting setup:

- Downloading Fridas ARM translator (helps run APK's that are made for the ARM architecture)
- Making sure your emulator is rooted
- Downloading ADB

Now if you have everything set up we can continue on your first part of reversing APK's

# Burp Suite

Burp Suite is a tool that helps us analyze HTTP requests.

Firstly to get your Emulator compatible with Burp suite you will need to install the Burp Suite certificate and encrypt your emulator.

Follow the linked guide to getting started: https://portswigger.net/burp/documentation/desktop/mobile/config-android-device

