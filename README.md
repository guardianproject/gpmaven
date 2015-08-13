# Guardian Project Maven Android Repository

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

### Android FFMPEG Java Library

    compile 'info.guardianproject:android-ffmpeg-java:1.0.0'
