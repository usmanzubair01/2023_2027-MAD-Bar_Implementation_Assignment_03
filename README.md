# Android Bar Implementation

| Field          | Details                        |
|----------------|--------------------------------|
| **Name**       | Muhammad Usman                 |
| **Class**      | BSCS 5th Sem (2023-2027)       |
| **Roll no**    | 100045                         | 
| **Assignment03** | Android Bar Implementation |
---

## 1. Introduction

This assignment demonstrates the implementation of different types of app bars in Android using Java and XML.
The main goal is to understand the difference between Action Bar, Toolbar, and Custom Toolbar, and how each one is used in Android applications.

## 2. Objectives

The objectives of this assignment are:

To understand the default Action Bar in Android

To implement a Toolbar as an alternative to the Action Bar

To design and implement a fully customized Toolbar

To use Java for logic and XML for UI design

To manage multiple activities in a single Android project

## 3. Tools and Technologies Used

Android Studio

Java Programming Language

XML for Layout Design

Android SDK

## 4. Project Description

The application consists of three different activities, each demonstrating a different type of app bar:

Action Bar Activity

Toolbar Activity

Custom Toolbar Activity

Each activity is implemented separately to clearly show the differences and usage.

## 5. Step-by-Step Implementation
### Step 1: Create a New Android Project

Open Android Studio

Create a new project

Select Empty Activity

Choose Java as the language

Finish project setup

### Step 2: Action Bar Implementation

Activity Name: ActionBarActivity

Use the default Action Bar provided by Android

Display the application title in the Action Bar

Create an options menu using a menu XML file

Add menu items such as "Settings" and "About"

Handle menu item click events in Java

Purpose:
This step demonstrates the use of the default Action Bar without any customization.

### Step 3: Toolbar Implementation

Activity Name: ToolbarActivity

Disable the default Action Bar from the theme

Add a Toolbar widget in the XML layout

Set the Toolbar as the Action Bar using setSupportActionBar()

Display a title on the Toolbar

Enable back navigation (Up button)

Add menu items and handle click events

Purpose:
This step shows how a Toolbar can replace the default Action Bar and provide more flexibility.

### Step 4: Custom Toolbar Implementation

Activity Name: CustomToolbarActivity

Create a separate XML layout for a custom toolbar

Add custom views such as:

ImageView for app logo

TextView for custom title

ImageButton for custom actions

Attach the custom toolbar to the activity

Handle button click actions using Java

Purpose:
This step demonstrates how to fully customize the app bar according to application requirements.

### Step 5: Android Manifest Configuration

Register all three activities in AndroidManifest.xml

Ensure correct activity launching and navigation

## 6. Project Structure

ActionBarActivity.java

ToolbarActivity.java

CustomToolbarActivity.java

activity_action_bar.xml

activity_toolbar.xml

activity_custom_toolbar.xml

custom_toolbar_layout.xml

menu XML files

AndroidManifest.xml

## 7. Output

A working Android application

Three activities demonstrating:

Default Action Bar

Toolbar

Custom Toolbar

Clean UI with proper navigation

Error-free Java and XML code

## 8. Conclusion

This assignment helped in understanding the concept of app bars in Android.
By implementing Action Bar, Toolbar, and Custom Toolbar separately, the differences and use cases of each component became clear.
This knowledge is essential for building professional and user-friendly Android applications.
