# Be Protected Life Insurance Quote Form

A multi-step web form for collecting life insurance quote information, built with HTML, CSS (Tailwind), and JavaScript.

## Features

- 6-step form process: Smoking status, Date of Birth, Health events, Homeownership, Contact details, Success confirmation
- Data persistence using localStorage
- Responsive design with Tailwind CSS
- Form validation and error handling
- Integration with Zapier for lead submission
- Loading screen between steps 4 and 5

## File Structure

- `index.html` - Entry point, redirects to step1.html
- `step1.html` - Smoking question
- `step2.html` - Date of birth collection
- `step3.html` - Health events
- `step4.html` - Homeownership
- `loading.html` - Loading screen
- `step5.html` - Contact details and submission
- `success.html` - Confirmation page

## Setup

1. Clone or download the repository
2. Open `index.html` in a web browser
3. For local development, you can use a simple HTTP server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Deployment

This is a static site, suitable for hosting on GitHub Pages, Netlify, or any static host.

### GitHub Pages

1. Push to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Set source to main branch

## Configuration

- Zapier webhook URL in `step5.html` may need updating for production
- Branding and styling can be customized in the HTML files

## Technologies

- HTML5
- Tailwind CSS (via CDN)
- JavaScript (ES6+)
- Petite Vue for components
- Iconify for icons
- Fontshare for typography

## License

[Add license information]