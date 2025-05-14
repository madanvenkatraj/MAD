# MAD

# Movie Rating Application

This project is a Movie Rating Application that allows users to browse movies, rate them, and submit reviews. It is designed to demonstrate full-stack development concepts including frontend design, backend integration, user authentication, and database operations.

## Project Overview

The Movie Rating Application enables users to:
- Register and log in to their account
- View a list of movies with details like title, description, and posters
- Rate movies on a scale (e.g., 1 to 5 stars)
- Submit and read user reviews
- View average movie ratings

This project was developed for academic and learning purposes.

---

## Technologies Used

Depending on your platform, you can modify this section. Here's a sample stack:

### Mobile Version (Flutter)
- **Frontend:** Flutter (Dart)
- **Backend:** Firebase Firestore
- **Authentication:** Firebase Auth
- **Media Storage:** Firebase Storage

### Web Version (MERN)
- **Frontend:** React.js
- **Backend:** Node.js + Express.js
- **Database:** MongoDB
- **Authentication:** JWT + Bcrypt

---

## Features

- User registration and authentication
- List of movies with poster images
- Movie detail screen with ratings and reviews
- Real-time average rating display
- Add/edit/delete reviews (per user)
- Responsive UI

---

## Installation

### Prerequisites

- Flutter SDK or Node.js (based on your stack)
- Firebase or MongoDB setup
- Code editor (VS Code or Android Studio)

### Setup Steps

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/movie-rating-application.git
cd movie-rating-application

2. Install dependencies



For Flutter:

flutter pub get

For Node.js (if applicable):

npm install

3. Configure Firebase/MongoDB



Add google-services.json or .env file depending on backend

Make sure Firestore/Database is connected


4. Run the app



flutter run

or

npm start


---

Folder Structure (Example for Flutter)

lib/
├── models/
├── screens/
├── services/
├── widgets/
└── main.dart

