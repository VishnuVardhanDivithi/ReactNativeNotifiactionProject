# ReactNativeNotifiactionProject
# PushNotificationApp

A React Native application with Firebase Cloud Messaging (FCM) integration, featuring a Node.js Express backend for push notification management.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- React Native mobile application with push notification support
- Firebase Cloud Messaging (FCM) integration
- Node.js Express backend for notification handling
- Token management and registration
- Cross-platform support (iOS and Android)
- Modern UI with token display and copy functionality

## Prerequisites

### Frontend (React Native)
- Node.js (v14 or higher)
- React Native CLI
- Android Studio (for Android development)
- Xcode (for iOS development)
- Firebase account and project setup

### Backend (Node.js)
- Node.js (v14 or higher)
- npm (Node Package Manager)
- Firebase Admin SDK credentials

## Installation

### Frontend Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd PushNotificationApp
```

2. Install dependencies:
```bash
npm install
```

3. Configure Firebase:
- Create a Firebase project
- Download the configuration file
- Place the configuration file in the appropriate directory

4. Run the app:
```bash
# For Android
npx react-native run-android

# For iOS
npx react-native run-ios
```

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables:
Create a `.env` file in the backend directory with the following variables:
```
PORT=3000
FIREBASE_SERVICE_ACCOUNT={your_service_account_json}
```

4. Start the server:
```bash
npm start
```

## Usage

### Frontend
The app provides a simple interface to:
- Display the FCM token
- Copy the token to clipboard
- Test notifications
- Navigate between screens using React Navigation

### Backend
The backend server provides endpoints for:
- Registering FCM tokens
- Sending notifications
- Health check
- Token management

## Configuration

### Firebase Setup
1. Create a Firebase project
2. Enable Cloud Messaging API
3. Generate service account credentials
4. Configure the credentials in the backend `.env` file

### Environment Variables
- `PORT`: Backend server port (default: 3000)
- `FIREBASE_SERVICE_ACCOUNT`: Firebase Admin SDK credentials

## Project Structure

```
PushNotificationApp/
├── android/              # Android platform files
├── ios/                 # iOS platform files
├── backend/             # Node.js backend server
│   ├── src/            # Backend source code
│   └── package.json    # Backend dependencies
├── src/                # React Native source code
├── App.tsx             # Main application file
└── package.json        # Frontend dependencies
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Step 3: Modify your app

Now that you have successfully run the app, let's make changes!

Open `App.tsx` in your text editor of choice and make some changes. When you save, your app will automatically update and reflect these changes — this is powered by [Fast Refresh](https://reactnative.dev/docs/fast-refresh).

When you want to forcefully reload, for example to reset the state of your app, you can perform a full reload:

- **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Dev Menu**, accessed via <kbd>Ctrl</kbd> + <kbd>M</kbd> (Windows/Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (macOS).
- **iOS**: Press <kbd>R</kbd> in iOS Simulator.

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [docs](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you're having issues getting the above steps to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
