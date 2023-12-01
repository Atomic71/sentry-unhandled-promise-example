# Sentry React Native Issue: Unhandled Promise Rejections

## Overview

This repository demonstrates an issue encountered with Sentry in a React Native application, specifically regarding the handling of unhandled promise rejections. Sentry for React Native promises out-of-the-box functionality to capture unhandled promise rejections, but it appears not to be functioning as expected.

<!--  -->

[Sentry's declaration in regards to unhandled promises](https://docs.sentry.io/platforms/react-native/troubleshooting/#unhandled-promise-rejections)

[Github issue #1](https://github.com/getsentry/sentry-react-native/issues/2268)

[Github issue #2](https://github.com/getsentry/sentry-react-native/issues/1077)

## Issue Description

When unhandled promise rejections occur in the React Native application, Sentry does not seem to capture these errors consistently or at all. This behavior is contrary to Sentry's documentation and expectations for React Native applications.

### Environment

- React Native Version: [Specify version]
- Sentry Version: [Specify version]

## Reproduction of the Issue

This repository contains a minimal React Native setup where this issue can be reproduced.

### Steps to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install` or `yarn`.
3. Run the application on a simulator or physical device.
4. Trigger an unhandled promise rejection using [describe the method or action].
5. Observe the behavior in the Sentry dashboard.

## Expected Behavior

Sentry should capture and report all unhandled promise rejections, as per its documentation for React Native integration.

## Actual Behavior

Unhandled promise rejections are not captured or reported in some or all cases.

## Additional Information

- Link to Sentry documentation/reference: [URL]
- Discussion on similar issues: [URLs to GitHub issues or discussions if available]

## Contributing

This issue needs more insights and potential solutions. If you have experienced a similar issue or have expertise with Sentry and React Native, your contribution would be greatly appreciated. You can contribute by:

- Testing the issue with different versions of React Native or Sentry and sharing your findings.
- Suggesting potential fixes or workarounds.
- Sharing insights or similar experiences in the 'Discussions' section of this repository.

## Contact

Feel free to contact me for any further information or clarification regarding this issue. [Provide contact method or leave blank if not applicable]

## License

[Specify the license if applicable, or state that the repository is not under any specific license]

---

**Note:** This repository and README are intended for collaborative troubleshooting and finding a resolution to the Sentry React Native issue regarding unhandled promise rejections.

This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

> **Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

## Step 3: Modifying your App

Now that you have successfully run the app, let's modify it.

1. Open `App.tsx` in your text editor of choice and edit some lines.
2. For **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Developer Menu** (<kbd>Ctrl</kbd> + <kbd>M</kbd> (on Window and Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (on macOS)) to see your changes!

   For **iOS**: Hit <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> in your iOS Simulator to reload the app and see your changes!

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
