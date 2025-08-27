# First Mobile App with Expo Router

## Steps Followed for Scaffolding

I navigated to the project directory using `cd prodev-mobile-setup`, initialized a new Expo project with `npx create-expo-app@latest .`, and then modified the home screen by opening `app/(tabs)/index.tsx` and changing the text from `Welcome!` to `** First App Created**`. After that, I started the development server with `npx expo start`, scanned the QR code using the Camera app on iOS or the Expo Go app on Android to view the app, and finally ran `npm run reset-project` to reset the application.

---

## Observations from `reset-project` Command

When I ran the reset command, it cleared the cached files, removed and reinstalled `node_modules` and the `.expo` cache, and restored the project to a fresh state similar to just after scaffolding. This ensures a clean environment and helps resolve dependency or cache-related issues.
