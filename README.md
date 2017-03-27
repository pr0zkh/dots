# dots - game which kept me awake during the long and boring university lessons. For more details please refer to this article: https://en.wikipedia.org/wiki/Dots_(game)

## Frameworks, utilities etc.

### dots-core
* jdk 1.8.x
* gradle 3.4.1
* spring-boot 1.5.2
* spock 1.0 (groovy 2.4)
* junit 4.12

### dots-web
* TBA

## Build, run, maintain

### dots-core
From the root folder execute: **gradlew build** - sources will be compiled and packed to jar file located at *build/libs/* (*build/libs/dots-core-0.1.0.jar* by defualt).
Jar mentioned above is executable jar, in order to run the app execute from the root folder: *java -jar build/libs/dots-core-0.1.0.jar*.
Application will be started at localhost port 8080 (some spring-boot+jetty magic, we'll figure out how it works later).
You can check whether app is running by accessing http://localhost:8080 (greeting message should be displayed by default).

### dots-web
TBA