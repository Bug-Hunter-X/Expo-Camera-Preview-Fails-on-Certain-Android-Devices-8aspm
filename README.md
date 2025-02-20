# Expo Camera Preview Failure on Android

This repository demonstrates a bug where the Expo Camera API fails to display a preview on certain Android devices. The preview remains a black screen, and no errors are logged in the console.  This makes debugging particularly challenging.

## Affected Devices

The bug has been observed on at least two devices:

* Samsung Galaxy S8
* Google Pixel 6

## Steps to Reproduce

1. Clone this repository.
2. Run the app using Expo Go on the affected devices.
3. Observe the camera preview.  It should fail to load and show a black screen.

## Potential Causes

The root cause of the problem might be related to how Expo's Camera API interacts with device-specific camera hardware or drivers.  Further investigation is needed.