# ColorIndicator
Google Glass application for picking up colors for driving and giving auditory notice

#Getting Started
#Installing Android Studio
1. Follow the [main tutorial](https://developers.google.com/glass/develop/gdk/quick-start) from Google to install Android Studio and add the GDK through the Android SDK Manager. 
2. Once you add the GDK, restart Android Studio in order to see that the correct SDKs were installed (In my experience, if you try to create a Glass app after installing the GDK, it will still appear grayed out).

#Setting up Git
1. Installing Git for the OS you are on. If using [Windows](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git#Installing-on-Windows), download and install the official build. Use all defaults in the installer. Keep note of where it is installed on your computer.
2. Follow this [tutorial](http://wii.logdown.com/posts/2013/11/15/android-studio-git-tutorial) for setting up Git for Android Studio for windows. Git is already set up for the project, just make sure your Android Studio is set up for Git.

- MAKE SURE you fork this repo and clone your own forked repo. The remote should already be set up.
- Committing and cloning can be done through Android Studio or the git bash.

#adb
ADB allows you to view your connected devices through the terminal.
- Go to your {sdk-path}\platform-tools through cmd and you can use the commands `adb devices`, `adb start-server`, `adb kill-server` to see connected devices, start, and kill the server respectfully.
- (For Windows) If you connect your device (i.e. Nexus 7) and it doesn't show up in ADB, you need to [go to your Device Manager and manually set the USB Driver for the device.](http://stackoverflow.com/a/14830431/4684652)

#Genymotion
If you don't have access to an Android device, I recommend you install [Genymotion free version](https://www.genymotion.com/#!/download) because it is vastly superior and faster than the vanilla Android emulator.