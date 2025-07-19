# Personal Resume Website

A modern, responsive personal resume website designed for GitHub Pages deployment and custom domain publishing.

## Features

- **Responsive Design**: Looks great on all devices from mobile to desktop
- **Modern UI**: Clean, professional design with smooth animations
- **Easy Navigation**: Smooth scrolling to different sections
- **Mobile-Friendly**: Hamburger menu for smaller screens
- **Contact Form**: Ready-to-use contact form (requires backend integration)
- **Social Media Integration**: Links to all your professional profiles
- **SEO Ready**: Properly structured HTML for better search engine visibility

## Sections

1. **Hero**: Eye-catching introduction with your name, title, and a call-to-action
2. **About**: Personal bio and professional summary
3. **Experience**: Work history with company details and responsibilities
4. **Education**: Academic background and qualifications
5. **Skills**: Technical and professional skills with visual indicators
6. **Projects**: Showcase of your best work with descriptions and links
7. **Contact**: Form and alternative contact methods

## Deployment

### GitHub Pages

1. Create a GitHub repository named `username.github.io` (replace username with your GitHub username)
2. Push this code to the repository
3. Go to repository Settings > Pages
4. Select the main branch as the source
5. Your site will be published at `https://username.github.io`

### Custom Domain

1. Purchase a domain from a domain registrar
2. In your GitHub repository, go to Settings > Pages
3. Under "Custom domain", enter your domain name and save
4. Configure your domain's DNS settings:
   - Add an A record pointing to GitHub Pages IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add a CNAME record pointing to `username.github.io`

## Customization

### Personal Information

Edit the HTML file to replace placeholder text with your information:

- Name, title, and bio in the hero and about sections
- Work experience details
- Education history
- Skills (adjust the progress bars as needed)
- Project details and links
- Contact information and social media links

### Colors and Styling

The color scheme can be easily modified by changing the CSS variables at the top of the style.css file:

```css
:root {
  --primary-color: #4a89dc;
  --secondary-color: #5d9cec;
  --accent-color: #3bafda;
  --text-color: #333;
  --text-light: #666;
  --bg-color: #fff;
  --bg-light: #f5f7fa;
  --border-color: #e6e9ed;
  --success-color: #8cc152;
}
```

### Images

Replace the placeholder images with your own:

- Profile photo in the hero section
- Project thumbnails
- Any background images

## Technologies Used

- HTML5
- CSS3 (with CSS variables and flexbox/grid layouts)
- JavaScript (vanilla JS with no dependencies)

## Browser Support

This website is compatible with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use this template for your personal resume website.