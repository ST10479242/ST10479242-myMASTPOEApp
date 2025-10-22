# 🧑‍💻 Developer

Author: Aneeq Harris ST10479242
Year: 2025
Framework: Expo (React Native + TypeScript)
Purpose: Mobile App Scripting POE — Part 2

# 🍽️ Chef’s Menu Creator App
A simple and elegant React Native app (built with Expo and TypeScript) that allows a chef to create, view, and manage their restaurant menu dynamically.

---
## Links


---
## 📱 Overview

The **Chef’s Menu Creator** helps chefs quickly add and organize dishes into different courses such as **Starters**, **Mains**, and **Desserts**.  
All data is stored in memory during the app session — no hardcoded values and no permanent storage needed.

This app was created for a coursework task to demonstrate basic React Native component usage, state management, and user interaction.

---

## ✨ Features

### 🧾 Menu Creation
- Add new dishes with:
  - Dish name  
  - Description  
  - Course selection (Starters, Mains, or Dessert)  
  - Price (in Rands)

### 🏠 Home Screen
- Displays all dishes added by the chef.
- Shows the **total number of menu items**.
- Each item card includes the name, course, description, and price.

### ⚙️ Technical Highlights
- Built using **Expo + React Native + TypeScript**.
- Fully responsive and styled for a professional, clean layout.
- Uses **Picker** for dropdown course selection.
- **No data is hardcoded** — items are added dynamically.
- SafeAreaView and KeyboardAvoidingView ensure good UX on both Android and iOS.

---

## 🧑‍🍳 Usage Instructions

### 1. Clone or Create the Project
If starting fresh, create a new Expo app:
npx create-expo-app chef-menu-app -t expo-template-blank-typescript
npm install @react-native-picker/picker

## 🎨 Design Notes

Color palette inspired by rustic restaurant tones (warm browns and creams).

Clean spacing and rounded cards for a friendly, aesthetic appearance.

Layout avoids common FlatList and ScrollView nesting issues for smooth scrolling and dropdowns.


## 📦 Screen Shots

