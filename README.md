# deliveroo

THE DELIVEROO APP CLONE.

The project is a typescript app, developed using expo cli, managed by Sanity Back end.

Set up and dependecies:
1. npx create-react-native-app deliveroo

//set up tailwind
Documentation found at: https://www.nativewind.dev/quick-starts/expo
2. yarn add nativewind                       
   yarn add --dev tailwindcss
npx tailwindcss init  ===> initialise tailwindcss.config

configure tailwind.config.js
  content: ["./App.{js,jsx,ts,tsx}",
    "./<custome-folder>/**/*.{js,jsx,ts,tsx}",
  ],

3. Add page Navigation. : https://reactnavigation.org/docs/hello-react-navigation
 yarn add @react-navigation/native 
 npm install @react-navigation/native-stack
 
 4. configure typescript: https://reactnative.dev/docs/typescript
 npm install -D typescript @types/jest @types/react @types/react-native @types/react-test-renderer @tsconfig/react-native
   
 5. I got an error after this step: ==> Unable to resolve module react-native-screens.
 Solution:
 npm install --save react-native-gesture-handler react-native-reanimated react-native-screens
   
 6. Run expo-start. to run the simulator.


