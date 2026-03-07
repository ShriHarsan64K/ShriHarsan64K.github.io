# 🌌 Shri Harsan M - Portfolio Website

A stunning, space-themed portfolio website featuring a realistic Milky Way background, rotating Earth with Saturn-style rings, and beautiful 3D visualizations.

![Portfolio Preview](https://img.shields.io/badge/Portfolio-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?logo=three.js&logoColor=white)

## ✨ Features

### 🎨 Visual Design
- **Realistic Milky Way Background** - 45,000+ stars with natural color variations (blue, white, yellow, orange, red)
- **Dark Dust Patches** - Authentic cosmic dust lanes for realistic depth
- **Nebula Clouds** - Colorful pinkish, bluish, and golden nebula effects
- **Rotating Earth Globe** - Realistic day/night shader with city lights
- **Saturn-Style Rings** - Multiple ring segments orbiting the Earth
- **6,000+ Background Stars** - Positioned behind Earth for proper depth
- **Smooth Animations** - Parallax effects and gentle rotations

### 🛠️ Technical Features
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Three.js 3D graphics
- ✅ Custom GLSL shaders for Earth rendering
- ✅ Particle systems for stars and rings
- ✅ Smooth scroll animations
- ✅ Custom cursor effects
- ✅ Working contact form with email integration
- ✅ Clean, semantic HTML5
- ✅ Modern CSS3 with custom properties
- ✅ Vanilla JavaScript (no frameworks)

### 📧 Contact Form
- Integrated with **FormSubmit** for email delivery
- Messages sent directly to: shriharsang@gmail.com
- No backend required - works instantly!
- Spam protection included

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create Repository
1. Go to [github.com/new](https://github.com/new)
2. Repository name: `ShriHarsan64K.github.io`
3. Set to **Public**
4. Click **Create repository**

### Step 2: Upload Files
```bash
git clone https://github.com/ShriHarsan64K/ShriHarsan64K.github.io.git
cd ShriHarsan64K.github.io
# Copy index.html to this folder
git add .
git commit -m "Initial portfolio deployment"
git push origin main
```

### Step 3: Enable GitHub Pages
1. Go to **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **root**
4. Click **Save**

### Step 4: Go Live! 🎉
Your portfolio will be live at: **https://ShriHarsan64K.github.io**
(Wait 2-3 minutes for first deployment)

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Main HTML file (entire website)
├── README.md          # This file
├── LICENSE            # MIT License
└── .gitignore         # Git ignore rules
```

## 🎯 Sections

1. **Hero** - Introduction with Milky Way background
2. **About** - Skills showcase with icons
3. **Experience** - Timeline of work history
4. **Projects** - Featured work with tech tags
5. **Achievements** - Awards and certifications
6. **Skills** - Technical expertise categorized
7. **Contact** - Email form with rotating Earth

## 🔧 Customization

### Update Personal Information

Search and replace in `index.html`:

**Name & Title:**
```html
Line ~250: <div class="nav-logo">Shri<em>Harsan</em></div>
Line ~260: <h1 class="hero-h1">Data Scientist &<br/><span class="gold">AI Engineer</span></h1>
```

**Social Links:**
```html
Line ~480-490: Update footer social links
```

**Email:**
```html
Line ~453: action="https://formsubmit.co/YOUR_EMAIL@gmail.com"
```

### Add/Remove Projects

Find the projects section around line ~325 and copy/modify:
```html
<div class="proj-card fu">
  <div class="proj-badge">YOUR BADGE</div>
  <div class="proj-title">Project Name</div>
  <p class="proj-desc">Description...</p>
  <div class="proj-tags">
    <span class="ptag t-py">Python</span>
    <!-- Add more tags -->
  </div>
  <a href="GITHUB_LINK" class="proj-link">View Code</a>
</div>
```

### Modify Colors

Change CSS variables (Line ~12):
```css
:root{
  --gold:#c9a96e;      /* Primary accent */
  --gold2:#e2c48a;     /* Secondary accent */
  --bg:#080808;        /* Background */
  --text:#f2f2f2;      /* Text color */
}
```

## 🌟 Advanced Features

### Three.js Scenes

**Milky Way (Hero Section):**
- 45,000 particles with realistic colors
- Dark dust patches for depth
- Nebula clouds with varied colors
- Subtle rotation and parallax

**Earth Globe (Contact Section):**
- Day/night shader with city lights
- Realistic continents and oceans
- Atmospheric glow layers
- 6,000 background stars
- 4 Saturn-style ring segments
- Smooth rotation

### Contact Form Setup

The form uses **FormSubmit.co** (free service):

1. **First submission**: You'll get a verification email
2. Click the link to activate
3. All future messages will arrive instantly!

**Features:**
- No backend needed
- Spam protection
- Email notifications
- Table format for easy reading

## 📱 Mobile Responsive

Tested and optimized for:
- ✅ iPhone (375px)
- ✅ iPad (768px)
- ✅ Desktop (1920px+)
- ✅ 4K displays

## 🧪 Local Testing

**Option 1: Direct Open**
```bash
# Just open the file
open index.html  # Mac
start index.html # Windows
```

**Option 2: Local Server**
```bash
# Python
python -m http.server 8000

# Node.js
npx serve

# Then visit http://localhost:8000
```

## 🎨 Design Philosophy

### Cosmic Theme
- Deep space aesthetic with realistic Milky Way
- Gold accents (#c9a96e) for elegance
- Dark background for reduced eye strain
- Subtle animations for engagement

### Typography
- **Nunito** - Modern, friendly headers
- **Nunito Sans** - Clean, readable body text
- **DM Mono** - Technical tags and labels

### Performance
- Optimized particle counts for smooth 60 FPS
- Efficient shader compilation
- Minimal DOM manipulation
- GPU-accelerated animations

## 📊 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

*Note: Three.js requires WebGL support*

## 🔒 Privacy & Security

- No tracking scripts
- No cookies
- No analytics (unless you add them)
- Contact form uses HTTPS
- Email protected by FormSubmit

## 🤝 Contributing

This is a personal portfolio, but feel free to:
- Fork and customize for your own use
- Report issues
- Suggest improvements

## 📄 License

MIT License - See LICENSE file for details

## 🙏 Acknowledgments

- **Three.js** - 3D graphics library
- **FormSubmit** - Free form backend
- **Google Fonts** - Nunito & DM Mono
- **Devicon** - Technology logos

## 📞 Contact

- **Email**: shriharsang@gmail.com
- **GitHub**: [@ShriHarsan64K](https://github.com/ShriHarsan64K)
- **Portfolio**: https://ShriHarsan64K.github.io

---

**Built with ❤️ using HTML5, CSS3, JavaScript, and Three.js**

*Last Updated: January 2025*
