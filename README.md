# React Native: Handling undefined or null objects
This repository demonstrates a common error in React Native applications: attempting to access properties of an object that is undefined or null.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides a solution using optional chaining and nullish coalescing.

## Problem
Asynchronous operations, like fetching data from an API, can lead to unexpected errors when accessing properties before the data is fully loaded.  This typically results in a `TypeError: Cannot read properties of undefined (reading '...')`.

## Solution
The solution uses optional chaining (`?.`) and the nullish coalescing operator (`??`) to gracefully handle potential null or undefined values.

## How to run
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npx react-native run-android` or `npx react-native run-ios` to start the app.