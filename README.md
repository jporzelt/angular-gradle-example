# angular-gradle-example
How to wrap an angular app build with gradle

## Create app
set 'appName' in build.gradle then execute

`./gradlew createApp`

## Build app
set 'appName' in build.gradle then execute

`./gradlew build`

1. The distribution is created in appName/dist
2. A war file is created in build/libs

## Run app
set 'appName' in build.gradle then execute

`./gradlew start`

Open your browser on http://localhost:4200/

TODO: starting the app locks the port, workaround: `sudo kill $(sudo lsof -t -i:4200)`