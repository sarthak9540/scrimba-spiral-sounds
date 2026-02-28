# Spiral Sounds 🌀🎵

> **🎓 Educational Project & Attribution**
> This repository contains my completed codebase for the "Spiral Sounds" project, built as part of a guided follow-along course on [Scrimba](https://scrimba.com/).
>
> The original application architecture, UI design, and initial boilerplate are credited to Scrimba and the course instructor. This repository serves as a practical demonstration of my learning process and my ability to implement backend features using Express.js.

## 📚 Project Overview

Spiral Sounds is a backend express project designed to manage and serve a library of albums tracks, allowing users to fetch and add to cart the albums.

## 🚀 Express.js Skills Demonstrated

Completing this coursework required hands-on application of core Node.js and Express.js concepts. Key technical takeaways include:

- **RESTful API Architecture:** Designed and implemented standard HTTP routes (GET, POST, PUT, DELETE) for resource management.
- **Modular Routing:** Utilized `express.Router()` to cleanly separate route definitions from the main server file, ensuring scalable code architecture.
- **Middleware Implementation:** Applied both built-in (e.g., `express.json()`, `express.session()`) and custom middleware functions to process incoming requests and validate data.
- **Centralized Error Handling:** Developed error-handling middleware to catch application errors and return standardized, client-friendly HTTP status codes and messages.
- **Controller Logic:** Separated business logic from route handlers to maintain clean, readable, and maintainable code.

## 🛠️ Tech Stack

- **Backend Environment:** Node.js
- **Web Framework:** Express.js
- **[Add other tools used]:** e.g. dotenv (environment variables), sqlite3

## 🔮 Future Scope & Independent Enhancements

While the core of this project was guided, I plan to leverage this Express.js foundation to build out independent features:

- **Frontend Integration:** Connect this Express API to a modern Next.js client to consume and display the data.
- **Advanced Media Delivery:** Expand the backend logic to handle robust audio or video streaming capabilities.
- **Database Persistence:** Transition from static/mock data to a full database integration (e.g., MongoDB) to finalize a complete MERN stack architecture.

## 💻 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/sarthak9540/scrimba-spiral-sounds.git
   ```
2. Navigate to the project directory:
   ```bash
   cd scrimba-spiral-sounds
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
