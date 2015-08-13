# Guardian Project Maven Repo

For all of your open-source secure, private and anonymous Gradle-powered needs!

Please visit our "Code" site to learn more about all the libraries in our CipherKit platform: https://guardianproject.info/code

## Add the Repository to Your Gradle Setup 

Our Maven repository is hosted here on Github at this URL:
https://raw.githubusercontent.com/guardianproject/gpmaven/master

To add it, follow this example below, to add it into your build.gradle file:

``` 
allprojects {
    repositories {
	...
        maven { url "https://raw.githubusercontent.com/guardianproject/gpmaven/master" }
    }
}
```

### NetCipher: https://guardianproject.info/code/netcipher

    compile 'info.guardianproject:netcipher:1.2.0'

### CamCipher: https://guardianproject.info/code/camcipher

    compile 'info.guardianproject:camcipher:2.0.1'

### Android FFMPEG Java Library

    compile 'info.guardianproject:android-ffmpeg-java:1.0.0'
