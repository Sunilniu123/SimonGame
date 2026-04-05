# 🎮 Simon Says Game

A fun and interactive memory game built using HTML, CSS, and JavaScript. The game challenges players to remember and repeat an increasing sequence of colors.

## 🚀 Features
- Increasing difficulty with each level  
- Button animations (game flash & user flash)  
- Start game with any key press  
- Game over detection with score display  
- Restart functionality  

## 🛠️ Technologies Used
- HTML  
- CSS  
- JavaScript  

## 📂 Project Structure
Simon-Says-Game/
│── index.html  
│── SimonGame.js  
│── SimonGamejs.css  

## 🎮 How to Play
1. Press any key to start the game  
2. Watch the color sequence carefully  
3. Click the buttons in the same order  
4. With each level, the sequence increases  
5. If you click the wrong color → Game Over  

## 🧠 Game Logic
- The game generates a random color sequence  
- User input is stored and compared step-by-step  
- If the sequence matches → next level  
- If not → game resets  

## ⚠️ Known Issue
Change this line in your JavaScript file:
let randIdx = Math.floor(Math.random() * 3);

Fix:
let randIdx = Math.floor(Math.random() * 4);

## 🔧 Setup Instructions
1. Clone the repository  
git clone <your-repo-link>

2. Open index.html in your browser  

## 💡 Future Improvements
- Add sound effects  
- Make it mobile responsive  
- Add high score tracking  
- Improve UI/UX  

## 👨‍💻 Author
Sunil Kumar Prajapati
