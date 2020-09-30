# Multiplatform-Mobile-App-Development-with-React-Native
Developing a Mobile Application using React Native

# How to run
Clone the repo, open a terminal and navigate to the cloned repo and do the following : 

1. Install the dependencies

      `npm install`

2. Install the *json-server* globally

      `npm install json-server -g`

3. Run the json-server to start a server on port 3001 

      `json-server --watch db.json --host 0.0.0.0 -p 3001 -d 2000`

Download the Expo App on your device from App Store or Play Store.

   [Download for Android](https://play.google.com/store/apps/details?id=host.exp.exponent) | [Download for iOS](https://apps.apple.com/us/app/expo-client/id982107779)

Open another command window or terminal and start the app (Make sure json-server is running) :

`npm start`

A QR code will appear in the terminal as well as in the browser. Scan it on the Expo app on your mobile device and the app will launch on your device.
