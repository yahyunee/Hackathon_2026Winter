# 2026 Neuro-AI Grand Hackathon Website

🧠 Official website for the 2026 Neuro-AI Grand Hackathon - A collaborative neuroscience research sprint bringing together 5 labs and 40 researchers.

**Website:** https://yahyunee.github.io/Hackathon_2026Winter

---

## 📚 About

This is the official website for the 2026 Neuro-AI Grand Hackathon, an intensive 3-night, 4-day collaborative research sprint focused on cutting-edge neuroscience and AI research.

### Key Features
- 🌐 **Bilingual Support:** Full Korean and English content
- 📖 **Comprehensive Guide:** What is a hackathon, preparation requirements, and best practices
- 🔬 **Research Projects:** Details on all 10 team research topics
- 📚 **Tutorials:** Technical guides for data preprocessing, GPU setup, and more
- 🎨 **Responsive Design:** Works on desktop, tablet, and mobile devices

---

## 🏗️ Structure

```
Hackathon_2026Winter/
├── _config.yml           # Jekyll configuration
├── _layouts/             # HTML templates
│   └── default.html      # Main layout with navigation
├── assets/
│   └── css/
│       └── style.css     # Custom styling
├── en/                   # English content
│   ├── index.md          # Homepage
│   ├── overview.md       # What is a Hackathon?
│   ├── projects.md       # Research Projects
│   └── tutorials.md      # Tutorials & Guides
├── kr/                   # Korean content
│   ├── index.md          # 홈페이지
│   ├── overview.md       # 해커톤이란?
│   ├── projects.md       # 연구 프로젝트
│   └── tutorials.md      # 튜토리얼 & 가이드
└── 해커톤-2026-arpa.pdf   # Reference documentation
```

---

## 🚀 Getting Started

### Prerequisites
- Git
- Ruby (version 2.7 or higher)
- Jekyll

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yahyunee/Hackathon_2026Winter.git
   cd Hackathon_2026Winter
   ```

2. **Install Jekyll** (if not already installed)
   ```bash
   gem install bundler jekyll
   ```

3. **Create a Gemfile**
   ```bash
   echo 'source "https://rubygems.org"
   gem "github-pages", group: :jekyll_plugins' > Gemfile
   ```

4. **Install dependencies**
   ```bash
   bundle install
   ```

5. **Run the local server**
   ```bash
   bundle exec jekyll serve
   ```

6. **View the site**
   - Open your browser and go to `http://localhost:4000/Hackathon_2026Winter/`

---

## 🌐 Deployment to GitHub Pages

### Initial Setup

1. **Create a new repository on GitHub**
   - Repository name: `Hackathon_2026Winter`
   - Make it public
   - Don't initialize with README (we already have one)

2. **Add remote and push**
   ```bash
   git remote add origin https://github.com/yahyunee/Hackathon_2026Winter.git
   git add .
   git commit -m "Initial commit: 2026 Neuro-AI Hackathon website"
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `(root)`
   - Click Save

4. **Wait a few minutes**
   - Your site will be available at: `https://yahyunee.github.io/Hackathon_2026Winter/`

### Updating the Site

```bash
# Make your changes
git add .
git commit -m "Update content"
git push
```

GitHub Pages will automatically rebuild and deploy your changes.

---

## 📝 Content Updates

### Adding Team Information
Edit `/en/projects.md` or `/kr/projects.md` and update the team cards with actual team leader names and research details.

### Updating Schedules
Modify the schedule tables in `/en/overview.md` and `/kr/overview.md` with specific dates and locations.

### Adding Tutorials
Add new tutorial sections to `/en/tutorials.md` or `/kr/tutorials.md`.

---

## 🎨 Customization

### Changing Colors
Edit `/assets/css/style.css` and modify the CSS variables:

```css
:root {
    --primary-color: #2c3e50;      /* Main navigation color */
    --secondary-color: #3498db;     /* Accent color */
    --accent-color: #e74c3c;        /* Highlight color */
}
```

### Modifying Navigation
Edit `/_layouts/default.html` to add or remove navigation links.

---

## 📋 Hackathon Information

### Event Details
- **Labs:** 5 research labs collaboration
- **Participants:** 40 researchers
- **Teams:** 10 research teams
- **Duration:** 3 nights, 4 days
- **Focus:** Neuroscience & AI research

### Research Topics
1. Emotion Contextualized Perception
2. Swift v3 Development
3. fMRI VQ-VAE Training
4. Affect-Contextualized Cognition
5. Pretrained ECoG Model
6. 4D Brain Transformer
7. Benchmarking Study Design
8. GPU Programming Optimization
9. Genetic Transformer
10. TBD

---

## 🤝 Contributing

This is a private hackathon website. If you're a participant and want to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📞 Contact

For questions about the hackathon or this website:
- **GitHub:** [@yahyunee](https://github.com/yahyunee)
- **Repository:** [Hackathon_2026Winter](https://github.com/yahyunee/Hackathon_2026Winter)

---

## 📄 License

This project is for the 2026 Neuro-AI Grand Hackathon and is intended for educational and research purposes.

---

## 🙏 Acknowledgments

- Built with [Jekyll](https://jekyllrb.com/)
- Hosted on [GitHub Pages](https://pages.github.com/)
- Designed for the Neuro-AI research community

---

**Ready to accelerate neuroscience research? See you at the hackathon! 🚀**
