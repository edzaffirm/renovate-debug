# renovate-debug

This repository contains a barebones Gradle/Kotlin project with buildscript locking enabled.

To illustrate the incompatibility with Renovate's current behavior, simply bump the version of spring-boot-gradle-plugin
to 2.5.6, and run `./gradlew properties`, and observe the error.