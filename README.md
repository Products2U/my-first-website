# My First Website

A simple, beautiful static website built with HTML, CSS, and JavaScript. This project is perfect for learning web development basics and understanding deployment.

## What's Inside

- **index.html** - The main HTML structure with sections for Home, About, Projects, and Contact
- **style.css** - Modern, responsive styling with gradient colors and smooth animations
- **script.js** - Interactive JavaScript features including smooth scrolling and form handling

## Features

- Responsive design that works on all devices
- Smooth scrolling navigation
- Interactive buttons and form
- Modern gradient design
- Fade-in animations
- Mobile-friendly navigation

## How to View Locally

1. Simply open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # If you have Python installed:
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## Deployment Options

### Option 1: GitHub Pages (Recommended for Beginners)

1. Create a GitHub account at https://github.com
2. Create a new repository (e.g., "my-first-website")
3. Upload your files or push via Git:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/my-first-website.git
   git push -u origin main
   ```
4. Go to repository Settings > Pages
5. Select "main" branch as source
6. Your site will be live at: `https://YOUR-USERNAME.github.io/my-first-website`

### Option 2: Netlify (Easiest, No Git Required)

1. Go to https://netlify.com
2. Sign up for a free account
3. Drag and drop your `my-first-website` folder onto the Netlify dashboard
4. Your site goes live instantly with a URL like: `https://random-name.netlify.app`
5. You can customize the domain name in settings

### Option 3: Vercel

1. Go to https://vercel.com
2. Sign up for a free account
3. Click "Add New Project"
4. Import your GitHub repository or upload files
5. Click "Deploy"
6. Your site will be live at: `https://my-first-website.vercel.app`

### Option 4: Render

1. Go to https://render.com
2. Sign up for a free account
3. Click "New Static Site"
4. Connect your GitHub repository
5. Deploy with one click

## Learning Resources

### HTML
- [MDN HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)

### CSS
- [MDN CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/CSS)
- [CSS Tricks](https://css-tricks.com/)

### JavaScript
- [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [JavaScript.info](https://javascript.info/)

## Next Steps

1. Customize the content with your own information
2. Add more sections or pages
3. Try adding new features like a dark mode toggle
4. Learn about CSS frameworks (Bootstrap, Tailwind)
5. Explore JavaScript libraries (React, Vue)

## Troubleshooting

**Site not loading styles?**
- Make sure `style.css` and `script.js` are in the same folder as `index.html`
- Check that the file names match exactly (case-sensitive)

**Deployment not working?**
- Ensure your main HTML file is named `index.html`
- Check that all files are in the root directory
- Wait a few minutes for changes to propagate

## License

Feel free to use this code for learning purposes!

---

Built with passion as part of my coding journey! 🚀
