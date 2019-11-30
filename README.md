<h1 align="center"> React Native Test App </h1>

## Introduction
_Add info here_

## Getting Started

### Pre-requisites
- [Java JDK 8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Android Studio](https://developer.android.com/studio)
- Android Device

1. [Download and install](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) Java JDK 8 on your system.

2. Add `JAVA_HOME` in your environmental variables with the root folder of your installed JDK.
    - for example: `C:\Program Files\Java\jdk1.8.0_231`

3. [Download and install] Android Studio, and make sure the following are checked:
    - Android SDK
    - Android SDK Platform
    - Android Virtual Device

4. Add `ANDROID_HOME` in your environmental variables with the `Sdk` folder.
    - for example: `C:\Users\<user>\AppData\Local\Android\Sdk`

5. Open Android studio, and to the bottom left of the welcome page `Configure` then `SDK Manager`

6. Check `Android 9.0 (Pie)` and clck OK.

7. Add platform tools to your `PATH`
    - for example: `C:\Users\<user>\AppData\Local\Android\Sdk\platform-tools`

### Running the project
1. [Download](https://nodejs.org/en/) the latest Node version. This is marked as `<version number> Current`. Install it on your machine.

2. _(Optional)_ [Download](https://yarnpkg.com/latest.msi) Yarn. This is a faster package manager than the default `npm` one.

3. Clone the project

    ```
    git clone https://github.com/RinMinase/react-native-test-app.git
    cd react-native-test-app
    ```

4. Connect your Android smartphone and make sure `USB Debugging` is enabled

5. Install the dependencies then run the project

    ```
    npm install
    npm start
    ```

    **Note:** If you have installed Yarn, run these instead:

    ```
    yarn install
    yarn start
    ```

## Built with
* <img width=20 height=20 src="https://facebook.github.io/react-native/img/favicon.ico"> [React Native](https://facebook.github.io/react-native/) - Web Framework
* <img width=20 height=20 src="https://babeljs.io/img/favicon.png"> [Babel ES9 / ES2018 Preset](https://babeljs.io/) - Syntax and compiler
* <img width=20 height=20 src="https://yarnpkg.com/favicon.ico"> [Yarn](https://yarnpkg.com/) - Package Manager