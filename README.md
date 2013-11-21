facebook-api-android-aar
========================

Facebook Android SDK library built with gradle in aar format for usage with android gradle build system. Versions included: 3.0.2, 3.5.0, 3.5.2

How to use
=======================
Before you can get aar you should checkout [facebook-android-sdk](https://github.com/facebook/facebook-android-sdk) submodule. Overall build process including build is straightforward:
```bash
  $ git submodule update --init
  ...
  $ ./gradlew build
  ...
```

When build is finished aar file will be located in `build/libs`.

Maven artifact in local repo
======================

```bash
  $ ./gradlew build uploadArchives
```

