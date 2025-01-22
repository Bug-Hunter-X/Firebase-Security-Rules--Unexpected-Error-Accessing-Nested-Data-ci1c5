# Firebase Security Rules: Unexpected Error Accessing Nested Data

This repository demonstrates a common yet subtle error encountered when using Firebase Realtime Database and accessing nested data.  The issue stems from improperly configured Firebase security rules that prevent access to specific data points, leading to unexpected errors that might not always provide clear debugging information.

The `bug.js` file shows the problematic code that tries to access nested data without proper authorization. The `bugSolution.js` demonstrates how to correctly set up the security rules and handle potential errors more gracefully.