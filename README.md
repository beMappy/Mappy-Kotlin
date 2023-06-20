# Mappy Android SDK
[![Maven Central](https://img.shields.io/maven-central/v/io.github.bemappy/mappy.svg?label=Latest%20Version)](https://search.maven.org/artifact/io.github.bemappy/mappy)

Mappy Android SDK provide an elegant and composable interface for mapping, geocoding, and routing for Android applications.

The Mappy SDKs leverages the power of best in class technology, including ESRI using the ArcGIS Runtime SDKs as dependencies.

## Installation

Make sure you have the maven repositories added in your project-level build.gradle file:

```groovy
 repositories {
        mavenCentral()
        mavenLocal() // To use the local maven release. Optional
        maven {
            url 'https://esri.jfrog.io/artifactory/arcgis'
        }
    }
```

To use Mappy SDK in your Android project, include the following dependency in your app's `build.gradle` file:

```groovy
implementation 'io.github.bemappy:mappy:0.10.10'
```

For detailed technical documentation and API reference, please visit [Mappy SDK Technical Documentation](https://bemappy.github.io/Mappy-Kotlin/).
