# 📖 FullStackVistaGram  

A **full-stack social media app** built with **React (frontend)** and **Spring Boot + MongoDB (backend)**.  

---

## 🚀 Tech Stack  

### Frontend  
- ⚛️ React.js  
- 🛣️ React Router  
- 🎨 CSS  

### Backend  
- ☕ Spring Boot (Java)  
- 🍃 MongoDB (Atlas)  
- 🔧 Lombok  

---

## 📂 Project Structure  

```
FullStackVistaGram/
│
├── frontend/               # React frontend
│   ├── src/
│   │   ├── App.js
│   │   └── Pages/
│   │       ├── Home.js
│   │       └── PostView.js
│   └── package.json
│
├── backend/                # Spring Boot backend
│   ├── src/main/java/com/example/VistaGram/
│   │   ├── Controller/MainController.java
│   │   ├── Entity/PostEntity.java
│   │   └── Services/PostServices.java
│   └── pom.xml
│
└── README.md
```

---

## ⚡ Features  

- 📄 View all posts  
- 🔍 View a single post by ID  
- ➕ Create a new post  
- ✏️ Update existing post  
- 🛣️ React Router for navigation  

---

## 🖥️ Frontend Setup  

```bash
cd frontend
npm install
npm start
```

Runs at 👉 **http://localhost:3000**  

---

## ⚙️ Backend Setup  

1. Make sure you have **Java 21+** and **Maven** installed.  
2. Configure MongoDB Atlas connection in `.env` file (inside backend folder):  

```
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/vistagram
```

3. Run backend:  

```bash
cd backend
./mvnw spring-boot:run
```

Backend will run at 👉 **http://localhost:8080**  

---

## 📡 API Endpoints  

| Method | Endpoint         | Description              |
|--------|-----------------|--------------------------|
| GET    | `/allPost`      | Get all posts            |
| GET    | `/postId?id=1`  | Get post by ID           |
| POST   | `/createPost`   | Create a new post        |
| PUT    | `/updatePost`   | Update existing post     |

---

## 🌍 CORS  

The backend allows requests from the frontend running at:  
```
http://localhost:3000
```

---

## 🔮 Future Improvements  

- 🔐 Add authentication (JWT)  
- 🖼️ Support image uploads  
- ❤️ Add likes & comments  
- 🚀 Deploy backend to **Render** and frontend to **Netlify/Vercel**  

---

✨ Built with ❤️ by **Naitik Mishra**  
