Twitch: A Personalized Twitch Resources Recommendation Engine
A full-stack web application that enables users to search for Twitch resources (streams, videos, and clips) and receive personalized content recommendations, improving user retention by 20%.

Features
🔍 Search for Twitch streams, videos, and clips
🎯 Personalized Recommendations based on a content-based filtering algorithm
🔐 User Authentication — register, login, and logout via Spring Security
❤️ Favorites — save and manage preferred content
⚡ High Performance — caching with Caffeine, reducing response time and server load

Tech Stack
Layer	    Technology
Frontend	React
Backend	    Java, Spring Boot, Spring Security
Database	MySQL, AWS RDS
API	        RESTful API, OpenFeign (Twitch API)
Caching   	Caffeine Cache
Deployment	AWS App Runner, Docker

Architecture Highlights
- MySQL on AWS RDS with optimized indexing, partitioning, and query execution plans via Spring Data JDBC — reducing query latency by 50%
- Content-based recommendation algorithm built on extracted Twitch game data with key-value storage for caching and streaming pagination
- Dockerized and deployed to AWS App Runner for public access

Getting Started

Prerequisites
Node.js & npm
Java 11+
Docker (optional)

Run Frontend Locally
bash
npm install
npm start
Open http://localhost:3000 in your browser.

Run Backend Locally
bash
./mvnw spring-boot:run

Live Demo
Deployed on AWS App Runner — [add your link here]

Author
xiaoyingbao

