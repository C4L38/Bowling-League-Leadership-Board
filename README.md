# Bowling-League-Leadership-Board
Prerequisites:
Make sure you have:

Node.js installed

A code editor (e.g., VS Code)

📦 Step 1: Create a React App
Open your terminal and run:

npx create-react-app bowling-leaderboard
cd bowling-leaderboard

🎨 Step 2: Set Up Tailwind CSS
Install Tailwind and its dependencies:
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

Update tailwind.config.js:
content: ["./src/**/*.{js,jsx,ts,tsx}"]

Replace src/index.css with:
@tailwind base;
@tailwind components;
@tailwind utilities;
Remove default styles from App.css or clear it out.

📁 Step 3: Install Extra Packages
Still in your project directory:
npm install framer-motion recharts lucide-react
_These power your animations, bar charts, and icons._

💻 Step 4: Replace the App Component
Create a file:
src/Leaderboard.jsx

Paste the leaderboard code (from above) into that file.

Replace your src/App.js with:
import Leaderboard from "./Leaderboard";

function App() {
  return <Leaderboard />;
}


