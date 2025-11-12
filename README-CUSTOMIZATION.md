# Business Profile Website - Customization Guide

This is a fully customizable business profile website built with HTML, CSS, and JavaScript.

## Customization Instructions

### 1. Business Information

**File:** `public/business-profile.html`

- **Company Name**: Search for "YourBusiness" and replace with your company name (appears in navbar and footer)
- **Hero Section**: Edit lines 30-35 to change the main headline and tagline
- **Contact Details**: Update lines 199-218 with your actual address, phone, and email

### 2. Colors & Branding

**File:** `public/styles.css`

Edit the CSS variables at the top of the file (lines 1-14):

```css
:root {
    --primary-color: #2563eb;        /* Main brand color */
    --primary-dark: #1e40af;         /* Darker shade */
    --secondary-color: #0ea5e9;      /* Accent color */
    --text-dark: #1e293b;            /* Main text color */
    --text-light: #64748b;           /* Secondary text */
}
```

### 3. Content Sections

#### About Section
- **Location**: Lines 39-71 in `business-profile.html`
- Edit the company story, statistics, and replace the image URL

#### Services
- **Location**: Lines 73-139 in `business-profile.html`
- Add/remove service cards
- Update service titles, icons, and descriptions

#### Portfolio
- **Location**: Lines 141-169 in `business-profile.html`
- Replace project images and descriptions
- Add more portfolio items by copying the `portfolio-item` div structure

#### Testimonials
- **Location**: Lines 180-221 in `business-profile.html`
- Update client names, titles, and testimonial text
- Replace client photos with your own

### 4. Images

All images use Pexels stock photos. Replace these URLs with your own:

- **Hero Background**: Line 19 - main banner image
- **About Image**: Line 61
- **Portfolio Images**: Lines 149, 154, 159, 164
- **Testimonial Photos**: Lines 190, 201, 212

### 5. Social Media Links

**Location**: Lines 223-235 in `business-profile.html`

Update the `href="#"` attributes with your actual social media URLs.

### 6. Logo

Replace the text logo "YourBusiness" with:
- Custom text
- An image logo: `<img src="your-logo.png" alt="Logo" class="logo-img">`

### 7. Navigation Menu

**Location**: Lines 15-23 in `business-profile.html`

Add/remove menu items by editing the `nav-links` list.

### 8. Contact Form

The form currently shows an alert. To connect to a real backend:

**File:** `public/script.js` (lines 31-45)

Replace the alert with your form handling service (e.g., FormSpree, Netlify Forms, or your own API).

## Deploying to Netlify

### Method 1: Drag & Drop
1. Visit [Netlify](https://app.netlify.com)
2. Sign up or log in
3. Drag the `public` folder onto the deploy area
4. Your site will be live!

### Method 2: Git Integration
1. Push your code to GitHub
2. Connect your repository to Netlify
3. Set build settings:
   - Build command: (leave empty)
   - Publish directory: `public`
4. Deploy!

## File Structure

```
public/
├── business-profile.html   # Main HTML file
├── styles.css              # All styling
├── script.js              # JavaScript functionality
├── _redirects             # Netlify redirects
```

## Features Included

- Fully responsive design
- Smooth scroll navigation
- Mobile menu
- Animated sections on scroll
- Contact form with validation
- Modern, professional design
- SEO-friendly structure
- Fast loading times

## Support

For issues or questions, consult the HTML, CSS, and JavaScript files. All code is well-structured and commented for easy understanding.