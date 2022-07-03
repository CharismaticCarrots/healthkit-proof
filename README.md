# healthkit-proof

Follow these instructions for installing and setting up environment: https://github.com/agencyenterprise/react-native-health/blob/master/docs/Expo.md

### TBD

Still need to determine if these steps are necessary: https://docs.expo.dev/workflow/customizing/

### Notes

Add steps into the Apple Health app from the home screen on the xcode simulator. FYI: you have to hard reload to see new data...

In `Healthkit.js` houses the permissions for using AppleHealthKit through react native health. I also imported the whole file into `index.js`, the root of the app. `Healthkit.js` also houses two additional things: a custom context provider (https://reactjs.org/docs/context.html) and custom hooks for fetching the data from AppleHealthKit. 

The context provider is like the store Provider, and is wrapped around the entire component in `App.js`. 

