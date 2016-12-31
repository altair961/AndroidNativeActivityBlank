# AndroidNativeActivityBlank
Blank Android project with native activity and Ant building  

This is a blank Android project with Native Activity

If you do not have build.xml file in the root directory of the project
you need first generate it:

android update project --path .

That will generate build.xml file that is required for building with ant
Then we need to run:

ant debug

Next we have to change to directory with newly generated apk file like so:

cd /native-activity-example/bin/

Then execute following command in order to install it to the device:

adb install NativeActivity-debug.apk

