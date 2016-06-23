# poi-xalan-bug

* This uses the [Gradle Wrapper](https://docs.gradle.org/current/userguide/gradle_wrapper.html) version 2.14
* Run `gradlew run` on a commandline to create a new businessplan.xml
* The dependencies can be seen in `build.gradle`
* The dependency `'xalan:xalan:2.4.0'` causes any xlsx files to be corrupted, however a newer version (`2.6.0`) seems to work fine
