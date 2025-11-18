## React Native Config v1.6.0 Bug Reproduction Project

#### This project demonstrates a reproducible issue in react-native-config v1.6.0.

#### Steps to Reproduce
```
# 1. Create a new React Native project
> npx @react-native-community/cli@latest init YourPackageName

# 2. Install react-native-config and complete the setup

> yarn add react-native-config
# (Follow the official setup guide for both iOS and Android)

# 3. Create a .env file and launch the app

# 4. Observe: The Android app crashes
When react-native-config is removed, the error disappears.
```

#### Error
```
TypeError: Cannot read property 'getConfig' of null
```