# HabitTracker Marketing Website

This folder contains a complete marketing website for the HabitTracker app, including:

- **index.html** - Main landing page
- **support.html** - Support and FAQ page
- **privacy.html** - Privacy policy page
- **styles.css** - Complete stylesheet for all pages

## 📁 Folder Structure

```
Website/
├── index.html          # Main landing page
├── support.html        # Support & FAQ page
├── privacy.html        # Privacy policy page
└── styles.css          # Stylesheet for all pages
```

The website expects screenshots to be in a folder at: `../Screenshots/`

## 🖼️ Screenshot Requirements

Place your app screenshots in a `Screenshots` folder at the same level as the `Website` folder:

```
YourProject/
├── Website/
│   ├── index.html
│   ├── support.html
│   ├── privacy.html
│   └── styles.css
└── Screenshots/
    ├── screenshot1.png
    ├── screenshot2.png
    ├── screenshot3.png
    └── screenshot4.png
```

### Recommended Screenshot Specifications:
- Format: PNG with transparency or white background
- Resolution: iPhone screenshots (1170x2532 for iPhone 13 Pro or similar)
- Content suggestions:
  - **screenshot1.png**: Main habit list view with several habits
  - **screenshot2.png**: Habit detail view showing streaks and progress
  - **screenshot3.png**: Achievements/badges view
  - **screenshot4.png**: Settings or iCloud sync interface

## 🎨 Customization

### Colors
The website uses CSS custom properties (variables) defined in `styles.css`. To change colors, edit these values:

```css
:root {
    --primary-color: #007AFF;      /* Main blue color */
    --secondary-color: #5856D6;    /* Purple accent */
    --success-color: #34C759;      /* Green for success */
    /* ... more colors ... */
}
```

### App Store Link
Update the App Store download link in all three HTML files. Look for:

```html
<a href="https://apps.apple.com/app/habittracker" class="btn-large btn-primary">
```

Replace with your actual App Store URL when available.

### Contact Email
Update email addresses throughout the site:
- support@habittracker.app
- privacy@habittracker.app

Search and replace these with your actual support email addresses.

### App Icon
The website uses an emoji (⚡) as a placeholder for the app icon. To use your actual app icon:

1. Export your app icon as a PNG (e.g., `app-icon.png`)
2. Place it in the Website folder
3. Replace the emoji span in the navigation:

```html
<!-- Before -->
<span class="app-icon">⚡</span>

<!-- After -->
<img src="app-icon.png" alt="HabitTracker" class="app-icon">
```

4. Update the CSS for `.app-icon` to style the image properly.

## 🚀 Deployment

### Option 1: GitHub Pages
1. Create a repository on GitHub
2. Push the Website folder contents to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://yourusername.github.io/repository-name/`

### Option 2: Netlify
1. Sign up for a free Netlify account
2. Drag and drop the Website folder to Netlify
3. Your site will be deployed instantly with a custom URL
4. Optional: Connect a custom domain

### Option 3: Custom Hosting
Upload the contents of the Website folder to any web host that supports static HTML files.

## ✅ Pre-Launch Checklist

Before publishing your website:

- [ ] Replace all placeholder email addresses
- [ ] Add your actual App Store link
- [ ] Add your app screenshots to the Screenshots folder
- [ ] Customize colors to match your app's branding
- [ ] Update the app icon in the navigation
- [ ] Review the Privacy Policy and ensure it matches your app's actual privacy practices
- [ ] Test the website on mobile devices
- [ ] Test all navigation links
- [ ] Add your company/developer name to the footer if desired

## 📱 Responsive Design

The website is fully responsive and looks great on:
- Desktop computers (1200px and wider)
- Tablets (768px - 1200px)
- Mobile phones (320px - 767px)

Test the website at different screen sizes to ensure everything looks good.

## 🎯 Features Included

### Main Landing Page (index.html)
- Hero section with call-to-action
- Features showcase (6 key features)
- Screenshot carousel
- How it works (4 steps)
- Testimonials
- Download section
- Footer with links

### Support Page (support.html)
- Comprehensive FAQ organized by category:
  - Getting Started
  - Streaks & Progress
  - Achievements
  - iCloud Sync
  - Data & Privacy
  - Troubleshooting
  - In-App Purchases
- Contact section

### Privacy Policy (privacy.html)
- Complete privacy policy covering:
  - Data collection (or lack thereof)
  - iCloud sync
  - Firebase Analytics and Crashlytics
  - In-app purchases
  - International compliance (GDPR, CCPA)
  - User rights and control
  - Data security

## 🔧 Technical Notes

- No JavaScript required - pure HTML/CSS
- Uses modern CSS features (Grid, Flexbox, Custom Properties)
- Apple-style design with SF Pro font stack
- Optimized for performance with minimal dependencies
- SEO-friendly with proper meta tags
- Accessible with semantic HTML

## 📝 Updating Content

### Adding New Features
To add a new feature card to the main page, find the `.features-grid` section and add:

```html
<div class="feature-card">
    <div class="feature-icon-large">🎯</div>
    <h3>Your Feature Name</h3>
    <p>Feature description goes here.</p>
</div>
```

### Adding FAQ Items
To add new FAQ items to the support page:

```html
<div class="faq-item">
    <h3>Your Question Here?</h3>
    <p>Your answer here.</p>
</div>
```

### Changing Testimonials
Edit the testimonials in the `.testimonials-grid` section:

```html
<div class="testimonial-card">
    <div class="stars">⭐⭐⭐⭐⭐</div>
    <p class="testimonial-text">"Your testimonial text"</p>
    <p class="testimonial-author">- Name</p>
</div>
```

## 🆘 Need Help?

If you need to modify the website:
1. All styling is in `styles.css`
2. Search for specific text to find where to edit
3. The CSS is well-organized with clear section comments
4. Colors are defined as CSS variables at the top of `styles.css`

## 📄 License

This website template is part of your HabitTracker project. Customize and use it as needed for your app marketing.

---

**Good luck with your app launch! 🚀**
