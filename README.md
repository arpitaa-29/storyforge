# 📖 StoryForge — Collaborative Story Building Platform

StoryForge is a full-stack platform that empowers users to co-create fiction with real-time collaboration. Writers can build branching narratives together, explore community stories, and manage their profile — all in one smooth experience.

---

## 🔧 Tech Stack

| Layer         | Technologies Used                                                 |
|--------------|--------------------------------------------------------------------|
| Frontend      | React.js, Tailwind CSS, Axios                                     |
| Backend       | Spring Boot (Java), MySQL, JWT, DTO-based architecture            |
| Real-Time     | WebSockets (STOMP over SockJS)                                    |
| Auth & APIs   | JWT-based authentication, REST APIs                               |

---

## 🔗 Repositories

- 💻 **Frontend Repo**: [storyforge-ui](https://github.com/arpitaa-29/storyforge-ui)
- 🛠️ **Backend Repo**: [storyforge-backend](https://github.com/arpitaa-29/storyforge-backend)

---

## 🚀 Key Features

- 🔐 JWT-based user registration, login, and profile management
- ✍️ Create, edit, and collaborate on story chapters in real time
- 📚 Explore stories with search, genre filters, pagination, and reader mode
- 🧱 Clean backend architecture (Controller–Service–Repository–DTO)
- 🖼️ Avatar upload and user profile editing
- ⚙️ Global error handling, database optimization, and scalability

---

## 📸 Screenshots



---

## 🛠️ Running the Project

### 🧩 Backend Setup

1. Clone the backend repo:
   ```bash
   git clone https://github.com/arpitaa-29/storyforge-backend
Set up your application.properties with:


spring.datasource.url=jdbc:mysql://localhost:3306/storyforge
spring.datasource.username=your_user
spring.datasource.password=your_password
Run the app via your IDE or:


./mvnw spring-boot:run
🌐 Frontend Setup
Clone the frontend repo:


git clone https://github.com/arpitaa-29/storyforge-ui
Install dependencies:


npm install
Start the app:


npm start
✨ Future Enhancements
Google/GitHub OAuth

Commenting on stories

Story drafts and publishing workflows

Reactions and bookmarks

👩‍💻 Author
Arpita 

