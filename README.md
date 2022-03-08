# expert-adventure

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Installation

### Add a new file in expert-adventure/src/. which includes your firebase config.

file with name `firebase.config.js` where "" is replaced with the credentials for your firebase project.

```
import { initializeApp } from "firebase/app";
import { getFirestore } from "firebase/firestore";

// Your web app's Firebase configuration
const firebaseConfig = {
apiKey: "",
authDomain: "",
projectId: "",
storageBucket: "",
messagingSenderId: "",
appId: "",
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
export const db = getFirestore()
```

### Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
