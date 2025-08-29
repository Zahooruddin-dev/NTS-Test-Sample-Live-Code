# 🎯 NTS ICS Sample Test - Interactive Platform

A comprehensive web-based testing platform for NTS (National Testing Service) ICS Computer Science Group practice tests. This interactive site replicates the official NTS testing experience with 90 carefully curated questions from authentic sample papers.

![Test Platform Preview](https://img.shields.io/badge/Questions-90-blue) ![Sections](https://img.shields.io/badge/Sections-4-green) ![Time](https://img.shields.io/badge/Duration-120%20mins-orange) ![Mobile](https://img.shields.io/badge/Mobile-Friendly-purple)

## 🚀 **Live Demo**
🔗 [**Try the Test Now**](https://zahooruddin-dev.github.io/nts-test-site/)

## 📋 **Features**

### ✅ **Complete Test Experience**
- **90 Questions** from authentic NTS ICS sample paper
- **4 Major Sections**: Verbal Ability, Analytical Reasoning, Quantitative Reasoning, Subject Knowledge
- **120-minute timer** with real-time countdown
- **Auto-submit** when time expires

### 🎨 **Modern UI/UX**
- Clean, professional interface
- Smooth animations and transitions
- Progress tracking with visual indicators
- Mobile-responsive design
- Gradient backgrounds and modern styling

### 📊 **Comprehensive Results**
- **Detailed score breakdown**
- **Section-wise performance** analysis
- **Answer key** with correct vs your answers
- **Color-coded results** (Green: Correct, Red: Wrong, Gray: Unanswered)
- **Percentage calculation** and performance metrics

### 📱 **Cross-Platform Support**
- Works on desktop, tablet, and mobile devices
- Responsive design adapts to all screen sizes
- Touch-friendly interface for mobile users

## 🏗️ **Test Structure**

| Section | Questions | Topics Covered |
|---------|-----------|----------------|
| **Verbal Ability** | 20 | Sentence completion, analogies, antonyms, synonyms, reading comprehension |
| **Analytical Reasoning** | 20 | Logic puzzles, critical reasoning, assumptions, conclusions |
| **Quantitative Reasoning** | 20 | Mathematics, geometry, algebra, probability, statistics |
| **Subject Knowledge** | 30 | Physics (10), Computer Science (10), Mathematics (10) |

## 🛠️ **Technologies Used**

- **HTML5** - Structure and semantic markup
- **CSS3** - Modern styling with flexbox, grid, animations
- **JavaScript (ES6+)** - Interactive functionality and logic
- **Responsive Design** - Mobile-first approach
- **Local Storage** - Session management (memory-based)

## 🚀 **Quick Start**

### Option 1: Direct Use
1. **Clone the repository**
   ```bash
   git clone https://github.com/zahooruddin-dev/nts-test-site.git
   cd nts-test-site
   ```

2. **Open in browser**
   ```bash
   # Simply open the index.html file in your browser
   open index.html
   # or
   double-click index.html
   ```

### Option 2: Live Server (Recommended)
1. **Install Live Server extension** in VS Code
2. **Right-click** on `index.html`
3. **Select "Open with Live Server"**

### Option 3: Python Server
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Then visit: http://localhost:8000
```

## 📁 **Project Structure**

```
nts-test-site/
│
├── index.html              # Main HTML file with embedded CSS & JS
├── README.md              # This file
└── screenshots/           # Screenshots for documentation
    ├── start-screen.png
    ├── test-interface.png
    └── results-page.png
```

## 🎮 **How to Use**

1. **Start Test**: Click "Start Test" button on welcome screen
2. **Answer Questions**: Click on options to select your answers
3. **Navigate**: Use Previous/Next buttons to move between questions
4. **Track Progress**: Monitor your progress with the progress bar
5. **Submit**: Click "Submit Test" on the last question or let timer expire
6. **Review Results**: Analyze your performance and check answer key
7. **Retake**: Click "Take Test Again" to practice more

## 📊 **Answer Key & Scoring**

- **Correct Answer**: +1 point
- **Wrong Answer**: 0 points  
- **Unanswered**: 0 points
- All correct answers are based on the official NTS sample paper patterns
- Detailed answer key shows correct vs selected answers for each question

## 🔧 **Customization**

### Adding New Questions
```javascript
// Add to the questions array in index.html
{
    section: "Section Name",
    number: 91,
    text: "Your question text here?",
    options: ["Option A", "Option B", "Option C", "Option D"],
    correct: 0  // Index of correct answer (0-3)
}
```

### Modifying Timer
```javascript
let timeLeft = 7200; // 120 minutes in seconds
// Change to desired time (e.g., 3600 for 60 minutes)
```

### Styling Changes
- Modify CSS variables in the `<style>` section
- Customize colors, fonts, and layouts as needed

## 🤝 **Contributing**

Contributions are welcome! Please feel free to submit a Pull Request.

1. **Fork** the project
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

## 📝 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 **Author**

**Zahoor Uddin**
- GitHub: [@zahooruddin-dev](https://github.com/zahooruddin-dev)
- LinkedIn: [Connect with me]

## 🙏 **Acknowledgments**

- NTS (National Testing Service) for the original sample paper
- Modern web design inspirations from contemporary testing platforms
- Open source community for tools and resources

## 📞 **Support**

If you find this project helpful, please give it a ⭐️ on GitHub!

For support, issues, or feature requests, please [open an issue](https://github.com/zahooruddin-dev/nts-test-site/issues) on GitHub.

---

### 💡 **Pro Tips for Test Takers**

1. **Practice Regularly** - Use this platform for daily practice
2. **Time Management** - Keep track of time per section
3. **Review Mistakes** - Analyze wrong answers in the answer key
4. **Section Focus** - Identify weak areas and practice more
5. **Mock Tests** - Take multiple attempts to build confidence

---

**Happy Learning! 🚀📚**