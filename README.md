Minimal Android Project

https://github.com/czak/minimal-android-project

build.gradle:

a line is old:
classpath 'com.android.tools.build:gradle:1.5.0'
for newer as seen on: https://stackoverflow.com/questions/52145064/error-minimum-supported-gradle-version-is-4-6-in-android-studio-3-0-1/52145566
as from: https://developer.android.com/studio/releases/gradle-plugin#updating-gradle
1.5.0 plugin is for 2.2.1 - 2.13 gradle

2.1.3 - 2.2.3 for gradle 2.14.1+
and 2.3.0+ for gradle 3.3+
Solus has gradle 3.5
debian on crostini has gradle 3.2

to get google repository as in: https://stackoverflow.com/questions/45781489/error6-0-gradle-dsl-method-not-found-google

this line in repositories:
maven { url 'https://maven.google.com' }

bla bla bla licenses: https://stackoverflow.com/questions/39760172/you-have-not-accepted-the-license-agreements-of-the-following-sdk-components
sdkmanager --licenses
