Frontend Assignment - React with Vite 🚀
Project Setup
This project is a simple React app created using Vite to display a home page with name and contact details.

Installation Steps
Step 1: Initialize React App using Vite
bash
Copy
Edit
npm create vite@latest
Select React as the framework
Choose JavaScript as the variant
Step 2: Install Dependencies
bash
Copy
Edit
npm install react-router-dom axios dotenv
Step 3: Create a Home Page
Inside src, create a Home.jsx file:

jsx
Copy
Edit
import React from 'react';

const Home = () => {
  return (
    <div>
      <h1>Your Name</h1>
      <p>Contact: yournumber@gmail.com</p>
    </div>
  );
};

export default Home;
Step 4: Update App.jsx
jsx
Copy
Edit
import React from 'react';
import Home from './Home';

const App = () => {
  return (
    <div>
      <Home />
    </div>
  );
};

export default App;
Run the Project
bash
Copy
Edit
npm run dev
Push to GitHub
bash
Copy
Edit
git init
git add .
git commit -m "Frontend Assignment"
git branch -M main
git remote add origin your_repo_link
git push origin main
