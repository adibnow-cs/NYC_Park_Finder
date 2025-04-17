# 🌍 What is NYC Park Finder?

NYC Park Finder is a full-stack web app that helps locals and tourists find the perfect park in Manhattan, NYC, based on location, schedule, and preferences. Whether you're looking to relax, exercise, attend events, or escape the noise, NYC Park Finder is your go-to platform.

## 🔍 Key Features

🌲 Smart Park Search: Enter your location, date, and time to find nearby parks.

✅ Amenity Filters: Cafés, accessible toilets, playgrounds, and more.

📊 Real-Time Busyness Prediction: ML-powered SVM model to help avoid crowds.

🎉 Event Explorer: Discover concerts, festivals, conferences, and more.

📂 Save Favourites: Bookmark parks for easy access.

📍 Explore by Activity: Filter by interests like shopping, skiing, or walking.

🗓 Central Park Highlights: View curated upcoming events.

## 💻 Tech Stack

### ⚖️ Frontend

React (with TypeScript)

CSS & Bootstrap

### ⚙️ Backend

Java Spring Boot (Microservices)

Spring Data JPA, Hibernate ORM, MySQL

Spring Security with JWT

### 🤖 Machine Learning

Python Flask API with Support Vector Machine (SVM) model for park busyness prediction

🔐 Privacy & Security

🔒 End-to-end encryption (in transit & at rest)

🛡️ Role-based access control

🧾 Strict privacy policy to protect user data

# 🤝 My Contributions

As the Data Lead, I:

Managed data acquisition, preprocessing, and integration of multiple datasets (weather, foot traffic, event data, and more).

Built and evaluated multiple ML models including Linear Regression, LSTM, and SVMs for real-time park busyness prediction.

Conducted geospatial analysis to align TLC taxi zones with Manhattan parks for more accurate mapping.

Implemented PCA and other dimensionality reduction techniques for better model performance.

Closely collaborated with the Backend and Frontend teams to ensure seamless integration and visualization of predictions.

Wrote the [**NYC Park Finder Individual Report (PDF)**](./docs/NYC_ParkfFinder_Data_report.pdf) titled "Enhancing Urban Well-Being through Predictive Park Recommendations",detailing the problem space, my approach to ML and geospatial challenges, dataset decisions, model evaluations, and lessons learned.

This project significantly improved my understanding of:

Data pipelines and preprocessing

Real-time ML model deployment

Geospatial mapping and park zoning

Team coordination in an agile development setup

# 🚀 Getting Started

To run the project locally:

Clone the repository

Start the backend (Spring Boot microservices)

Run the Flask ML service

Start the frontend React app

Open the app in your browser and begin exploring!



