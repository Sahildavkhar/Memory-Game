# 🧠 Memory Game

A simple **Memory Matching Game** built using **React**, **Vite**, and **Tailwind CSS**.  
Flip cards to reveal numbers and match pairs until you clear the entire board!

---

## 🚀 Features
- Dynamic grid size (2x2 to 10x10)
- Randomized cards for every game
- Flip and match logic with smooth transitions
- Win detection and reset/play-again functionality
- Responsive UI using Tailwind CSS

---

## 🗂️ Project Structure<br>
Memory-Game/<br>
├── public/<br>
├── src/<br>
│ ├── MemoryGame.jsx<br>
│ ├── index.css<br>
│ ├── main.jsx<br>
│ └── App.jsx<br>
├── package.json<br>
├── postcss.config.js<br>
├── tailwind.config.js<br>
├── vite.config.js<br>
└── README.md<br>


---

## ⚙️ Installation & Setup

### Prerequisites
- [Node.js](https://nodejs.org/) (v16+ recommended)
- npm or yarn

### Steps to Run Locally
```bash
# Clone the repository
git clone https://github.com/Sahildavkhar/Memory-Game.git

# Move into the project directory
cd Memory-Game

# Install dependencies
npm install

# Run the development server
npm run dev
```
The app will start at http://localhost:5173/ by default.<br>

🧩 **How It Works**

Generates a shuffled grid of card pairs based on the selected grid size.<br>
Tracks flipped and solved cards using React state.<br>
Matches pairs and locks solved ones.<br>
Detects win condition when all pairs are matched.<br>
Allows grid resizing and restarting the game anytime.<br>
