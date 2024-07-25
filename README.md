# 🍔 Wraply - Food Delivery System

<img src="/public/logo.jpg" alt="Wraply Logo" width="100" height="100" style="display: block; margin: auto;"/>

Wraply is a food delivery system frontend application built with React and Vite. It includes a dummy backend using Express for demonstration purposes.

## 🌟 Features

- 🚀 React-based frontend for a sleek food delivery application
- ⚡ Vite as the build tool for lightning-fast development and optimized production builds
- 🖥️ Express.js backend API (dummy) for simulating server interactions
- 🌐 Deployment-ready configuration for Vercel

## 🏗️ Project Structure

```
/project-root
├── 📂 /public
├── 📂 /api
│   └── 📄 index.js (Express server for dummy backend)
├── 📂 /src
│   ├── 📄 main.jsx
│   ├── 📄 App.jsx
│   └── 📂 ... other components
├── 📄 index.html
├── 📄 package.json
├── 📄 vite.config.js
└── 📄 vercel.json
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 18.x)
- npm (comes with Node.js)

### Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/wraply.git
   cd wraply
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```
   Open your browser and navigate to `http://localhost:5173` to view the application.

4. **Start the dummy backend server:**
   ```bash
   npm start
   ```
   This will run the Express server located in `api/index.js`.

## 🛠️ Building for Production

To create a production build:

```bash
npm run build
```

This will generate optimized files in the `dist` directory.

## 🌐 Deployment

This project is configured for easy deployment on Vercel. The `vercel.json` file includes the necessary settings for both the frontend and the serverless backend functions.

To deploy:

1. Install the Vercel CLI:
   ```bash
   npm i -g vercel
   ```
2. Run the deployment command:
   ```bash
   vercel
   ```
   Follow the prompts to complete the deployment.

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start the Vite development server |
| `npm run build` | Build the project for production |
| `npm run lint` | Run ESLint |
| `npm run preview` | Preview the production build locally |
| `npm start` | Start the Express backend server |
| `npm run vercel-build` | Build script for Vercel deployment |


## 📞 Contact

[Aditya Prakash]  - prakash610aditya@gmail.com

Project Link: [https://github.com/your-username/wraply](https://github.com/your-username/wraply)

---

⭐️ If you find this project useful, please consider giving it a star!

