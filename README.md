# 💪 React Fitness Exercise App

<p align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/MUI-007FFF?style=for-the-badge&logo=mui&logoColor=white"/>
  <img src="https://img.shields.io/badge/RapidAPI-0055DA?style=for-the-badge&logo=rapid&logoColor=white"/>
</p>

A feature-rich **Fitness & Exercise** web application powered by **React.js**, **Material UI**, and the **ExerciseDB API** via RapidAPI. Browse thousands of exercises, filter by muscle group, and watch YouTube tutorials for each movement.

---

## ✨ Features

- 🏋️ Browse **1,300+ exercises** from ExerciseDB API
- 🔍 Search exercises by name, muscle group, or equipment
- 💪 Filter by **target muscle**, **body part**, and **equipment type**
- 📹 Watch **YouTube exercise tutorial videos** for each exercise
- 📊 View similar exercises and target muscle animations
- 📱 Fully **responsive** across all devices
- ⚡ Horizontal scrollable category cards with smooth UX
- 🎨 Clean, modern UI with **Material UI** components

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **React 18** | Component-based UI |
| **Material UI (MUI)** | UI component library |
| **RapidAPI — ExerciseDB** | Exercise data (1,300+ exercises) |
| **RapidAPI — YouTube Search** | Exercise video tutorials |
| **React Router** | Client-side navigation |
| **CSS** | Custom styling |

---

## 🚀 Getting Started

### Prerequisites
- Node.js 16+
- A free [RapidAPI](https://rapidapi.com) account

### Installation

```bash
# Clone the repository
git clone https://github.com/yuvrajsinghantino/exercise-app.git
cd exercise-app

# Install dependencies
npm install
```

### Environment Setup

Create a `.env` file in the root:

```env
REACT_APP_RAPID_API_KEY=your_rapidapi_key_here
```

Get your free API key at [rapidapi.com/justin-WFnsXH_t6/api/exercisedb](https://rapidapi.com/justin-WFnsXH_t6/api/exercisedb)

```bash
# Start the development server
npm start
```

Open [http://localhost:3000](http://localhost:3000)

---

## 📁 Project Structure

```
exercise-app/
├── src/
│   ├── components/
│   │   ├── ExerciseCard.js       # Individual exercise card
│   │   ├── Exercises.js          # Exercise listing with pagination
│   │   ├── SearchExercises.js    # Search & filter bar
│   │   ├── HorizontalScrollbar.js # Category scroll component
│   │   ├── Detail.js             # Exercise detail view
│   │   └── ExerciseVideos.js     # YouTube video embed
│   ├── pages/
│   │   ├── Home.js               # Home page
│   │   └── ExerciseDetail.js     # Detail page
│   ├── utils/
│   │   └── fetchData.js          # RapidAPI fetching utility
│   └── App.js
└── public/
```

---

## 🌐 API Integration

```javascript
// Fetching exercises from ExerciseDB via RapidAPI
const options = {
  method: 'GET',
  headers: {
    'X-RapidAPI-Key': process.env.REACT_APP_RAPID_API_KEY,
    'X-RapidAPI-Host': 'exercisedb.p.rapidapi.com'
  }
};

const data = await fetch(url, options);
```

---

## 👨‍💻 Author

**Yuvraj Singh** — Frontend Engineer | React · Next.js · TypeScript

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/yuvrajsinghantino)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/yuvrajsinghantino)
