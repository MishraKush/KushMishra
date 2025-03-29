# Kush Mishra - Professional Consulting Website

A modern, responsive website showcasing Kush Mishra's professional consulting services in strategy, management, and IT.

## Features

- **Responsive Design**: Works on all device sizes
- **Dark Mode**: Toggleable dark/light theme
- **Five Complete Pages**:
  - Homepage with hero section
  - About page with professional journey
  - Services page with consulting offerings
  - Experience page with timeline
  - Contact page with form
- **Modern UI**:
  - Tailwind CSS for styling
  - Font Awesome icons
  - Google Fonts typography
  - Smooth transitions and animations

## Technologies Used

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (for theme toggle and form handling)
- Font Awesome (icons)
- Google Fonts (Inter font family)

## Deployment

This is a static website that can be deployed to any web hosting service:

### Option 1: Netlify
1. Push the repository to GitHub/GitLab
2. Create a new site in Netlify and connect your repository
3. Set the build command to empty (no build needed)
4. Set publish directory to `/` (root)
5. Deploy!

### Option 2: Vercel
1. Push the repository to GitHub/GitLab
2. Create a new project in Vercel and import your repository
3. Configure as a static site
4. Deploy!

### Option 3: GitHub Pages
1. Push the repository to GitHub
2. Go to Settings > Pages
3. Set source to deploy from main branch
4. Set root directory
5. Save and wait for deployment

## Local Development

1. Clone the repository
2. Run a local server:
   ```bash
   python3 -m http.server 8000
   ```
3. Open http://localhost:8000 in your browser

## Customization

To modify content:
- Update text in the HTML files
- Change colors in Tailwind classes (search for `blue-600`, `gray-800`, etc.)
- Add/remove sections as needed

To add new pages:
1. Create a new HTML file
2. Copy the basic structure from existing pages
3. Add to navigation in all pages