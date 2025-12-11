# 🍌🐵 BATTLE OF THE BANANAS: Monkey Puzzle Game! 🐵🍌

<div align="center">

![Banana Game Logo](https://img.shields.io/badge/Banana-Game-yellow?style=for-the-badge&logo=react&logoColor=white)
![React](https://img.shields.io/badge/React-18.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**🧠 Test Your Monkey Brain Power! 🧠**

*Put your banana knowledge to the ultimate test in this epic puzzle adventure!*

🍌 **Challenge yourself!** 🍌 **Compete globally!** 🍌 **Earn points!** 🍌

[🚀 Play Now](#getting-started) | [📱 Demo](#live-demo) | [🛠️ Tech Stack](#tech-stack)

---

## 🎯 What is Battle of the Bananas?

**Battle of the Bananas** is an insanely fun, interactive web game where players race against time to solve banana-themed puzzles! 🏆

- **🤔 Puzzle Solving**: Identify mystery images and guess what they are!
- **⏱️ Speed Challenge**: Beat the clock to maximize points!
- **🩺 Difficulty Levels**: Easy (60s), Medium (45s), Hard (30s) - for all skill levels!
- **🪙 Power-Ups**: Use coins to freeze time, double points, and gain advantages!
- **🏅 Global Leaderboard**: See how you rank against players worldwide!
- **🎨 Beautiful UI**: Stunning animations powered by GSAP with a monkey-banana theme!

---

## 🌟 Key Features

### 🎮 Core Gameplay
- **🟢 Easy Mode**: 60 seconds - Perfect for beginners! 🌱
- **🟡 Medium Mode**: 45 seconds - Monkey Challenge! 🐒
- **🔴 Hard Mode**: 30 seconds - Expert Level! 🦧
- **💰 Coin System**: Earn coins for correct answers and special achievements 💰
- **🔥 Streak System**: Build combo streaks for bonus points! 🔥
- **⏰ Power-Ups**: Freeze timer (❄️) or double points (2x💎)!

### 👤 User Experience
- **♿ Accessibility**: Full keyboard navigation and screen reader support
- **📱 Responsive Design**: Play anywhere - desktop, tablet, or mobile!
- **🎨 Custom Animations**: GSAP-powered smooth transitions and effects
- **🌈 Dark/Light Themes**: Comfortable viewing in any lighting
- **🔒 Secure Authentication**: JWT-based login system
- **📊 Detailed Stats**: Track your progress with comprehensive statistics

### 🔧 Advanced Features
- **👑 Admin Dashboard**: Complete game management system
- **📈 Real-time Leaderboard**: Live ranking updates
- **🎯 Personalized Profiles**: View and update your gaming stats
- **🔔 Toast Notifications**: Get instant feedback on your actions!
- **⚡ Real-time Updates**: Live coin and score counters
- **🔄 Auto-save**: Never lose your progress!

---

## 🚀 Getting Started

### Prerequisites 📋

Before you begin, ensure you have:
- **🖥️ Node.js** (version 16 or higher)
- **📝 npm** or **🧵 yarn** package manager
- **🌐 Internet connection** for fetching puzzles

### Installation 🛠️

#### 1. **Clone the Repository** 📥
```bash
git clone <repository-url>
cd banana-monkey-game
```

#### 2. **Install Dependencies** 📦
```bash
npm install
# or
yarn install
```

#### 3. **Environment Setup** ⚙️
Create a `.env.local` file in the root directory:
```env
VITE_API_URL=http://localhost:8000/api
VITE_GAME_ENV=development
```

#### 4. **Start the Development Server** ▶️
```bash
npm run dev
# or
yarn dev
```

🎉 **Open your browser to `http://localhost:5173`** and start playing!

---

## 🎮 How to Play

### 🎯 Game Rules
1. **Choose Difficulty**: Select Easy 🟢, Medium 🟡, or Hard 🔴
2. **View Puzzle**: A mysterious image appears! 🤔
3. **Type Your Guess**: What do you think it is? ⌨️
4. **Beat the Clock**: Answer before time runs out! ⏱️
5. **Earn Points**: Correct answers give points (10/20/30 based on difficulty) 💎
6. **Build Streaks**: Consecutive correct answers multiply your score! 🔥

### 🪙 Coin System Explained
- **Correct Answer**: +1-3 coins (based on difficulty)
- **Streak Bonus**: Extra coins for maintaining streaks
- **Early Answer Bonus**: Points for answering quickly
- **Use Coins**: Buy power-ups like timer freeze or double points!

### ⏰ Power-Up Guide
- **❄️ Freeze Timer**: Pause time for 5s or 10s (costs 20/35 coins)
- **💰 2x Points**: Double points on next answer (costs 50 coins)
- **Unlock Bonuses**: Special achievements give exclusive power-ups!

---

## 🛠️ Tech Stack

### 🎨 Frontend Technologies
![React](https://img.shields.io/badge/React-18.0-61DAFB?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

### 🏗️ Core Libraries
- **UI Components**: shadcn/ui with Radix UI primitives 🧱
- **State Management**: React Context + Zustand 📊
- **Routing**: React Router v6 🗺️
- **Forms**: React Hook Form + Zod validation 📝
- **Animations**: GSAP (GreenSock Animation Platform) ✨
- **HTTP Client**: Axios 🌐
- **Icons**: Lucide React + custom emojis 😎

### 🔧 Development Tools
- **Build Tool**: Vite ⚡
- **Testing**: Vitest + React Testing Library 🧪
- **Linting**: ESLint 🚨
- **Formatting**: Prettier 🎨
- **Version Control**: Git + GitHub 🐙

---

## 📁 Project Structure

```
banana-monkey-game/
├── 🎯 public/               # Static assets
│   ├── favicon.ico         # Game favicon
│   ├── placeholder.svg     # Default images
│   └── robots.txt         # SEO optimization
├── 🌟 src/                 # Source code
│   ├── 🧩 components/       # Reusable UI components
│   │   ├── DifficultySelector.tsx 🟢🟡🔴
│   │   ├── Navbar.tsx      # Navigation bar
│   │   └── ui/             # shadcn/ui components
│   ├── 🎮 contexts/         # React contexts
│   │   └── AuthContext.tsx # User authentication
│   ├── 🗂️ hooks/           # Custom React hooks
│   │   ├── use-toast.ts    # Notification system
│   │   └── use-mobile.tsx  # Responsive design
│   ├── 📄 pages/           # Page components
│   │   ├── Home.tsx       # Landing page 🍌
│   │   ├── GamePage.tsx   # Main game interface 🧠
│   │   ├── LeaderboardPage.tsx 🏆
│   │   ├── ProfilePage.tsx 👤
│   │   ├── AdminPage.tsx   👑 (Admin only)
│   │   └── Login.tsx      # Authentication
│   ├── 🌐 services/        # API service functions
│   │   ├── gameService.ts # Game API calls 🎮
│   │   ├── authService.ts # Auth API calls 🔐
│   │   └── leaderboardService.ts 🏅
│   ├── 🎨 lib/             # Utility functions
│   │   └── utils.ts       # Helper functions
│   └── 📊 config/          # Configuration files
├── 🤖 vite.config.ts      # Vite configuration
├── 🎨 tailwind.config.ts  # Tailwind CSS config
├── 📏 tsconfig.json       # TypeScript config
└── 📋 package.json       # Dependencies & scripts
```

---

## 🎯 Usage Examples

### 🏃‍♂️ Quick Start
```typescript
// Main app entry point
import { createRoot } from 'react-dom/client';
import App from './App';
import './index.css';

const container = document.getElementById('root')!;
const root = createRoot(container);
root.render(<App />);
```

### 🎮 Game Component Usage
```typescript
import DifficultySelector from './components/DifficultySelector';

function GamePage() {
  const startGame = (difficulty: string) => {
    // Start game with selected difficulty
    console.log(`Starting ${difficulty} mode! 🍌`);
  };

  return (
    <DifficultySelector
      onDifficultySelect={startGame}
      loading={false}
    />
  );
}
```

### 🔐 Authentication Hook
```typescript
import { useAuth } from './contexts/AuthContext';

function Profile() {
  const { user, login, logout } = useAuth();

  return (
    <div>
      {user ? (
        <div>
          Welcome, {user.username}! 🐵
          <button onClick={logout}>Logout</button>
        </div>
      ) : (
        <button onClick={() => login(credentials)}>Login</button>
      )}
    </div>
  );
}
```

---

## 🎉 Screenshots & Live Demo

### 🌍 Live Demo
Heroku/ Vercel/ Netlify deployment coming soon! 🚀

### 📸 Game Screenshots

#### 🏠 Home Page
Beautiful landing page with animated bananas, game features, and user interface

#### 🎯 Game Interface
- Stunning puzzle area with corner monkey decorations 🐵🍌
- Power-up buttons with tooltips and coin costs 💰
- Real-time timer with freeze capabilities ⏰❄️
- Animated progress bar with color-coded difficulty
- User stats tracking with emojis 📊
- Responsive design for mobile and desktop 📱💻

#### 🏆 Leaderboard
Global ranking system with user avatars and scores 👥

#### 👤 Profile Page
Personal statistics, game history, and achievements 🏅

---

## 🤝 Contributing

We love banana enthusiasts! 🐵 Banana lovers wanted! 🍌

### How to Contribute

1. **🍴 Fork the Repository** on GitHub
2. **🌿 Create a Feature Branch**: `git checkout -b feature/amazing-banana-feature`
3. **💻 Make Your Changes**: Add more bananas, monkeys, or puzzle types!
4. **🧪 Add Tests**: Ensure your changes don't break existing functionality
5. **📝 Update Documentation**: Keep our README banana-fresh! 🍌
6. **🚀 Submit a Pull Request**: Let's merge your monkey magic! 🐒

### 🐛 Bug Reports & Feature Requests
Found a bug? Have a banana-inspired idea?
- [🐛 Open an Issue](../../issues) on GitHub
- Use the bug report or feature request templates
- Include screenshots, browser info, and detailed steps

### 📜 Contribution Guidelines
- Follow our [Code of Conduct](./CODE_OF_CONDUCT.md) 🍌
- Write clear, descriptive commit messages
- Test your changes across different browsers
- Keep the banana theme alive! 🥴

---

## 🧪 Testing

```bash
# Run tests
npm test

# Run tests in watch mode
npm run test:watch

# Run tests with coverage
npm run test:coverage

# Run e2e tests
npm run test:e2e
```

---

## 📦 Build & Deployment

### Production Build 🏗️
```bash
npm run build
```

### Preview Production Build 👀
```bash
npm run preview
```

### Deployment 🚀
The project can be deployed to:
- **Vercel** (recommended for React projects)
- **Netlify** (excellent for static sites)
- **Heroku** (full-stack deployment)
- **AWS S3 + CloudFront**
- **Firebase Hosting**

---

## 🏷️ License

Distributed under the **MIT License**. See [LICENSE](./LICENSE) for more information.

```
MIT License

© 2025 Battle of the Bananas Team

Permission granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without
limitation the rights to use, copy, modify, merge, publish, distribute,
sublicense, and/or sell copies of the Software, and to permit persons
to whom the Software is furnished to do so...
```

---

## 🙏 Acknowledgments

- **Monkey Wisdom Contributors**: Special thanks to all banana experts who helped design the puzzle database! 🐵🧠
- **Open Source Community**: Built with love using incredible open-source tools ❤️
- **GSAP**: Amazing animation library that brings our bananas to life! 🍌✨
- **shadcn/ui**: Beautiful, accessible UI components 🎨
- **React Team**: For the best frontend framework ever! ⚛️
- **TypeScript**: Making our code banana-safe and bug-free! 🛡️

---

## 📞 Contact & Support

### 🆘 Need Help?
- **🐛 Bugs & Issues**: [GitHub Issues](../../issues)
- **💬 Discussions**: [Start a Discussion](../../discussions)
- **📧 Email**: support@bananagame.dev
- **🕴️ Discord**: Join our Banana Chat server!

### 🥳 Follow Us
- **🐦 Twitter**: [@BananaGameDev](https://twitter.com/banagame)
- **📺 YouTube**: [Banana Game Tutorials](https://youtube.com/banagame)
- **📱 Instagram**: [@banana_game_official](https://instagram.com/banana_game_official)

---

## 🎊 What's Next?

### 🗺️ Roadmap
- **🎮 Mobile App**: Native iOS/Android apps with offline puzzles 📱
- **🌍 Multiplayer Mode**: Real-time battles with other players! ⚔️
- **🏆 Tournaments**: Weekly challenges and prizes 🏅
- **🎨 Custom Themes**: Unlock new monkey avatars and backgrounds 🐒
- **🤖 AI Puzzles**: Machine learning-generated banana mysteries 🤖
- **🔊 Sound Effects**: Immersive audio for every correct answer! 🔊
- **🌟 Achievements**: Unlock banana badges and stickers 🌟
- **📊 Advanced Analytics**: Detailed player performance metrics 📈

### 🚀 Future Features Wishlist
- Daily puzzles and challenges 📅
- Friend system and challenges 👥
- Virtual banana shop with items 🛒
- Seasonal events with special puzzles 🎄
- Puzzle creation tool for contributors 🛠️
- Voice recognition for answers 🎤

---

<div align="center">

**🎯 Ready to go bananas? Start playing now! 🍌**

**Built with ❤️, 🐵, and a lot of 🍌 by the Banana Game Team**

*© 2025 Battle of the Bananas - All Rights Reserved*

**[⬆️ Back to Top](#-battle-of-the-bananas-monkey-puzzle-game-)**

</div>
