# 🕒 TimeLapse- Social media application

A full-stack MERN (MongoDB, Express, React, Node.js) application that lets users create, view, like, update, and delete timeline-style posts. 
Each post can include a title, message, tags, and an image.

## 🚀 Features

- Create and share posts with images
- Edit and delete existing posts
- Like posts
- Add tags to categorize posts
- View posts in a responsive grid
- Real-time post updates using Redux

## 🛠️ Tech Stack

### Frontend
- React
- Redux
- Axios
- Material-UI
- FileBase64 (for file uploads)
- Moment.js

### Backend
- Node.js
- Express
- MongoDB (with Mongoose)
- dotenv

## 📦 API Endpoints

| Method | Route                   | Description           |
|--------|-------------------------|-----------------------|
| GET    | `/posts`                | Fetch all posts       |
| POST   | `/posts`                | Create a new post     |
| PATCH  | `/posts/:id`            | Update a post         |
| DELETE | `/posts/:id`            | Delete a post         |
| PATCH  | `/posts/:id/likePost`   | Like a post           |



