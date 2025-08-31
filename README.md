# 🎨 Fluent Community Quiz

A interactive quiz application to test knowledge about the Fluent ecosystem and mint personalized Expressive IDs for community members.

## 🚀 Live Demo

[View Live Site](https://your-vercel-url.vercel.app) *(Replace with your actual Vercel URL)*

## ✨ Features

### 🧠 **Interactive Quiz System**
- 10 randomized questions about Fluent's blended execution network
- 6-second timer per question with visual warnings
- Real-time scoring and progress tracking
- Immediate feedback with correct/incorrect highlighting

### 🎯 **Smart Attempt Management**
- Limited to 2 attempts per user
- Questions shuffle on each retry for fresh experience
- Attempt counter with visual warnings

### 🎨 **Expressive ID Minting**
- Custom profile picture upload with live preview
- Personalized user details form including:
  - Username customization
  - Auto-calculated blended rank based on quiz score
  - Discord role selection
  - Community-specific preferences
- Animated holographic ID card generation
- Downloadable PNG certificate

### 🎭 **Premium Design**
- Purple and black theme with art palette background
- Smooth animations and hover effects
- Responsive design for all devices
- Glassmorphism UI elements with backdrop blur

## 🛠️ Tech Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Custom CSS with gradients, animations, and responsive design
- **Icons**: Unicode emoji and custom SVG graphics
- **Deployment**: Optimized for Vercel hosting

## 📁 Project Structure

```
fluent-quiz/
├── index.html          # Main quiz application
├── README.md          # Project documentation
└── .vercelignore      # Vercel deployment config (optional)
```

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/fluent-quiz.git
   cd fluent-quiz
   ```

2. **Open locally**
   ```bash
   # Simply open index.html in your browser
   open index.html
   # Or use a local server
   python -m http.server 8000
   ```

### Deploy to Vercel

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Connect to Vercel**
   - Go to [Vercel Dashboard](https://vercel.com)
   - Import your GitHub repository
   - Deploy automatically (no build configuration needed)

3. **Custom Domain (Optional)**
   - Add your custom domain in Vercel settings
   - Update the live demo link above

## 🎮 How to Use

### Taking the Quiz
1. **Start Quiz**: Questions appear with 6-second timer
2. **Answer Questions**: Click your choice before time runs out
3. **View Results**: See your score out of 10
4. **Retry**: Up to 2 attempts with shuffled questions

### Minting Your ID
1. **Complete Quiz**: Finish all 10 questions
2. **Click "Mint Your ID"**: Opens customization form
3. **Upload Photo**: Add your profile picture
4. **Fill Details**: Enter username, select Discord role, etc.
5. **Generate ID**: Create your animated Expressive ID
6. **Download**: Save your ID as PNG image

## 📊 Quiz Content

### Question Topics
- Fluent's blended execution technology
- Virtual machine integration (Wasm, EVM, SVM)
- Development tools and CLI
- Community programs and funding
- Technical architecture and features

### Scoring System
- **9-10/10**: Fluent Master 🏆
- **7-8/10**: Blended Expert ⭐
- **5-6/10**: Community Member 👥
- **3-4/10**: Fluent Learner 📚
- **0-2/10**: Newcomer 🌱

## 🎨 Customization

### Updating Questions
Edit the `allQuestions` array in the JavaScript section:

```javascript
const allQuestions = [
    {
        question: "Your question here?",
        options: ["Option A", "Option B", "Option C", "Option D"],
        correct: 1 // Index of correct answer (0-3)
    },
    // Add more questions...
];
```

### Styling Changes
- **Colors**: Modify CSS custom properties for theme colors
- **Background**: Update the SVG pattern in the body background
- **Animations**: Adjust keyframe animations for different effects

### Timer Settings
Change the timer duration by modifying:
```javascript
timeLeft = 6; // Change to desired seconds
```

## 🌟 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Ideas
- [ ] Add more quiz questions
- [ ] Implement leaderboard system
- [ ] Add social sharing for Expressive IDs
- [ ] Create difficulty levels
- [ ] Add sound effects and music
- [ ] Multi-language support

## 📱 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Internet Explorer (limited support)

## 🐛 Known Issues

- File upload requires modern browser with FileReader API
- Canvas download feature needs HTML5 support
- Some animations may be reduced on low-performance devices

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Acknowledgments

- Fluent Labs for the amazing blended execution technology
- The Fluent community for inspiration and feedback
- All beta testers who helped improve the quiz experience

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/fluent-quiz/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/fluent-quiz/discussions)
- **Community**: Join the Fluent Discord server

---

**Made with 💜 for the Fluent Community**

*Ready to get blended? Take the quiz and mint your Expressive ID today!* 🎨✨