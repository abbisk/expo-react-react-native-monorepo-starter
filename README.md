# expo-react-react-native-monorepo-starter
Starter Kit for Monorepo containing react and react native projects.

## Requirements
```
yarn
nodejs (version 12 and above)
lerna
react-native
expo-cli
```

## Installation
```
git@github.com/abbisk/react-monorepo.git <project_folder>
cd <project_folder>
yarn install
```
To start web application
```
lerna --scope=web-app run start
```
I also added quick commands. you can use 
```
yarn web
```

To start Native android app
```
lerna --scope=NativeApp run android 
```
or  quick command
```
yarn android
```

To start Native ios App
```
lerna --scope=NativeApp run ios
```

or  quick command
```
yarn ios
```

To start Expo app

```
lerna --scope=ExpoApp run start
```

or  quick command
```
yarn expo
```
