# Production-Ready n8n on AWS - Documentation Website

A beautiful, modern documentation website for deploying n8n workflow automation on AWS EC2 with Docker, PostgreSQL, Nginx, and SSL.

![n8n AWS Guide](https://img.shields.io/badge/n8n-AWS%20Guide-ff6d5a?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- **Modern UI/UX** - Clean, professional design with smooth animations
- **Dark/Light Mode** - Automatic theme detection with manual toggle
- **Copy to Clipboard** - One-click code copying for all commands
- **Responsive Design** - Works beautifully on desktop, tablet, and mobile
- **Progress Indicator** - Reading progress bar as you scroll
- **Smart Navigation** - Sticky sidebar with active section highlighting
- **Accessible** - Keyboard navigation support and semantic HTML

## 🚀 Quick Start

Simply open `index.html` in your browser:

```bash
# Clone the repo (if applicable)
git clone <repository-url>
cd n8n-aws-guide

# Open in browser
open index.html
# Or on Linux
xdg-open index.html
```

Or use a local server for best experience:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📁 Project Structure

```
n8n-aws-guide/
├── index.html      # Main HTML document
├── styles.css      # All styling (CSS variables, responsive design)
├── script.js       # Interactive functionality
└── README.md       # This file
```

## 🎨 Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --accent-primary: #ff6d5a;
    --accent-secondary: #ff8c7a;
    /* ... other variables */
}
```

### Content

All guide content is in `index.html`. Each step is organized in sections with the class `step-section`.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, and CSS Variables
- **Vanilla JavaScript** - No dependencies, pure JS for interactivity
- **Google Fonts** - Inter (body) and JetBrains Mono (code)

## 📄 License

This project is open source and available for personal and commercial use.

## 🙏 Credits

- [n8n](https://n8n.io) - The workflow automation tool
- [Inter Font](https://rsms.me/inter/) - Beautiful typeface by Rasmus Andersson
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) - Developer-friendly monospace font

---

**Made with ❤️ for the n8n community**
