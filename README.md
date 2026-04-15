# Sustainable-Environment-Project
GreenSteps — Sustainable Living Platform

1️⃣ Overview

GreenSteps is a web-based platform designed to encourage sustainable living through community participation. It allows users to discover, share, and engage with eco-friendly practices that can be easily incorporated into daily life. The platform focuses on creating awareness and promoting small habits that collectively lead to a positive environmental impact.

2️⃣ Architecture / Design
The application follows a client-side architecture:

1.Frontend Layer
Built using HTML, CSS, and JavaScript
Handles UI rendering, user interaction, and dynamic updates

2.Database Layer
Uses SQLite (via sql.js) running in the browser
Stores user data, practices, and likes

3.Storage
LocalStorage is used for session management and persistence

4.API Integration
External API is used to fetch real-time weather data

3️⃣ Modules

1. Login / Registration Module
Allows users to create an account and log in
Validates user credentials
Maintains session using LocalStorage

2. Dashboard / Discover Module
Displays all sustainable practices
Shows trending, newest, and most liked practices
Includes filtering and search functionality

3.Share Practice Module
Users can add new sustainability practices
Includes fields like title, category, effort level, tags, and steps
Stores data in SQLite database

4. Like System Module
Users can like/unlike practices
Tracks total likes and updates UI dynamically

5. User Profile Module
Displays user details
Shows number of submissions and likes
Lists user’s shared practices

6. Weather Module
Fetches live weather data
Displays temperature, humidity, and conditions
Suggests eco-friendly tips based on weather

7. UI / Theme Module
Responsive design for all devices
Light/Dark mode toggle
Interactive UI components (cards, dialogs, filters)

4️⃣ APIs Used
Open-Meteo API

Used for fetching real-time weather data
Provides temperature, humidity, wind speed, and weather conditions
No API key required

5️⃣ Challenges Faced

Implementing a database inside the browser using sql.js
Managing user authentication without a backend
Ensuring data persistence using LocalStorage
Designing a responsive and user-friendly UI
Integrating and handling real-time weather API data
Managing state updates for likes, filters, and user sessions

6️⃣ Team Contribution

Hridya
Developed UI design and frontend layout
Implemented theme and responsiveness


Handled database integration (SQLite using sql.js)
Developed authentication system
Member 3
Implemented filtering, search, and like system
Integrated weather API
Member 4
Testing, debugging, and documentation





