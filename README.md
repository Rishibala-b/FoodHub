# FoodHub 

FoodHub is a food‑themed web application that allows users to explore categorized food menus, search for dishes, and add items to a cart. It includes user authentication using Firebase and demonstrates a clean separation of UI, logic, and authentication flow. The project is built using a pure HTML, CSS, and JavaScript stack with Firebase Authentication. No frontend framework is used, making it simple, lightweight, and easy to understand for learning purposes.

# Tech Stack

## Frontend

HTML

CSS 

JavaScript

## Authentication

Firebase Authentication

Email & Password login

Google Sign‑In

## Storage

Browser localStorage (user session & cart data)

## Build / Tools

VS Code

Git & GitHub

# Core Features & Use Cases

## Authentication

User login using Firebase Email/Password

Login using Google Sign‑In

Authenticated user details stored in localStorage

Redirects to FoodHub home page after successful login

## Food Menu Browsing

Categorized food menus such as:

North Indian

Chinese

South Indian and More

Carousel‑based card layout for each category

Clean and responsive UI

## Search

Search bar with dynamic suggestions

Filter food items by name

## Cart Functionality

Add food items to cart

Shared cart state between home page and cart page

# Repository Structure

```
FoodHub/
├── images/                    # All food images, banners, icons used in the project
├── FoodHub.html            # Main landing / home page
├── signin.html             # Login page (Firebase auth)
├── cart.html               # Cart page
├── cart.css                # Cart-specific styles
├── cart.js                 # Cart logic
├── faq.css                 # faq styles
├── faq.html                # faq page
├── FoodHub.css             # Main styles
├── FoodHub.js              # Main logic
├── signin.css              # Login styles
├── signup.html             # Signup page
├── signup.css              # Signup styles

│
├── README.md                   # Project documentation
└── .gitignore

```

# Images & Assets

All images used in the FoodHub project (food item images, banners, icons, and UI graphics) are stored locally inside the images/ folder within the repository. No external image links are used, ensuring the project works fully offline once downloaded.

# Firebase Configuration

Create a Firebase project at https://console.firebase.google.com

Enable Authentication

Email/Password

Google Provider

Copy Firebase config and place it in:

```
// signup.js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "...",
  appId: "..."
};
```

# License

This project is for educational and learning purposes.
