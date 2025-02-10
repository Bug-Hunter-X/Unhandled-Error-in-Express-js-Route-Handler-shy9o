# Unhandled Error in Express.js Route Handler

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input.  The `bug.js` file shows a route that attempts to find a user by ID. However, it fails to handle cases where the provided ID is not a number or doesn't correspond to any existing user. This can lead to unexpected behavior or even application crashes.

The `bugSolution.js` file provides a corrected version with comprehensive error handling.  It checks if the ID is a valid number and gracefully handles the case where a user is not found using appropriate HTTP status codes.