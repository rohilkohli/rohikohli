# GitHub Pages Setup Instructions

This repository now includes a modern, dynamic portfolio page that can be hosted on GitHub Pages.

## Automatic Deployment

The repository includes a GitHub Actions workflow (`.github/workflows/pages.yml`) that automatically deploys the site to GitHub Pages when you push to the `main` branch.

## Enable GitHub Pages

To enable GitHub Pages for this repository, follow these steps:

### Step 1: Enable GitHub Pages in Repository Settings

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. In the left sidebar, click on **Pages**
4. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"
   - This will use the workflow file to build and deploy your site

### Step 2: Verify Deployment

1. After merging the pull request to `main`, the workflow will automatically run
2. Go to the **Actions** tab to see the deployment progress
3. Once complete, your site will be available at: `https://rohilkohli.github.io/rohikohli/`

## Features of the Portfolio Page

✨ **Dynamic Elements**
- Typing animation that cycles through roles (Web Developer, UI/UX Designer, etc.)
- Smooth scrolling navigation
- Interactive hover effects on buttons and cards
- Parallax background effects

🎨 **Modern Design**
- Dark theme with purple/blue gradient accents
- Animated background with floating circles
- Responsive design for mobile and desktop
- Smooth transitions and animations

📊 **Content Sections**
- Hero section with animated greeting
- About section with personal information
- Skills showcase organized by categories
- GitHub statistics integration
- Social media links and contact section

## Local Development

To test the portfolio page locally:

```bash
# Start a simple HTTP server
python3 -m http.server 8080

# Open your browser to
http://localhost:8080/index.html
```

## Files Structure

- `index.html` - Main portfolio page with all sections
- `styles.css` - Modern CSS with animations and responsive design
- `script.js` - JavaScript for dynamic features and interactions
- `.github/workflows/pages.yml` - GitHub Pages deployment workflow

## Customization

To customize the portfolio:

1. **Update personal information** in `index.html`
2. **Modify colors** by changing CSS variables in `styles.css`
3. **Adjust animations** in `script.js` and `styles.css`
4. **Add/remove sections** by editing the HTML structure

Enjoy your new dynamic portfolio! 🚀
