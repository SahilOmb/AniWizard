# AniWizard

🍿 AniWizard is a full-stack web application for movie and anime enthusiasts to discover, rate, review, and track their favorite media. Built with Java Spring Boot, React, and MongoDB, it leverages external APIs to sync real-time entertainment metadata. 🎬 ✨

🚀 Key Features

• Unified Tracker: Manage personal "Watchlists", "Completed", and "Plan to Watch" logs for both movies and anime.
• Ratings & Reviews: Submit text reviews and score series with community-facing rating systems.
• Smart Search: Filter global content catalogs by genre, studio, release year, or average score.
• Polymorphic Data: Utilizes MongoDB to store diverse data points native to both Western film and Japanese anime.

🛠️ Tech Stack & Integrations

• Frontend: React.js, Tailwind CSS, Axios (Responsive, single-page UI architecture)
• Backend: Java, Spring Boot, Spring Security (Secure, modular RESTful APIs)
• Database: MongoDB, Spring Data MongoDB (High-performance NoSQL document storage)
• APIs: External Media Integrations (Real-time cast data, poster art, and schedules)


⚡ Quick Start


1. Backend Setup

1. Add your credentials to backend/src/main/resources/application.properties:properties
spring.data.mongodb.uri=your_mongodb_connection_string
media.api.key=your_api_key
Use code with caution.
2. Run the server:bash
./mvnw spring-boot:run
Use code with caution.

2. Frontend Setup

1. Install dependencies and start the client:bash
cd frontend
npm install
npm start
Use code with caution.
The application will run locally at http://localhost:3000.
