# Mobile App Setup with Expo Router

## Objective
Set up your first mobile application using the Expo Router template. Document the scaffolding process and understand the file structure of a React Native application using Expo.

## Instructions

### 1. Navigate to Your Project Directory
Open your terminal and move to your parent project directory:
```sh
cd prodev-mobile-setup
```

### 2. Set Up Your Project
Initialize a new Expo project using the latest Expo Router template:
```sh
npx create-expo-app@latest .
```

### 3. Modify the Home Screen
- Open `app/(tabs)/index.tsx`.
- Locate the default text `Welcome!`.
- Change it to `First App Created`.

### 4. Run and Test Your Application
Start the Expo development server with:
```sh
npx expo start
```
#### For iOS Devices:
- Scan the QR code in the terminal using your phone’s Camera app.

#### For Android Devices:
- Scan the QR code using the Expo Go app.

### 5. Reset the Application
Run the reset command and observe its effects:
```sh
npm run reset-project
```

## Observations from `reset-project`
- This command removes dependencies, clears caches, and resets configurations.
- After running the command, you may need to reinstall dependencies with:
  ```sh
  npm install
  ```
- The project returns to its initial state, requiring reconfiguration of custom changes.

## Summary
This guide covers setting up an Expo Router project, modifying the home screen, running the app, and resetting it when necessary. Happy coding! 🚀

