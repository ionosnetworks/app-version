# app-version

This repository hosts a simple JSON file (`app-version.json`) that contains the latest version numbers for iOS and Android builds of the mobile app.

## Purpose

Used by the mobile app to check for updates. If the installed version is older than the one listed here, the app can prompt users to update from the App Store or Google Play.

The app fetches this JSON from GitHub Pages:
https://ionosnetworks.github.io/app-version/app-version.json

## Usage Notes

This repo must remain public for GitHub Pages to serve the JSON file.

The version numbers needs to be updated manually whenever a new app build is published to the App Store or Play Store.
