# Kavana D R - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and contact information as a Computer Science student passionate about full-stack development.

## Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Dark/Light Mode**: Toggle between themes with persistent preference
- **Responsive**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth scroll, animations, and hover effects
- **Contact Form**: Functional contact form (demo mode)
- **Resume Download**: One-click resume download functionality
- **Project Showcase**: Display of featured projects with tech stacks

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript**: ES6+ for interactivity and dynamic features
- **Font Awesome**: Icons for visual enhancement
- **Google Fonts**: Inter font family for typography

## Project Structure

```

portfolio/
├── index.html          # Main HTML file
├── styles.css          # Styling with theme variables
├── script.js           # JavaScript functionality
└── README.md           # Project documentation

```

## How to Use Locally

1. **Clone or download** this repository
2. **Navigate** to the project folder
3. **Open `index.html`** in your web browser
4. **Explore** the portfolio website

## Deployment to GitHub Pages

### Option 1: Direct Upload
1. Create a new repository on GitHub named `KavanaDR2006.github.io`
2. Upload all three files (`index.html`, `styles.css`, `script.js`)
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://KavanaDR2006.github.io`

### Option 2: Using Git Commands
```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial portfolio commit"

# Add remote repository
git remote add origin https://github.com/KavanaDR2006/KavanaDR2006.github.io.git

# Push to GitHub
git push -u origin main
```

## Customization Guide

### Update Personal Information

1. **Name & Title**: Modify the `<h1>` and `<p>` tags in `index.html`
1. **Bio**: Update the hero description text
1. **Email & GitHub**: Replace placeholder links and email addresses
1. **Projects**: Edit the projects section with your actual projects
1. **Skills**: Modify the skills cards to match your expertise

### Update Resume

The resume download is currently a text file. To update:

- Modify the `resumeContent` variable in `script.js` (line ~25)
- Or replace with actual PDF download functionality

### Color Scheme

Modify the CSS variables in `styles.css` to change colors:

```
:root {
    --accent: #4d6bfe;  /* Change this to your preferred color */
    /* ... other variables ... */
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Future Enhancements

- Add backend integration for contact form
- Implement blog section
- Add project filtering by category
- Integrate with GitHub API to show live repositories
- Add more interactive animations

## Contact

- **Email**: kavanadr01@gmail.com
- **GitHub**: [github.com/Kavanadr2006](https://github.com/Kavanadr2006)

## License

© 2024 Kavana D R. All rights reserved.

**Live Demo**: [Your GitHub Pages URL]

