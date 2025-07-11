# Expo Go setup process

- Initialize a new Expo project using;
` npx create-expo-app@latest `

- Edit the title from "Welcome!" to "First App Created!"

- Run `npx expo start` in the project and scan the QR code using the Expo Go app in my Android device.

- After running ` npm run reset-project ` in a new terminal window, the reset worked exactly as intended: 
   1. Moved existing files to /app-example.
   2. A clean /app directory with basic files was created.
   3. My Android device showed the new clean screen and updated live the changes that I made in the app/(tabs)/index.tsx. file.
