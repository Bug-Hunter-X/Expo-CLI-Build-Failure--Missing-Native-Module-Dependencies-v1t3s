# Expo CLI Build Failure: Missing Native Module Dependencies

This repository demonstrates a common issue when using Expo CLI and integrating native modules. The `expoBug.js` file shows the code that triggers the issue. The `expoBugSolution.js` demonstrates how to resolve it.

## Problem

When you attempt to build an Expo app using a native module that isn't correctly linked or configured, the build process fails.  The error messages can be quite unclear and may require debugging the native module linking process.

## Solution

The solution involves properly linking the native module to your Expo project using the appropriate Expo CLI commands.  Often this includes reinstalling the native modules and ensuring that the native module's configuration files (e.g., Podfile, build.gradle) are correctly set up.