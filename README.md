# 🎬 Film Recommendation System

This is a backend-based **Film Recommendation System** developed using **Flask**, **MySQL**, and **JWT-based authentication**. The system enables personalized movie suggestions, user profile management, rating/review functionality, and supports complex movie filtering.

## 🚀 Features
- User registration, login, and profile management  
- Add, edit, delete movies and genres (admin-only for some actions)  
- Rate and review movies  
- View watch history  
- Receive movie recommendations based on preferences and history  
- Filter and search movies using complex criteria  
- Swagger UI for API documentation  

## 🧠 Tech Stack
- **Backend**: Flask (RESTful API)  
- **Database**: MySQL  
- **Authentication**: JWT (JSON Web Token)  
- **Documentation**: Swagger (Flasgger)  

## 🗂️ Database Design
Includes the following tables:  
- `user`, `movie`, `genre`  
- Associative entities: `movie_genre`, `rating`, `review`, `watch_history`, `recommendation`  

All tables follow normalized schema with primary/foreign keys to ensure integrity and performance.

## ⚙️ Challenges & Solutions
- ✅ Robust DB design: Normalized schema with strong relations  
- ✅ Many-to-many: Solved with `movie_genre` join table  
- ✅ Auth: Secure JWT-based system  
- ✅ Query performance: Indexed tables, optimized joins  
