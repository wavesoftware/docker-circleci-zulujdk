CircleCI docker image with Azul JDK
===================================

This Docker image contains Azul JDK in all published versions as well as CircleCI customizations so that this image can easily be used to build on CircleCI service.

To use this image on CircleCI service simple use:

```yml
image: azul/zulu-openjdk:11
```

You can use any of tags for this image to use in CircleCI builds.

This image contains Java build tools:

 * Maven
 * Ant
 * Gradle
 * SBT
