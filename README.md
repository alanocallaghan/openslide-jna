# openslide-check

Minimal repo to test OpenSlide with JNA

## Usage

Make sure th


For other platforms, the appropriate native libraries should be used.

To test with a different JDK (e.g. to compare aarch64 and x86_64), create a `gradle.properties` file with (for example)

```
jna.library.path=/path/to/libopenslide.so
org.gradle.java.home=/path/to/JDK/Contents/Home
```
