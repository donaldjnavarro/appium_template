# Appium Template

A basic Appium framework for quick set up of test automation.

## Setup

### System prerequisites

#### Environmental Variables

1. Install [Android Studio](https://developer.android.com/studio)
2. Add SDK path to environmental variables. Ex: `ANDROID_HOME=C:\Users\{username}\AppData\Local\Android\Sdk`
3. Install [JDK](https://docs.oracle.com/en/java/javase/11/install/overview-jdk-installation.html)
4. Add JAVA path to environmental variables. Ex: `JAVA_HOME=C:\Program Files\Java\jdk-23`

### Configuring Android Studio

* In Preferences > SDK Manager - Install the Android OS version you want
* In Tools > Device Manager - Use "Create Virtual Device" to configure the device you want
* Android Studio will require your BIOS to support virtualization, so if Android Studio fails to launch a virtual device, then you may need to activate virtualization such as SVM

#### Verify Appium Doctor

Run `npx appium-doctor` and address any issues it reports

## Usage

1. Open Android Studio and launch a virtual device
2. Launch appium in a terminal with the command `appium`
3. In another terminal run the test, such as `node example.js`
