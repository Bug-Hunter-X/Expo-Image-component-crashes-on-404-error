# Expo Image Component 404 Error

This repository demonstrates a bug in the Expo `Image` component where a 404 error from a remote image URI causes the application to crash.  The expected behavior is for the component to gracefully handle the error and display a placeholder image or log an error message.

## Bug Description
When an `Image` component is provided with a remote image URI that returns a 404 error, the application crashes instead of displaying a placeholder or handling the error in a more robust way.  This inconsistency makes the application unstable and negatively impacts the user experience.

## Solution
The provided solution demonstrates how to implement error handling for the `Image` component, ensuring that a placeholder image is displayed if the image fails to load. This improves application stability and provides a more user-friendly experience.

## Setup
1. Clone this repository.
2. Navigate to the directory.
3. Run `expo start`.