# AndroidNativeActivityBlank
Blank Android project with native activity and Ant building  

This is a blank Android project with Native Activity

in order to build it you need first being in the root directory of the
project run:

android update project --path .

That will generate build.xml file that is required for building with ant
Then we need to run:

ant debug

Next we have to change to directory with newly generated apk file like so:

cd /native-activity-example/bin/

Then execute following command in order to install it to the device:

adb install NativeActivity-debug.apk

