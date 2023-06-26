# google-webrtc
Maven repository for google-webrtc library for android os

Fix " Failed to resolve: org.webrtc:google-webrtc " (jcenter library not available)

# Connection
To connect library, you need to add a link to project repository in build.gradle file of project

```gradle
    allprojects {
        repositories {
            ..
            maven { url "https://raw.githubusercontent.com/alexgreench/google-webrtc/master" }
        }
    }
```

Add a dependency for the current version of the library to list of dependencies in build.gradle file of required module

```gradle''
     dependencies {
         ..
         implementation 'org.webrtc:google-webrtc:1.0.30039@aar'
     }
```
