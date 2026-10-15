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

# 📂 Project Structure

```text
moviereview/
├── backend/                                   # Spring Boot Core REST API
│   ├── MongoTestRunner.java                   # Database connectivity tester
│   ├── Movie.java                             # Movie schema entity model
│   ├── MovieController.java                   # Endpoints mapping for /api/v1/movies
│   ├── MovieRepository.java                   # MongoDB repository framework interface
│   ├── MoviereviewApplication.java            # Main Spring Boot execution class
│   ├── MovieService.java                      # Service layer processing movies logic
│   ├── ReviewController.java                  # Endpoints mapping for /api/v1/reviews
│   ├── ReviewRepo.java                        # MongoDB repository framework interface
│   ├── ReviewService.java                     # Service layer processing reviews logic
│   └── Reviews.java                           # Review schema entity model
│
├── frontend/                                  # React Dynamic Web UI Client
│   ├── App.js                                 # Main client component router engine
│   ├── App.css                                # Primary custom layouts styling rule
│   ├── index.js                               # Root DOM injection rendering point
│   ├── index.css                              # Global CSS standard rule variables
│   └── logo.svg                               # Interface branding application icon
│
└── README.md                                  # Repository documentation manual
```

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
The application will run locally at "http://localhost:3000".
