# Weight Progress - Android Weight Tracker

Weight Progress is an Android mobile application developed for CS 360 Project Three. The app helps users track weight entries, monitor progress toward a goal, and manage their information through a simple, user-centered interface.

## App Summary

The goal of this app was to create a functional weight tracking application that supports account creation, login, persistent data storage, and weight progress tracking. The app was designed for users who want a straightforward way to record weigh-ins, view their progress, and stay focused on a personal weight goal without a complicated setup.

The main user needs addressed by this app include secure access, easy weight entry, clear progress tracking, editable history, and optional goal alerts. Users can create an account, log in, add weight records, view their current progress, update or delete entries, and log out when finished.

## Features

- Account creation with first name, last name, email, phone number, password, and confirm password fields
- Login and logout functionality
- Password hide and unhide controls
- Input validation for required fields, valid email format, and password confirmation
- Local SQLite database storage
- Salted and hashed password storage using PBKDF2
- Weight entry creation, editing, and deletion
- Weight history grid
- Progress dashboard
- Hamburger menu with navigation and app actions
- Optional SMS goal alert when permission is granted
- Responsive layouts designed to fit different Android screen sizes

## User-Centered UI Design

The app required several screens to support user needs, including a login screen, create account screen, dashboard, add weight entry screen, history screen, and menu/logout options. These screens were designed to keep the user's workflow simple: sign in, view progress, add or update records, and return to the main dashboard.

The UI designs kept users in mind by using clear labels, readable text, consistent button styling, and logical navigation. Password visibility controls were added so users could check their input when needed, and validation messages help prevent errors before data is saved. The designs were successful because they focused on completing the user's main tasks with minimal confusion.

## Development Approach

I approached development by building the app in stages. I started with the core screens and navigation, then added database functionality, account handling, validation, and user interface improvements. Breaking the work into smaller parts made it easier to test each feature before moving on to the next one.

Some of the main strategies I used were incremental development, manual testing after each major change, and keeping the design focused on the assignment requirements. These strategies can be applied in future projects by planning the app around user needs first, then building and testing one feature at a time.

## Testing

Testing was important because it confirmed that the app worked as expected and helped reveal issues that were not obvious during coding. I tested login, account creation, password validation, password visibility, weight entry management, database persistence, navigation, logout, and screen layout behavior.

This process revealed the importance of testing both functionality and usability. An app can compile successfully but still need improvements to layout, button behavior, validation, or navigation. Testing helped make sure the app was not only working, but also easier for users to understand.

## Challenges and Innovation

One challenge was making the app feel complete rather than just meeting the minimum technical requirements. I had to think through how the user would move between screens, how account creation should work, how to protect password data, and how to make the interface fit different screen sizes.

I also had to improve the UI based on how the app looked during testing. This included making screens use the available display space better, improving button names, adding password hide/unhide controls, replacing the launch icon, and adding a menu with useful actions such as logout. These improvements helped turn the app into a more polished and user-friendly product.

## Area of Success

I was particularly successful in connecting the user interface with real app functionality. The app includes working screens, persistent SQLite storage, account handling, password security, validation, and progress tracking. This demonstrated my ability to combine design, Java programming, database management, and testing into one complete Android application.

## Technologies Used

- Java
- Android Studio
- Android SDK
- SQLite
- Gradle

## Project Status

This project was completed as an academic Android application for CS 360. Future improvements could include cloud backup, enhanced charts, additional reminder options, and preparation for a public Google Play release.
