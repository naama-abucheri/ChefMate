# ChefMate

# 🧠 ChefMate –  Recipe Generator

ChefMate is a full-stack MERN web application that lets users generate personalized recipes based on the ingredients they have on hand.  the app produces creative, easy-to-follow recipes in real time. Users can sign up, generate meals, and save their favorite recipes for later.

![App Screenshot](./screenshot.png)

## 🔥 Live Demo
🌐 [View Deployed App](https://your-live-url.com)

---

## 🚀 Features

- 🧠 **AI Integration**: Uses OpenAI (GPT-3.5) to generate recipes based on user input.
- 🔐 **User Authentication**: Register and log in to manage your saved recipes.
- 🗃 **MongoDB Database**: Stores user data and saved recipe history.
- 💻 **Full-Stack MERN Architecture**: MongoDB, Express.js, React, Node.js.
- 🎨 **Responsive & Elegant UI**: Built with Tailwind CSS for a sleek user experience.
- 🔒 **Protected Routes**: Secure recipe management only for authenticated users.
- 📱 **Mobile-Friendly**: Optimized for all screen sizes.

---

## 🧱 Tech Stack

| Layer         | Technology                        |
|---------------|------------------------------------|
| **Frontend**  | React, Tailwind CSS, React Router  |
| **Backend**   | Node.js, Express                   |
| **AI**        | OpenAI GPT-3.5 (ChatCompletion API)|
| **Database**  | MongoDB, Mongoose                  |
| **Auth**      | JWT, bcrypt                        |
| **Deployment**| Vercel (frontend), Render (backend)|

---

## 📁 Folder Structure





project-root/
│
├── client/ # React Frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── services/
│ │ ├── App.jsx
│ │ └── index.js
│ └── tailwind.config.js
│
├── server/ # Node + Express Backend
│ ├── routes/
│ ├── controllers/
│ ├── models/
│ ├── middleware/
│ ├── .env
│ └── server.js
















---

## 🧠 How It Works

1. User enters a list of ingredients (e.g., `"onion, chicken, rice"`).
2. The backend sends this prompt to OpenAI’s GPT API.
3. GPT generates a unique recipe: title, ingredients, and steps.
4. The response is sent to the frontend and beautifully rendered.
5. Logged-in users can save the recipe to their profile.

---

## 📦 Installation Instructions

### ✅ Prerequisites
- Node.js
- MongoDB
- OpenAI API Key
- Git

---

### 🚀 Local Setup

1. **Clone the repo**

```bash
git clone https://github.com/your-username/chefmate.git
cd chefmate

#Backend
npm run dev


#frontend
cd ../client
npm install
npm run dev

