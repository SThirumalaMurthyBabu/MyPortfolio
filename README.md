# STMB - Portfolio Website

A highly professional, feature-rich portfolio website for Aspiring Robotics Engineer.

## 🚀 Features

- **Particle Background Animation** - Interactive canvas-based particle system with connection lines
- **Typing Effect** - Dynamic role typing animation in hero section
- **Dark/Light Mode Toggle** - Theme switching with localStorage persistence
- **Custom Cursor** - Animated dot cursor with hover effects (desktop only)
- **Scroll Animations** - Intersection Observer based reveal animations
- **Animated Skill Bars** - Progress bars that animate on scroll
- **Live Stats Counter** - Animated counting statistics
- **Project Filtering** - Filter projects by category (ROS 2, Computer Vision, Embedded)
- **Project Modals** - Detailed project view with features list
- **GitHub Activity Graph** - Contribution-style activity visualization
- **Responsive Design** - Fully mobile-optimized with hamburger menu
- **Contact Form** - Interactive form with validation states
- **Back to Top Button** - Appears after scrolling
- **Smooth Scrolling** - All navigation links smooth scroll to sections
- **Loading Screen** - Animated loader on page entry
- **Parallax Effects** - Subtle parallax on hero section

## 📁 File Structure

```
portfolio/
├── index.html      # Main HTML file
├── style.css       # All styles (responsive, dark/light mode)
├── script.js       # All JavaScript (interactivity, animations)
├── Murthy.jpeg      # Your profile photo (ADD THIS!)
└── Murthy_Resume    # Your resume (ADD THIS!)
```

## 🛠️ Setup Instructions

### 1. Add Your Profile Photo
- Copy your `abina.jpeg` from `/home/abinaabey/Downloads/` into this folder
- Make sure it's named exactly `abina.jpeg`
- Recommended size: 500x500px or larger, square aspect ratio

### 2. Add Your Resume
- Save your CV as `Abina_CV.pdf` in this folder
- The download button in the About section links to this file

### 3. Deploy to GitHub Pages

#### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and log in
2. Click the **+** icon → **New repository**
3. Name it `abinaabey2006.github.io` (this creates a user site)
   - OR name it anything (e.g., `portfolio`) for a project site
4. Make it **Public**
5. Click **Create repository**

#### Step 2: Upload Files
**Option A: Via Web Interface**
1. In your new repo, click **Add file** → **Upload files**
2. Drag and drop all files from this folder (including abina.jpeg and Abina_CV.pdf)
3. Click **Commit changes**

**Option B: Via Git Command Line**
```bash
cd portfolio/
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/abinaabey2006/abinaabey2006.github.io.git
git push -u origin main
```

#### Step 3: Enable GitHub Pages
1. Go to your repository **Settings**
2. Scroll down to **Pages** section (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Select **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait 2-5 minutes, then visit: `https://abinaabey2006.github.io`

## 🎨 Customization

### Changing Colors
Edit CSS variables in `style.css` under `:root`:
```css
--primary: #6366f1;    /* Main accent color */
--secondary: #06b6d4;  /* Secondary accent */
--accent: #f59e0b;     /* Highlight color */
```

### Adding New Projects
In `index.html`, copy a `.project-card` block and update:
- `data-category` attribute for filtering
- Project title, description, tags
- In `script.js`, add project details to `projectDetails` object

### Updating Social Links
Links are in multiple places:
- Hero section social icons
- Contact section social icons
- Footer social icons
- GitHub card section

Search for `github.com/abinaabey2006` and `linkedin.com/in/abina-abey-064857326` in all files to update.

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance Tips

- Compress `abina.jpeg` to under 200KB for faster loading
- Use WebP format if possible (update filename in HTML)
- The site is fully static - no backend required

## 📧 Contact

For any issues or updates, modify the files directly and push to GitHub.

---

**Built with ❤️ and 🤖 by STMB**
