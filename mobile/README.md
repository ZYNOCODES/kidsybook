# Mobile application

Expo and React Native. Part of [KidsyBook](../README.md).

> **Structure only.** The source code is private. Source files here are intentionally empty so you can see how the project is organized. Commands describe the private codebase.

## Responsibilities

- Child profiles
- Story chat and library
- Account settings

## Screenshots

| Mobile sign in | Mobile sign up |
| --- | --- |
| ![Mobile sign in](../docs/screenshots/mobile-signin.png) | ![Mobile sign up](../docs/screenshots/mobile-signup.png) |

## Main dependencies

`@coreui/coreui`, `@coreui/icons`, `@coreui/react`, `@expo/vector-icons`, `@react-native-async-storage/async-storage`, `@react-native-community/datetimepicker`, `@react-navigation/bottom-tabs`, `@react-navigation/native`, `@tanstack/react-query`, `axios`, `events`, `expo`, `expo-blur`, `expo-constants`, `expo-document-picker`, `expo-file-system`, `expo-font`, `expo-haptics`, `expo-image-picker`, `expo-linear-gradient`, `expo-linking`, `expo-router`, `expo-sharing`, `expo-splash-screen`, `expo-status-bar`, `expo-symbols`, `expo-system-ui`, `expo-updates`, `expo-web-browser`, `heroicons`, `lucide-react`, `lucide-react-native`, `nativewind`, `react`, `react-dom`, `react-native`, `react-native-gesture-handler`, `react-native-heroicons`, `react-native-reanimated`, `react-native-safe-area-context`, `react-native-screens`, `react-native-svg`, `react-native-web`, `react-native-webview`, `react-native-worklets`, `socket.io-client`, `tailwindcss`

## Structure

```text
app/(tabs)/                       3 files
app/CreateChild/                  1 file
app/ForgotPassword/               1 file
app/ResetPassword/                1 file
app/Settings/                     1 file
app/SignIn/                       1 file
app/SignUp/                       1 file
app/StoryChat/                    1 file
app/VerifyEmail/                  1 file
app/                              2 files
app/components/                   1 file
app/contexts/                     2 files
app/hooks/                        8 files
app/services/                     6 files
assets/                           31 files
constants/                        1 file
```

## Commands

```bash
npm install
npm start
npm test
npm run lint
npm run web
npm run android
```
