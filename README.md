
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

Sharanya
Developed UI design and frontend layout
Implemented theme and responsiveness

Arya
Handled database integration (SQLite using sql.js)
Developed authentication system

Ankitha
Implemented filtering, search, and like system
Integrated weather API

Hridya
Testing, debugging, and documentation


## Screenshots
## Home Page
<img width="1658" height="733" alt="Screenshot 2026-04-15 202216" src="https://github.com/user-attachments/assets/8c2a8eb9-67ca-47a4-83d1-c7bf8c86f484" />

## Discover Practices Page
<img width="1638" height="909" alt="Screenshot 2026-04-15 202240" src="https://github.com/user-attachments/assets/eed437b8-2a05-496b-8fbe-b77adba0abdf" />

## Login / Register Screen
<img width="550" height="818" alt="Screenshot 2026-04-15 203316" src="https://github.com/user-attachments/assets/5d9b4d85-1159-4c74-888a-d407e184d5c9" />

## Share Practice Form
<img width="1453" height="858" alt="Screenshot 2026-04-15 202835" src="https://github.com/user-attachments/assets/85a92e28-777e-4ce8-8403-283b10e3f810" />

## User Profile
<img width="1490" height="723" alt="Screenshot 2026-04-15 202923" src="https://github.com/user-attachments/assets/2270c418-9087-4b16-8984-b5a8b24e3d8b" />











