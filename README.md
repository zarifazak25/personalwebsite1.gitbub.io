# Personal Website - GitHub Pages Ready

A simple, beginner-friendly personal website with Home, About, Portfolio, and Contact pages.

## 📁 Files Included

- `index.html` - Home page
- `about.html` - About Me page
- `portfolio.html` - Portfolio page
- `contact.html` - Contact page
- `styles.css` - Stylesheet for all pages

## 🎨 Customizing Your Website

### 1. Update Your Information

Replace the following placeholder text in each HTML file:

- **Your Name** - Replace everywhere with your actual name
- **[Your interests/field]** - Add your professional interests
- **[hobbies/activities]** - Add your hobbies
- **Email, LinkedIn, GitHub, Twitter** - Update with your actual links

### 2. Add Your Projects (portfolio.html)

- Replace "Project Title 1, 2, 3, 4" with your actual project names
- Update project descriptions
- Link the "View Project" buttons to your actual projects
- You can add project images by replacing the placeholder divs

### 3. Customize Colors (styles.css)

At the top of `styles.css`, you'll find color variables you can easily change:

```css
--primary-color: #4a90e2;      /* Main blue color */
--secondary-color: #2c3e50;    /* Dark gray for headers */
--text-color: #333;            /* Main text color */
```

Just change these hex codes to your preferred colors!

## 🚀 Deploying to GitHub Pages

### Step 1: Create a GitHub Account
If you don't have one, sign up at [github.com](https://github.com)

### Step 2: Create a New Repository

1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
4. Make it **Public**
5. Click "Create repository"

### Step 3: Upload Your Files

**Option A: Upload via GitHub Website (Easiest for beginners)**

1. On your new repository page, click "uploading an existing file"
2. Drag and drop ALL your HTML and CSS files
3. Scroll down and click "Commit changes"

**Option B: Using Git (if you're comfortable with command line)**

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/your-username.github.io.git
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository settings
2. Scroll down to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

### Step 5: View Your Website!

Your website will be live at: `https://your-username.github.io`

It may take a few minutes to deploy for the first time.

## 📝 Important Notes

### Contact Form
The contact form on the contact page won't work by default on GitHub Pages. To make it work, you have two options:

1. **Use Formspree (Recommended for beginners)**
   - Sign up at [formspree.io](https://formspree.io)
   - Get your form endpoint
   - Replace `<form action="#"` with `<form action="https://formspree.io/f/YOUR_FORM_ID"`

2. **Use Netlify Forms** (requires hosting on Netlify instead)
   - Add `netlify` attribute to your form
   - Deploy to Netlify instead of GitHub Pages

### Adding Images

To add your own images:

1. Create an `images` folder in your repository
2. Upload your images to this folder
3. Reference them in HTML like: `<img src="images/your-photo.jpg" alt="Your Name">`

## 🎯 Next Steps

- Add your own professional photo to the About page
- Include screenshots of your actual projects in the Portfolio
- Link to your real social media profiles
- Customize the colors to match your personal brand
- Add more pages if needed (just copy an existing HTML file and modify it)

## 💡 Tips for Beginners

- Always test your changes locally by opening the HTML files in your browser
- Make small changes one at a time
- Use GitHub's edit feature to make quick changes online
- Don't be afraid to experiment - you can always undo changes!

## 🆘 Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML & CSS Tutorial](https://www.w3schools.com)
- [Markdown Guide](https://www.markdownguide.org) (for editing this README)

---

Good luck with your website! 🎉
