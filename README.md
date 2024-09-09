# Flutter Increment App with User Authentication

## Overview

This is a Flutter application that allows users to register, log in, and interact with a simple value incrementing feature. Once logged in, users can increment a value by clicking a button, and the value will be stored in a Firestore database. Each user has their own unique value stored, so when users log in again, they will see the value they last left off with.

## Features

- **User Authentication**: Users can sign up, log in, and log out using Firebase Authentication.
- **Value Persistence**: The incremented value is saved to Firestore and persists between sessions. Each user has their own value.
- **Increment Button**: Users can increment the value using a button. The display updates in real time.
- **Firestore Storage**: User-specific data (such as the incremented value) is stored in Firestore under each user's unique document.

## Technologies Used

- **Flutter**: Cross-platform mobile development framework.
- **Firebase Authentication**: For user sign-up, login, and authentication management.
- **Cloud Firestore**: To store and retrieve user-specific data (increment values).

## Setup Instructions

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) installed.
- A Firebase project set up with **Firebase Authentication** and **Firestore**.
- Firebase configuration file (`google-services.json` for Android or `GoogleService-Info.plist` for iOS) added to your project.
