# renovate-debug

This repository contains a barebones Gradle/Kotlin project with buildscript locking enabled.

To illustrate the incompatibility with Renovate's current behavior:
1. Bump the version of `spring-boot-gradle-plugin` in line 6 of `build.gradle.kts` to `2.5.6`
2. Run `./gradlew properties`
3. Observe the error.
