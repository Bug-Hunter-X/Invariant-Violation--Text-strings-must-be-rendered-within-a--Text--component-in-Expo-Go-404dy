# Invariant Violation: Text strings must be rendered within a <Text> component in Expo Go

This repository demonstrates a common error encountered when developing React Native applications using Expo:  'Invariant Violation: Text strings must be rendered within a <Text> component.'

The error arises from attempting to directly render text strings in JSX without enclosing them within a `<Text>` component. This repository provides a minimal reproducible example of the error and a solution to fix it.

## Setup

1. Clone the repository.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install the necessary dependencies.
4. Run `expo start` to start the development server.

## Bug Report

The `bug.js` file contains code that will reproduce the error.  The error occurs when the application attempts to display a string directly without a `<Text>` component wrapper.

## Solution

The `bugSolution.js` file demonstrates the corrected code. Wrapping the text string within a `<Text>` component resolves the error.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open a pull request.