# Kostenko CrossPlatform Assignment – AI Meal Planner

Premium cross-platform React Native application for generating personalized AI meal plans using modern mobile architecture and reusable components.

---

# Project Overview

This project was developed as a Cross-Platform Mobile Development assignment using React Native and Expo.

The application allows users to:

- generate AI-based meal plans;
- define nutrition goals;
- calculate calories and meal duration;
- create shopping lists;
- track grocery completion;
- save meal plans locally;
- reopen previous plans from history.

The app follows a modern mobile UI/UX structure inspired by premium wellness and nutrition applications.

---

# Main Features

## AI Meal Plan Generation

Users can generate personalized meal plans based on:

- budget;
- number of people;
- number of days;
- calorie goals;
- nutrition targets.

---

## Processing Screen

Animated AI processing screen with:

- loading animation;
- animated dots;
- asynchronous API handling;
- automatic navigation flow.

---

## Meal Plan Screen

Displays generated meal plans with reusable meal components and dynamic rendering.

---

## Interactive Shopping List

Users can:

- check purchased products;
- track grocery completion;
- view shopping completion status;
- navigate through shopping flow.

---

## Summary Screen

Dynamic analytics screen displaying:

- estimated budget usage;
- people count;
- days;
- calories;
- nutrition goal;
- progress visualization.

---

## History Persistence

Meal plans are saved locally using AsyncStorage.

Users can:

- reopen previous plans;
- browse history;
- delete saved plans.

---

# Technologies Used

- React Native
- Expo
- JavaScript
- React Navigation
- AsyncStorage
- Fetch API
- Functional Components
- React Hooks

---

# Architecture

The application uses:

- reusable UI components;
- modular folder structure;
- stack navigation;
- route parameters;
- local persistent storage;
- asynchronous API communication.

---

# Screens Included

- Home Screen
- Processing Screen
- Meal Plan Screen
- Shopping Screen
- Summary Screen
- History Screen

---

# Application Flow

```txt
Home
↓
Processing
↓
Meal Plan
↓
Shopping
↓
Summary
↓
History
```

---

# Application Screenshots

## Home Screen

![Home](./screenshots/home.png)

---

## Processing Screen

![Processing](./screenshots/processing.png)

---

## Meal Plan Screen

![Meal Plan](./screenshots/meal-plan.png)

---

## Shopping Screen

![Shopping](./screenshots/shopping.png)

---

## Summary Screen

![Summary](./screenshots/summary.png)

---

## History Screen

![History](./screenshots/history.png)

---

# Installation

## Clone Repository

```bash
git clone https://github.com/yulianakosenko/Kostenko_CrossPlatform_Assignment_AI_Meal_Planner.git
```

---

## Install Dependencies

```bash
npm install
```

---

## Run Application

```bash
npx expo start
```

---

# Assignment Requirements Covered

## Cross-Platform Development

Implemented using React Native and Expo.

---

## Navigation

Implemented with React Navigation and stack navigation architecture.

---

## State Management

Implemented using React Hooks:

- useState
- useEffect
- useRef

---

## Persistent Storage

Implemented using AsyncStorage.

---

## Reusable Components

Application includes reusable:

- buttons;
- cards;
- tab bars;
- headers;
- meal components;
- shopping components.

---

## API Communication

Implemented asynchronous API requests using Fetch API.

---

## UI/UX Design

Implemented responsive premium mobile UI inspired by modern wellness applications.

---

# Project Structure

```txt
src
 ├── components
 ├── screens
 ├── navigation
 ├── constants
 ├── utils
 ├── data
```

---

# Author

Yuliya Kostenko

Cross-Platform Mobile Development Assignment