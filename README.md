# Family-Travel-Tracker
🌍 Family Travel Tracker
A full-stack web application to track and visualize countries visited by each family member. This project helps families tally their global travels, compare progress, and set goals for future trips.

✨ Features
👨‍👩‍👧‍👦 Track visited countries for each family member

🌐 Visualize total and individual travel coverage

➕ Add, update, and remove travel records

📊 See common and unique destinations

🔐 Basic validation and error handling

🛠️ Tech Stack
Backend: Node.js + Express.js

Database: PostgreSQL

Frontend: (Optional placeholder if you add one — e.g., EJS / React / plain HTML)

Learning Focus: Hands-on practice with REST APIs and relational data handling

📦 How to Run Locally
Clone the Repository

bash
Copy
Edit
git clone https://github.com/yourusername/family-travel-tracker.git
cd family-travel-tracker
Install Dependencies

bash
Copy
Edit
npm install
Set Up PostgreSQL Database

Create a DB (e.g., travel_tracker)

Run the schema SQL script (/db/schema.sql)

Configure .env file:

ini
Copy
Edit
DB_HOST=localhost
DB_USER=your_pg_user
DB_PASSWORD=your_pg_password
DB_NAME=travel_tracker
DB_PORT=5432
Start the Server

bash

npm start
📁 Project Structure
pgsql
Copy
Edit
/family-travel-tracker
│
├── /routes        → API routes for members and countries
├── /controllers   → Request handlers
├── /db            → SQL schema & DB logic
├── /public        → Static frontend (if any)
├── .env           → Environment config
└── server.js      → Entry point
🚀 Why This Project?
This project was created to practice full-stack development using PostgreSQL and Express.js — especially focusing on:

Designing relational data (users ↔ countries)

Implementing clean REST API routes

Learning database joins, constraints, and queries
