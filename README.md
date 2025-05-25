Food Journal App

A mobile application built with React Native that allows users to visually and descriptively document their daily meals. Users can capture or select meal photos, add descriptions, categorize entries (Breakfast, Lunch, Dinner, Snacks), and manage their food journals with editing, filtering, and swipe-to-delete features.
Features

    Add Food Journals: Take a photo with the camera or select one from the gallery, add a description, and categorize your meal.

    Edit & Delete Entries: Update or remove journal entries with intuitive swipe actions.

    Category Filtering: View all entries or filter by meal category.

    Local Storage: All data is stored locally using SQLite for privacy and offline access.

    User Authentication: Each user’s journals are kept separate.

    Modern UI: Clean, user-friendly interface with responsive design.

Screenshots

(Add your app screenshots here)
Installation

    Clone the repository:

bash
git clone https://github.com/yourusername/food-journal-app.git
cd food-journal-app

Install dependencies:

bash
npm install
# or
yarn install

Install required Expo modules:

bash
npx expo install expo-camera expo-media-library expo-image-picker
npm install react-native-swipe-list-view @react-native-picker/picker

Run the app:

    bash
    npx expo start

Usage

    Add Entry: Tap "Take Photo" or "Choose from Gallery", enter a description, select a category, and save.

    Edit Entry: Swipe left on a journal entry and tap "Edit".

    Delete Entry: Swipe left and tap "Delete".

    Filter: Use the category picker to filter journal entries.

Project Structure

text
/components
  /database
    database.js
/screens
  homeScreen.js
  JournalsScreen.js
/App.js

Dependencies

    React Native

    Expo Camera

    Expo Image Picker

    Expo Media Library

    react-native-swipe-list-view

    @react-native-picker/picker

    SQLite

