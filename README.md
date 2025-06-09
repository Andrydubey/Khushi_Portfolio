# Full Stack Developer Portfolio

A modern, responsive portfolio website for a Full Stack Developer built with HTML, CSS, and JavaScript.

## Features

- Fully responsive design (mobile-first approach)
- Dark/light theme toggle with localStorage persistence
- Smooth scrolling and animations
- Interactive project cards
- Contact form with validation
- Modern UI with clean aesthetics

## Sections

1. **Hero Section** - Introduction with call-to-action buttons
2. **About Section** - Personal information and resume download
3. **Skills Section** - Technical skills categorized by area
4. **Projects Section** - Showcase of development projects
5. **Contact Section** - Contact form and personal contact information
6. **Footer** - Social media links and copyright information

## Technologies Used

- HTML5
- CSS3 (with CSS variables for theming)
- JavaScript (ES6+)
- Font Awesome icons
- Google Fonts

## Setup and Usage

1. Clone the repository
2. Open `index.html` in your browser

## Customization

### Changing Personal Information

- Edit the text in `index.html` to update your name, bio, and contact information
- Replace `images/profile.jpg` with your own profile picture
- Update project information and images in the Projects section

### Changing Colors and Theme

- Edit the CSS variables in the `:root` selector in `css/style.css` to change the color scheme
- Modify the `.dark-theme` variables to customize the dark mode appearance

### Adding More Projects

To add more projects, copy and paste the following HTML structure in the projects grid:

```html
<div class="project-card">
    <div class="project-img">
        <img src="images/your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description goes here...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
            <span>Technology 3</span>
        </div>
        <div class="project-links">
            <a href="#" class="btn small-btn"><i class="fas fa-globe"></i> Live Demo</a>
            <a href="#" class="btn small-btn"><i class="fab fa-github"></i> GitHub</a>
        </div>
    </div>
</div>
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For any questions or feedback, please reach out to:
- Email: your-email@example.com
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)
- GitHub: [Your GitHub Profile](https://github.com/yourusername) 