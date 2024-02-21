# EcoSentry_Cloud_Function

The main highlight of this package is a feature that improves the process of automatically exporting function triggers in Firebase Cloud Functions. The Cloud function is designed to receive real-time data sent from IoT devices in the form of HTTP requests, and then transmit the data for storage on the Firestore system.

## Installation

Simply install from npm

```bash
  npm install -g firebase-tools
```

Run the following command to log in via the browser and authenticate the Firebase tool:

```bash
  firebase login
```

Run the following command to set up Firebase functions for your project:

```bash
  firebase init functions
```

To deploy functions, use the following command:

```bash
  firebase deploy --only functions
```
