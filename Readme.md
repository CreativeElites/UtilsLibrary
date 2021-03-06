# Android Utils Library (Java And Kotlin)
This is the library I have developed as Utility functions in Java, and started as Mix and match of Utility functions + Extension functions in Kotlin. Traditionally develoed in Java, now entirely being developed in Kotlin.

## Features
### Kotlin
- Originally started as fork of [Kaffiene](https://github.com/ragunathjawahar/kaffeine) thus inheriting it's code and updating as kotlin evolves.
- Also taken some code and inspiration from [Anko](https://github.com/Kotlin/anko). 

    
- Bundles: Putting data with Pair, Extracting the bundle for debug
- Context: All functions from Java library, added accessing resources (Compat version) and system service (With cast) as extension function 
- Drawables: Applying tinting as Extension functions
= Some extension functions for fragments
= Intent: Having refied extension functions for creating intents and accessing default intents.
- Preference: Higher order function to write preferences.


And a [lot more](http://prashamtrivedi.github.io/UtilsLibrary/kutils/index.html)....

## How to use
- Maven Repository (JitPack will always be available, JCenter is available from 0.5).

- Gradle credentials 

```goovy
    implementation 'com.creativeelites:kutils:{latest_version}@aar'
```
    
For latest version see below.
    
## Latest Version
0.8

View [Changelog](changelog.md)

## Future Upgrades 
There are lot to be done in this area, version 0.5 is just starting of these things.

My plans for improvements are
- [x] Update documentations.
- [x] Use kotlin capability at its full. Some methods can be improved.
- [x] Use typealiases
- [x] Use kutils in Java, and retire devUtils forever.
- [ ] New extension libraries for Design Support libraries
- [ ] Android Architecture components support.


All these are being planned for version 1.0. Thanks