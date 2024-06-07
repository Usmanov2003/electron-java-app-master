Electron+Java Demo
Java Desktop Application with HTML 5 UI based on Electron and Vaadin.

Uses
Node JS
Electron
Gradle
JDK 11
Jetty HTTP Server
Vaadin 14
Features
Easy building with Gradle
Jetty server with Web Sockets enabled
Vaadin UI code in plain Java
Bi-directional WebSocket connection with Vaadin Push and Jetty WebSocket module
Two way communication between Electron and web application using javascript functions
Auto start / stop of server side on application init / exit
Custom window header
Menu option to show developer tools only when running in debug mode
Want to know how to implement all the features? See complete tutorial: https://github.com/cuba-labs/java-electron-tutorial !

Try it!
Preparations
Run debug version:

}> gradlew runApp
Building standalone app
}> gradlew bundleApp
Application will be bundled to build/bundle

Run in production mode
}> gradlew runApp -Pvaadin.productionMode
Or

}> gradlew bundleApp -Pvaadin.productionMode
