# AILibraryVault.com

**AILibraryVault** is a modern AI library and news portal that helps users discover and vote on AI models while staying updated with the latest AI industry news. Built with the MERN stack (MongoDB, Express, React, Node.js), the platform is scalable, easy to use, and continuously updated through an automated scraping pipeline.

---

## 🌐 Live Site

Coming Soon

---

## 📌 Features

- 🔍 Browse AI models by type or field (e.g. Chatbot, Image Generator, Finance, Healthcare)
- 🗳️ Vote on AI models (Upvote/Downvote system)
- 🧠 View AI model details (name, description, type, field, vote stats)
- 📰 Get AI news scraped from trusted sources like TechCrunch and VentureBeat
- 🔐 User authentication (JWT-based) – register, login, and manage profile
- 🧑‍💼 Admin dashboard to manage model listings (add/edit/delete)
- 📱 Responsive and modern frontend with React + TailwindCSS
- 📊 MongoDB schema designed for scalability and searchability
- ⏱️ Scheduled scraper updates news content daily
- 🧰 RESTful API with full CRUD operations and secure endpoints

---

## 🛠 Tech Stack

| Layer        | Tech                               |
|--------------|------------------------------------|
| Frontend     | React, TailwindCSS, React Router   |
| State Mgmt   | Context API / Redux Toolkit        |
| Backend API  | Node.js, Express.js                |
| Database     | MongoDB, Mongoose                  |
| Auth         | JWT, bcrypt                        |
| Scraping     | Cheerio, Axios, Puppeteer, RSS     |
| Scheduler    | node-cron                          |
| Deployment   | Render / Vercel / Railway (Planned)|

---

## 📁 Project Structure

```bash
AILibraryVault/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   ├── scraper/
│   ├── .env
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── api/
│   │   ├── App.js
│   │   └── index.js
│   ├── public/
│   └── tailwind.config.js
├── README.md
└── package.json
