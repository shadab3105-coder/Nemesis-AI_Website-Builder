# 🚀 Nemesis – The AI Website Builder

Nemesis is an **AI-powered frontend website builder** built with the MERN stack and Generative AI. It allows users to describe a website using a natural-language prompt and generates the corresponding **HTML, CSS, and JavaScript code**, along with a live preview.

## ✨ Features

* 🤖 AI-powered website generation from natural-language prompts
* 🧩 Generates responsive frontend code
* 👀 Live website preview
* 💻 View and edit generated source code
* 🔐 Google Authentication using Firebase
* 🔑 JWT-based authentication with HTTP-only cookies
* 💳 Credit-based AI generation system
* 🖼️ Image integration using Unsplash / Pexels APIs
* ⚡ Responsive and modern UI
* 🔄 AI generation workflow with structured JSON responses
* 💰 Free and paid plans with credit management
* 💳 Stripe integration for subscription/payment workflow

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* JavaScript
* Tailwind CSS
* Framer Motion

### Backend

* Node.js
* Express.js
* REST APIs
* JWT Authentication
* HTTP-only Cookies

### Database

* MongoDB
* MongoDB Atlas

### Authentication

* Firebase Authentication
* Google OAuth
* JWT

### AI & APIs

* Generative AI APIs
* OpenRouter
* Gemini API
* Unsplash API
* Pexels API

### Payments

* Stripe

### Tools

* Git
* GitHub
* VS Code

## 🏗️ How It Works

```text
User Prompt
     ↓
AI Generation API
     ↓
Structured Website Response
     ↓
HTML + CSS + JavaScript
     ↓
Live Preview + Source Code
```

## 📁 Project Structure

```text
Nemesis/
│
├── client/                 # React frontend
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── ...
│
├── server/                 # Node.js / Express backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── ...
│
├── .env
├── package.json
└── README.md
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Shadab3105-coder/2.websiteBuilder.git
cd 2.websiteBuilder
```

### 2. Install dependencies

For the frontend:

```bash
cd client
npm install
```

For the backend:

```bash
cd ../server
npm install
```

### 3. Configure Environment Variables

Create `.env` files and add the required configuration:

```env
MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

OPENROUTER_API_KEY=your_openrouter_api_key

GEMINI_API_KEY=your_gemini_api_key

VITE_FIREBASE_API_KEY=your_firebase_api_key

STRIPE_SECRET_KEY=your_stripe_secret_key
```

> Never commit API keys, database credentials, or other secrets to GitHub.

### 4. Run the Application

Start the backend:

```bash
npm run dev
```

Start the frontend:

```bash
npm run dev
```

The application will be available on the local development server.

## 🔐 Authentication Flow

Nemesis uses Firebase for Google authentication and JWT for maintaining authenticated sessions.

```text
Google Login
     ↓
Firebase Authentication
     ↓
Backend Authentication
     ↓
JWT Token
     ↓
HTTP-only Cookie
     ↓
Authenticated User
```

## 🤖 AI Generation

Users provide a prompt describing the website they want to build.

Example:

```text
Create a modern food delivery landing page
with a hero section, food cards, pricing section
and a responsive navigation bar.
```

The AI processes the prompt and returns structured website data that is converted into frontend code and displayed through the live preview.

## 💳 Credit System

Nemesis uses a credit-based generation model.

* Users receive credits according to their plan.
* Each AI website generation consumes credits.
* Different plans can provide different credit limits.
* The backend manages and validates credit usage.

## 🖼️ Image Integration

The generated websites can use external images through image APIs such as:

* Unsplash
* Pexels

This helps generated websites contain more realistic visual content instead of relying only on placeholders.

## 📌 Current Project Status

Nemesis is currently focused on **AI-powered frontend website generation**.

The current workflow supports:

* Natural-language website prompts
* AI-generated frontend code
* HTML/CSS/JavaScript generation
* Live preview
* Source-code viewing
* User authentication
* Credit management
* API integrations

## 🚀 Future Improvements

* Full multi-page website generation
* Advanced code editing
* One-click website deployment
* Custom domains
* More AI model providers
* Website version history
* Improved design controls
* Component-level regeneration


### Technologies

`React.js` `Node.js` `Express.js` `MongoDB` `JavaScript` `Tailwind CSS` `Firebase` `JWT` `GenAI` `OpenRouter` `Gemini` `Stripe`

---

⭐ If you find this project useful, consider giving the repository a star.

Live Project Link:- https://nemesis-ai-genweb.onrender.com/
