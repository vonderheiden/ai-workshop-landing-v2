# AI Workshop Landing Page v2

This is a clean deployment of the AI Workshop Landing Page to GitHub Pages with a comprehensive webinar lead magnet page.

## 🚀 Live Sites

- **Main Workshop Page**: https://vonderheiden.github.io/ai-workshop-landing-v2/
- **Webinar Landing Page**: https://vonderheiden.github.io/ai-workshop-landing-v2/event.html

## 📋 GitHub Pages Setup Instructions

If the site is not loading with proper styling, please follow these steps:

1. **Enable GitHub Pages:**
   - Go to your repository settings: https://github.com/vonderheiden/ai-workshop-landing-v2/settings/pages
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch
   - Choose "/ (root)" folder
   - Click "Save"

2. **Wait for deployment:**
   - GitHub Pages can take 5-10 minutes to deploy changes
   - You'll see a green checkmark when it's ready

## 🔧 Files Structure

- `index.html` - Main workshop landing page with complete HTML structure
- `event.html` - **NEW** Webinar landing page for lead magnet campaigns
- `styles.css` - Complete Tailwind CSS styles (22KB)
- `.nojekyll` - Prevents Jekyll processing
- `test.html` - Simple test page to verify CSS loading

## 🎯 Navigation Structure

### Updated Menu System:
- **Program** - Links to main page program section
- **Why Us** - Links to main page why us section  
- **Events** (Dropdown) - **NEW** Dropdown menu with:
  - **Webinars** - Links to webinar landing page (`event.html`)
  - **Workshops** - Links to Eventbrite (placeholder: `https://www.eventbrite.com`)
- **Agenda** - Links to webinar agenda (on webinar page only)
- **Speaker** - Links to speaker section (on webinar page only)
- **FAQ** - Links to FAQ section

### Navigation Features:
- **Desktop**: Hover dropdown with smooth transitions
- **Mobile**: Expandable menu with nested structure
- **Cross-page linking**: Proper navigation between main and webinar pages
- **External links**: Workshop link opens in new tab with security attributes

## 🎯 New Webinar Landing Page Features

### Content Sections:
- **Hero Section**: "Stop Experimenting With AI. Start Shipping Value"
- **Problem Statement**: 5 common AI implementation challenges
- **Value Proposition**: What attendees will learn in 60 minutes
- **Detailed Agenda**: 6 main topics + Live Q&A
- **Speaker Bio**: Professional background and expertise
- **Target Audience**: Clear "for you" vs "not for you" sections
- **Social Proof**: Participant testimonials
- **FAQ Section**: 3 key questions about the webinar
- **Final CTA**: Registration with event details

### Design Features:
- Consistent branding with main workshop page
- Vibrant yellow (#FFD700) accent color
- Professional typography with Inter font
- Responsive design for all devices
- Animated sticky note decorations
- Clear navigation between pages

### Lead Magnet Optimization:
- Multiple "Save My Seat" CTAs throughout the page
- Free webinar positioning (no cost barriers)
- 60-minute time commitment (manageable)
- Practical, execution-focused messaging
- Clear value proposition for busy professionals
- Social media friendly content structure

## 🎨 Design System

- **Primary Color**: Vibrant Yellow (#FFD700)
- **Typography**: Inter font family
- **Layout**: Responsive grid system
- **Components**: Cards, buttons, navigation, forms, dropdowns
- **Animations**: Floating sticky notes, hover effects, dropdown transitions
- **Accessibility**: Focus states, semantic HTML, proper contrast

## 🐛 Troubleshooting

If CSS is not loading:
1. Check that GitHub Pages is enabled (see instructions above)
2. Wait 5-10 minutes for changes to propagate
3. Try hard refresh (Ctrl+F5 or Cmd+Shift+R)
4. Check browser developer tools for CSS loading errors

The CSS path is set to `/ai-workshop-landing-v2/styles.css` which should work with GitHub Pages.

## 📱 Social Media Usage

The webinar page (`event.html`) is optimized for social media campaigns:
- Clear, benefit-focused headlines
- Scannable content structure
- Multiple engagement points
- Mobile-responsive design
- Fast loading times
- SEO-optimized meta tags

## 🔗 Navigation Links

### Main Page (`index.html`):
- **Events > Webinars** → `event.html`
- **Events > Workshops** → `https://www.eventbrite.com` (external)

### Webinar Page (`event.html`):
- **Program** → `index.html#program`
- **Why Us** → `index.html#why-us`
- **Events > Webinars** → `event.html` (current page)
- **Events > Workshops** → `https://www.eventbrite.com` (external)
- **Agenda** → `#agenda` (same page)
- **Speaker** → `#speaker` (same page)
- **FAQ** → `#faq` (same page)