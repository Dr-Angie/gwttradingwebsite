# GWT Trading Website

A professional website for GWT Trading, a white-label critical infrastructure services provider.

## Structure

```
gwt-website/
├── index.html              # Home page
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── main.js             # JavaScript functionality
├── images/
│   └── logo.png            # Company logo
├── pages/
│   ├── about.html          # About Us
│   ├── services.html       # Services Overview
│   ├── service-contracts.html
│   ├── capacity-support.html
│   ├── proreports.html     # ProReports™
│   ├── partner.html        # Partner With Us
│   ├── contact.html        # Contact form
│   ├── end-user-support.html
│   └── free-issue.html     # Free-Issue Equipment
├── netlify.toml            # Netlify configuration
└── README.md
```

## Deployment to Netlify

### Option 1: Drag & Drop
1. Go to [netlify.com](https://netlify.com) and sign up/log in
2. Drag the entire `gwt-website` folder to the Netlify dashboard
3. Your site will be live in seconds

### Option 2: GitHub Integration
1. Push this folder to a GitHub repository
2. Connect the repository to Netlify
3. Netlify will automatically deploy on each push

### Custom Domain Setup
1. In Netlify dashboard, go to Domain Settings
2. Add custom domain: `gwttrading.com.au`
3. Update your domain's DNS:
   - Add a CNAME record pointing to your Netlify subdomain
   - Or use Netlify DNS for automatic configuration
4. Netlify provides free SSL certificates automatically

## Contact Form

The contact form is configured to work with Netlify Forms:
- No backend required
- Submissions appear in Netlify dashboard
- Email notifications can be configured in Netlify settings

## Customisation

### Colours
Edit CSS variables in `css/styles.css`:
- `--color-primary`: Main brand green
- `--color-sage`: Secondary green
- Adjust as needed to match brand guidelines

### Content
- All content is in HTML files
- Update text directly in the relevant page files
- Images use Unsplash placeholders - replace with actual photos

### Logo
Replace `images/logo.png` with updated logo files as needed.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## Features

- Responsive design (mobile-first)
- Accessible navigation
- Form validation
- Smooth scroll animations
- Dropdown menus
- Mobile hamburger menu

## Stock Images

The site currently uses Unsplash stock images. For production, consider:
- Professional photography of actual work sites
- Team photos for the leadership section
- Equipment and installation imagery

---

Built for GWT Trading | www.gwttrading.com.au
