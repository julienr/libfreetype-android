===========
libfreetype
===========
This is a repackaging of Android's libfreetype. It basically allows one to build libfreetype as a static library to be linked with an Android NDK application.

Although the Android system includes a version of freetype, it is not part of the standard API and therefore linking against it is kind of risky. This is why I made this small repackaging.

The original sources can be found at :
http://android.git.kernel.org/?p=platform/external/freetype.git;a=summary

Assuming 'ndk-build' is in your path, you can use the build.sh script to create a static library.

