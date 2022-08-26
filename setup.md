# setup

https://github.com/NativeScript/nativescript-app-templates/tree/main/packages/template-blank-svelte

```
ns create my-blank-svelte --template @nativescript/template-blank-svelte
```

## Install native script

https://svelte-native.technology/docs#quick-start

After install ns in global from the link:

```
npm install -g nativescript
ns doctor android
```

## Install java

```
sudo apt-get install openjdk-11-jdk

java --version
javac -- version
```

## Env variables

```
export ANDROID_HOME=/home/trixky/Dev/Android/
export ANDROID_HOME=/home/trixky/Dev/Android/Sdk/
export PATH=$PATH:$ANDROID_HOME/platform-tools
```

## Install a builder < v30

### in sdk manager

Can be install in the sdk manager (click on show detail).

### by the cli

https://dor.ky/android-install-older-version-of-build-tools/

https://developer.android.com/studio/command-line#:~:text=Note%3A%20The%20Android%20SDK%20Command,package%20(located%20in%20tools%20).

```
find /home/ -name "android" | grep tools

/home/trixky/Dev/Android/Sdk/cmdline-tools/latest/bin/sdkmanager --list
/home/trixky/Dev/Android/Sdk/cmdline-tools/latest/bin/sdkmanager --install "build-tools;29.0.3"
```

## physical device

- Activate developer mode
- Put usb mode in PTP on the device
- Activate the debug usm mode
- Authorize the connetion to the pc on the device

Check devices:

```
tns device
```

Then run __ns__ command normally.

## tutorial

https://svelte-native.technology/tutorial#the-goal