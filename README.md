# Data Science Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript for showcasing data science and machine learning projects.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling and active section highlighting
- **Mobile-Friendly**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Beautiful project cards with hover effects
- **Skills Display**: Organized skill categories with icons
- **Resume Download**: Easy access to your resume

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles and responsive design
├── js/
│   └── script.js       # JavaScript functionality
├── images/
│   └── README.md       # Image requirements and guidelines
├── resume.pdf          # Your resume file (add this)
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Clone or Download** this repository to your local machine
2. **Add Your Images**:
   - Add your profile photo as `images/profile-placeholder.jpg`
   - Add project screenshots as `images/project1-placeholder.jpg`, etc.
   - See `images/README.md` for detailed image requirements
3. **Add Your Resume**: Place your resume as `resume.pdf` in the root directory
4. **Customize Content**: Edit `index.html` to replace placeholder text with your information
5. **Open in Browser**: Double-click `index.html` or open it in your preferred browser

## 🎨 Customization Guide

### Personal Information
Edit the following sections in `index.html`:

- **Hero Section**: Update name, title, and description
- **About Section**: Replace placeholder text with your bio
- **Skills**: Modify the skills list to match your expertise
- **Projects**: Update project titles, descriptions, and links
- **Contact**: Replace email and social media links

### Styling
Modify `css/style.css` to customize:

- **Colors**: Change the color scheme by updating CSS variables
- **Fonts**: Replace Google Fonts link or modify font-family
- **Layout**: Adjust spacing, grid layouts, and responsive breakpoints
- **Animations**: Modify transition effects and hover states

### Functionality
Edit `js/script.js` to customize:

- **Form Handling**: Modify contact form submission logic
- **Animations**: Adjust scroll reveal effects
- **Navigation**: Customize mobile menu behavior

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: 1200px+ (full layout with side-by-side sections)
- **Tablet**: 768px-1199px (adjusted grid layouts)
- **Mobile**: <768px (stacked layout with hamburger menu)

## 🎯 Key Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Me**: Personal story and key statistics
3. **Skills**: Organized by categories (Programming, Data Science, Tools)
4. **Projects**: Showcase of your best work with links to GitHub
5. **Resume**: Download link and brief overview
6. **Contact**: Contact form and social media links

## 🔧 Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and animations
- **Font Awesome**: Icons for skills and social links
- **Google Fonts**: Inter font family for modern typography

## 📝 Content Guidelines

### Projects Section
For each project, include:
- **Title**: Clear, descriptive project name
- **Description**: 2-3 sentences explaining the project and outcomes
- **Technologies**: Key tools and frameworks used
- **Links**: GitHub repository and live demo (if available)

### Skills Section
Organize skills into categories:
- **Programming Languages**: Python, R, SQL, etc.
- **Data Science & ML**: Pandas, Scikit-learn, TensorFlow, etc.
- **Tools & Platforms**: Git, AWS, Docker, etc.

## 🚀 Deployment

### GitHub Pages (Free)
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify (Free)
1. Drag and drop your portfolio folder to Netlify
2. Get a custom domain and HTTPS automatically
3. Enable form handling for the contact form

### Vercel (Free)
1. Connect your GitHub repository to Vercel
2. Automatic deployments on every push
3. Custom domain and analytics included

## 📞 Contact Form Setup

The contact form currently shows a success message. To make it functional:

1. **Netlify Forms**: Add `netlify` attribute to the form
2. **Formspree**: Replace form action with Formspree endpoint
3. **EmailJS**: Integrate EmailJS for client-side email sending
4. **Backend**: Create a simple backend API to handle form submissions

## 🎨 Color Scheme

Current color palette:
- **Primary Blue**: #2563eb
- **Secondary Yellow**: #fbbf24
- **Dark Gray**: #1f2937
- **Light Gray**: #f8fafc
- **Text Gray**: #4b5563

## 📈 Performance Tips

1. **Optimize Images**: Compress images to reduce file sizes
2. **Minify CSS/JS**: Use minified versions for production
3. **Lazy Loading**: Implement lazy loading for images
4. **CDN**: Use CDN for external resources (Font Awesome, Google Fonts)

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements that could benefit others, consider submitting a pull request!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Unsplash for placeholder images
- The open-source community for inspiration

---

**Happy coding! 🚀**

If you have any questions or need help customizing your portfolio, feel free to reach out! 