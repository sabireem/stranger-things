# 🔦 Stranger Things - Interactive Hero Page

A visually stunning, interactive hero landing page inspired by Netflix's **Stranger Things** series. Built with React and Vite, featuring immersive animations and a unique fire-reveal mouse effect.

![React](https://img.shields.io/badge/React-19.1.0-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-7.3.0-646CFF?logo=vite)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-12.16.0-FF0055?logo=framer)

---

## ✨ Features

- 🎬 **Cinematic Hero Section** - Dark, atmospheric design inspired by the Upside Down
- 🔥 **Fire Reveal Effect** - Interactive mouse-following reveal effect with smooth animations
- 🎭 **Framer Motion Animations** - Elegant staggered animations with spring physics
- 📱 **Responsive Design** - Looks great on all device sizes
- ⚡ **Lightning Fast** - Powered by Vite for instant HMR and optimized builds

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sabireem/stranger-things.git
   cd stranger-things/vite-project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser** and navigate to `http://localhost:5173`

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **React 19** | UI Component Library |
| **Vite 7** | Build Tool & Dev Server |
| **Framer Motion** | Animation Library |
| **CSS3** | Styling & Effects |

---

## 📁 Project Structure

```
vite-project/
├── public/
│   └── bg.png              # Background image
├── src/
│   ├── assets/             # Static assets
│   ├── components/
│   │   ├── Hero.jsx        # Main hero section component
│   │   ├── Hero.css        # Hero styling with fire reveal effect
│   │   ├── Navbar.jsx      # Navigation bar component
│   │   └── Navbar.css      # Navbar styling
│   ├── App.jsx             # Root application component
│   ├── App.css             # Global app styles
│   ├── main.jsx            # Application entry point
│   └── index.css           # Global CSS reset/base styles
├── index.html              # HTML template
├── vite.config.js          # Vite configuration
├── eslint.config.js        # ESLint configuration
└── package.json            # Project dependencies
```

---

## 🎨 Key Components

### Hero Component
The main attraction featuring:
- **Staggered text animations** using Framer Motion
- **Mouse-tracking fire reveal effect** with smooth interpolation
- **Atmospheric design** with the Mind Flayer theme

### Fire Reveal Effect
A custom mouse-following effect that:
- Tracks cursor position with eased interpolation
- Creates an immersive "revealing" visual effect
- Uses CSS custom properties for real-time updates

---

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with HMR |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint for code quality |

---

## 🌐 Deployment

Build the project for production:

```bash
npm run build
```

The optimized files will be in the `dist/` folder, ready for deployment to:
- Vercel
- Netlify
- GitHub Pages
- Any static hosting service

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Inspired by Netflix's **Stranger Things** series
- Built with ❤️ using React and Vite
- Animation magic powered by Framer Motion

---

<p align="center">
  <strong>👻 "Friends don't lie." - Eleven</strong>
</p>
