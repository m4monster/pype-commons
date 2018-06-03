# Pype Common Utilities
Here's a set of Java APIs to serve common utilities to all our projects. So there's no need to re-write the methods again and again in different projects several times. Currently this set contains following APIs...

- PDF Utilities
- File Utilities
- JSON Utilities

## How to use?
In your top level build.gradle file, add following entries in repositories and dependencies...
```gradle
repositories {
    maven { url "https://jitpack.io" }
}

dependencies {
    compile 'com.github.m4monster.pype-commons:file-utils:v1.1.2'
}
```