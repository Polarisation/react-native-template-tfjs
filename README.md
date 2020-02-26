# React Native Template TensorFlow.js

This template will give you a new React Native project with TensorFlow.js installed using a single command. You could install TensorFlow.js yourself following the [TensorFlow.js Platform Adapter for React Native instructions](https://github.com/tensorflow/tfjs/tree/master/tfjs-react-native), but this is a fairly complex process, especially if not using Expo. 

## Usage

Simply run the following command:
```
npx react-native init MyApp --template react-native-template-tfjs
```

This will generate the new project in the `MyApp` directory. In the `MyApp` directory you can then run the app with `react-native run-ios` or `react-native run-android`, so long as you've already [configured your environment](https://reactnative.dev/docs/getting-started.html) for these platforms.

### Not working? Check your `react-native` CLI version

Ensure you are using the latest `react-native` CLI (not the legacy one).

You can uninstall the legacy command with `npm uninstall -g react-native-cli`

You can install the current CLI globally with `npm i -g @react-native-community/cli` or `yarn global add @react-native-community/cli`. It is not required to install it but this will allow you to run the command without `npx`

### License

This project is made available under an [MIT License](./LICENSE) (so you can use & reuse with very few limitations).
