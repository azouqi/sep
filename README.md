# SEP
COMP 354 Software Engineering Project

## Description

This is the repository for the project code.

## How to run
### From the command line
#### OS X / Linux
 - `cd` to the project root
 - Run `./gradlew`

#### Windows
 - Open the project root in the command prompt
 - Run `gradlew.bat`

### In IntelliJ IDEA
 - Go to File > New > Project From Existing Sources... and select the project folder
 - Import project from external model > Gradle > Next
 - Uncheck 'Create separate model per source set', make sure 'Use default gradle wrapper (recommended) is selected, and Gradle JVM is a Java 8 version, then press 'Finish'
 - Create a new Gradle run configuration using `build.gradle` from the repo root with tasks `clean run`

### In Eclipse
- Install the 'Gradle (STS) Integration for Eclipse' plugin from the Eclipse Marketplace
- Go to File > Import... > Gradle > Gradle Project and select the project folder
- Press 'Build Model', select the `sep` project, and press 'Finish'
- 'Run as...' > 'Gradle (STS) Build' with tasks `clean run`
 

## How to build
### OS X / Linux
 - `cd` to the project root
 - Run `./gradlew build`

### Windows
 - Open the project root in the command prompt
 - Run `gradlew.bat build`

The standalone executable is built for your platform and can be found in `build/distributions`.


(C) 2016 SEPGROUP