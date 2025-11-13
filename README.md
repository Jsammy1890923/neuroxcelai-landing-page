# NeuroXcelAi Landing Page

Professional launch page for NeuroXcelAi — an AI-powered executive brief generation service (C-TaaS). Built with Tailwind CSS.

## Overview

NeuroXcelAi is a cutting-edge C-TaaS (Content Transformation as a Service) that transforms complex business data into actionable executive briefs using advanced AI technology combined with human expertise. This landing page showcases the service's features, pricing, and value proposition.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Tailwind CSS**: Utility-first CSS framework via CDN (no build process required)
- **Modern UI**: Clean, professional design with smooth animations
- **GitHub Pages Ready**: Static site optimized for GitHub Pages deployment
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Accessible**: WCAG compliant with proper focus states and semantic markup

## Project Structure

```
neuroxcelai-landing-page/
├── index.html          # Main landing page
├── styles/
│   └── styles.css      # Custom CSS styles
├── README.md           # This file
├── LICENSE             # MIT License
└── .gitignore          # Git ignore rules
```

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/Jsammy1890923/neuroxcelai-landing-page.git
   cd neuroxcelai-landing-page
   ```

2. Open `index.html` in your web browser:
   - **Option 1**: Double-click `index.html` to open in your default browser
   - **Option 2**: Use a local development server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (with npx)
     npx serve
     
     # Using PHP
     php -S localhost:8000
     ```

3. View the site at `http://localhost:8000` (if using a local server)

### Customization

#### Updating Colors
Edit the Tailwind config in `index.html`:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#3b82f6',    // Change primary color
                secondary: '#1e40af',  // Change secondary color
                accent: '#06b6d4',     // Change accent color
            }
        }
    }
}
```

#### Modifying Content
All content is in `index.html`. Update the text, links, and sections as needed.

#### Adding Custom Styles
Add your custom CSS to `styles/styles.css` for styles that extend Tailwind's utility classes.

## Deployment

### GitHub Pages

This site is configured for GitHub Pages deployment:

1. Go to your repository settings
2. Navigate to **Pages** section
3. Under **Source**, select the branch (e.g., `main`) and root directory `/`
4. Click **Save**
5. Your site will be available at `https://jsammy1890923.github.io/neuroxcelai-landing-page/`

### Other Hosting Platforms

Since this is a static site, you can deploy it to:
- **Netlify**: Drag and drop the folder or connect your GitHub repository
- **Vercel**: Import your GitHub repository
- **Cloudflare Pages**: Connect your GitHub repository
- **AWS S3**: Upload files to an S3 bucket configured for static hosting
- **Any static hosting service**: Upload the files via FTP/SFTP

## Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Custom CSS**: Additional styling in `styles/styles.css`
- **SVG Icons**: Inline SVG for crisp, scalable icons

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

This is a landing page project. If you'd like to suggest improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please visit the contact section on the landing page or open an issue in this repository.

---

**Built with ❤️ using Tailwind CSS**
