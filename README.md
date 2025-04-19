# Tic-Tac-Toe-DevSecOps


![image](https://github.com/user-attachments/assets/c982fe61-71cc-4102-becd-dbb4581d98f3)


In today's fast-paced development environments, speed without security is a risk. DevSecOps—short for Development, Security, and Operations—is a modern approach that ensures security is not an afterthought, but a shared responsibility integrated into every phase of the software development lifecycle (SDLC).

🚀 Why DevSecOps?

Shifts security left: Detect and fix vulnerabilities early, not in production.

Fosters collaboration between developers, operations, and security teams.

Automates security checks using CI/CD pipelines to prevent delays.

Reduces risk of data breaches and compliance violations.

Builds secure software faster and more confidently.

🛡️ DevSecOps empowers teams to deliver resilient, secure, and scalable applications without sacrificing speed.

## Features

- 🎮 Fully functional Tic Tac Toe game
- 📊 Score tracking for X, O, and draws
- 📜 Game history with timestamps
- 🏆 Highlights winning combinations
- 🔄 Reset game and statistics
- 📱 Responsive design for all devices

## Technologies Used

- React 18
- TypeScript
- Tailwind CSS
- Lucide React for icons

## Project Structure

```
src/
├── components/
│   ├── Board.tsx       # Game board component
│   ├── Square.tsx      # Individual square component
│   ├── ScoreBoard.tsx  # Score tracking component
│   └── GameHistory.tsx # Game history component
├── utils/
│   └── gameLogic.ts    # Game logic utilities
├── App.tsx             # Main application component
└── main.tsx           # Entry point
```

## Game Logic

The game implements the following rules:

1. X goes first, followed by O
2. The first player to get 3 of their marks in a row (horizontally, vertically, or diagonally) wins
3. If all 9 squares are filled and no player has 3 marks in a row, the game is a draw
4. Winning combinations are highlighted
5. Game statistics are tracked and displayed

![image](https://github.com/user-attachments/assets/5ddb5495-2bfd-4f74-a801-4b77276808f1)


## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/devsecops-demo.git
   cd devsecops-demo
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Building for Production

To create a production build:

```bash
npm run build
# or
yarn build
```

The build artifacts will be stored in the `dist/` directory.
