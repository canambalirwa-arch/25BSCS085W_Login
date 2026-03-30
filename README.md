# Calvin's Portfolio

##  Project Info

- Project Name: Portfolio with Login
- Name: NAMBALIRWA CALVIN
- Registration Number: 25BSCS085W
- Technologies Used: HTML5, CSS3, JavaScript, PHP, MySQL

##  Features

- **Modern Design**: NYC-inspired dark theme with gradient accents
- **Fully Responsive**: Mobile, tablet, and desktop optimized
- **GitHub Pages Ready**: Pure static HTML/CSS/JS - no server required
- **Smooth Animations**: Creative transitions and hover effects
- **Professional Profile**: Detailed introduction section for your resume/CV
- **Contact Form**: Interactive contact section
- **Social Links**: Easy integration with social media profiles

##  File Structure

```
├── index.html          # Main portfolio page
├── db_connect.php      # Centralized MySQL connection settings
├── styles.css          # All styling (NYC theme)
├── script.js           # Interactive features
├── README.md           # This file
├── database.sql        # Create tables + sample data
└── assets/             # Add images/icons here
```

##  Deployment

### How to Run Locally

1. Install XAMPP (Windows) or LAMP/MAMP (Mac/Linux).
2. Copy the project folder into your web root:
   - Windows: `C:\xampp\htdocs\carlvin`
   - Mac/Linux: `/Applications/MAMP/htdocs/carlvin` or `/var/www/html/carlvin`
3. Start Apache and MySQL services.
4. Open browser and go to: `http://localhost/carlvin/index.html` for portfolio, or `http://localhost/carlvin/bakery.php` for bakery demo.
5. Edit `db_connect.php` with your database credentials:
   - `host`, `user`, `password`, `dbname`

### Database Import Instructions

1. Open phpMyAdmin (`http://localhost/phpmyadmin`).
2. Create a database (e.g., `carlvin_bakery`).
3. Select the database and go to the `Import` tab.
4. Choose `database.sql` from this project and click `Go`.
5. Verify table `tbl_bakery` is created and sample rows inserted.

### Deploy to GitHub Pages

1. **Create a GitHub repository** named `username.github.io`
2. **Push this folder** to the repository
3. **Your site will be live** at `https://username.github.io`

Or for a project repository:
1. Fork/create a repository
2. Push files to `gh-pages` branch
3. Enable Pages in repository settings
4. Access at `https://username.github.io/repository-name`

##  Customize Your Profile

Edit `index.html` to add your information:

- **Name & Title**: Update in navbar and hero section
- **Bio**: Replace "About Me" paragraph with your background
- **Skills**: Modify the skill cards to match your expertise
- **Contact Info**: Update email, phone, location in contact section
- **Social Links**: Add your GitHub, LinkedIn, Twitter URLs
- **Stats**: Update years of experience, projects completed, etc.

 Key Sections

### Hero Section
Your main introduction with CTA buttons

### About Section
Personal biography and key statistics

### Skills Section
Technical skills in card format

 Contact Section
Contact form and social links

 Customization

 Change Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-dark: #0f0f0f;
    --accent-blue: #0099ff;
    --accent-purple: #9d4edd;
    /* ... other colors ... */
}
```

 Add Images
Place images in an `assets/` folder and reference them in HTML:

```html
<img src="assets/profile.jpg" alt="Profile picture">
```

Update Social Links
Find the social links section and update URLs:

```html
<a href="https://github.com/yourusername" class="social-icon">
    <i class="fab fa-github"></i>
</a>
```

---

 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

 License

Feel free to use this template for your own portfolio.

 Credits

- Font Awesome icons for social media and skill icons
- Modern CSS Grid and Flexbox for responsive layout

---

**Good luck with your portfolio! 🚀**



