# 청호건설 (Cheongho Construction) Website

A modern, responsive, multi-page corporate website for 주식회사 청호건설 (Cheongho Construction Co., Ltd.).

## Project Overview

This is a complete redesign of the existing 청호건설 website (https://www.chcc.co.kr/), transformed into a high-converting multi-page website designed to increase qualified traffic, improve time on site, strengthen trust, and increase consultation and quotation inquiries.

## Features

- **Multi-page Architecture**: Separate pages for each main navigation menu and content category
- **Responsive Design**: Fully responsive for desktop, tablet, and mobile devices
- **Korean Language**: All visible content is in Korean for Korean users
- **Premium Design**: Professional corporate design with deep navy, charcoal gray, white, and light gray color scheme
- **Smooth Navigation**: Client-side routing with smooth scrolling
- **Form Validation**: Complete form validation and submission handling
- **Mobile-First**: Mobile bottom contact bar for easy access on mobile devices
- **SEO Optimized**: Proper page structure and Korean search keywords

## Project Structure

```
cheongho-construction/
├── index.html              # Main HTML file with global header/footer
├── css/
│   └── styles.css          # Global styles and responsive design
├── js/
│   ├── router.js           # Client-side routing system
│   └── main.js             # Additional JavaScript functionality
└── pages/
    ├── home.html           # Homepage (/)
    ├── company.html        # Company introduction main page (/company)
    ├── company-greeting.html    # CEO greeting (/company/greeting)
    ├── company-history.html      # Company history (/company/history)
    ├── company-organization.html # Organization chart (/company/organization)
    ├── company-certification.html # Certifications (/company/certification)
    ├── company-location.html     # Location (/company/location)
    ├── business.html        # Business areas main page (/business)
    ├── business-construction.html  # Construction services (/business/construction)
    ├── business-remodeling.html   # Remodeling services (/business/remodeling)
    ├── business-commercial.html   # Commercial space (/business/commercial)
    ├── business-interior.html     # Interior design (/business/interior)
    ├── business-maintenance.html  # Maintenance (/business/maintenance)
    ├── business-other.html        # Other specialized construction (/business/other)
    ├── process.html         # Construction process (/process)
    ├── portfolio.html       # Portfolio main page (/portfolio)
    ├── performance.html     # Business performance (/performance)
    ├── support.html         # Customer support main page (/support)
    ├── support-guide.html   # Construction preparation guide (/support/guide)
    ├── support-checklist.html # Remodeling checklist (/support/checklist)
    ├── support-cost.html    # Cost and estimation guide (/support/cost)
    ├── support-schedule.html # Construction duration guide (/support/schedule)
    ├── support-before-construction.html # Pre-construction checklist (/support/before-construction)
    ├── support-as.html      # Defect and A/S guide (/support/as)
    ├── support-faq.html    # FAQ (/support/faq)
    ├── support-news.html    # News and announcements (/support/news)
    └── contact.html        # Consultation and quotation inquiry (/contact)
```

## Pages Overview

### Homepage (/)
- Hero section with construction imagery
- Customer concern section
- Core business area preview
- Why choose 청호건설 preview
- Construction process preview
- Featured project portfolio preview
- Business performance preview
- Customer support and FAQ preview
- Consultation CTA section

### Company Pages
- **Company Introduction** (/company): Company overview, vision, mission, core values
- **CEO Greeting** (/company/greeting): CEO message and leadership philosophy
- **Company History** (/company/history): Visual timeline of company milestones
- **Organization Chart** (/company/organization): Responsive organization diagram
- **Certifications** (/company/certification): Business licenses, certifications, awards
- **Location** (/company/location): Address, contact info, map, transportation guide

### Business Pages
- **Business Areas** (/business): Overview of all construction services
- **Construction** (/business/construction): Building construction services
- **Remodeling** (/business/remodeling): Remodeling services
- **Commercial Space** (/business/commercial): Commercial space construction
- **Interior Design** (/business/interior): Interior design services
- **Maintenance** (/business/maintenance): Facility maintenance services
- **Other Services** (/business/other): Specialized construction services

### Process Page
- **Construction Process** (/process): 6-step construction process timeline

### Portfolio & Performance
- **Portfolio** (/portfolio): Project portfolio with category filters
- **Performance** (/performance): Business performance history with filters

### Customer Support Pages
- **Support Main** (/support): Customer support hub
- **Preparation Guide** (/support/guide): Construction preparation checklist
- **Remodeling Checklist** (/support/checklist): Remodeling-specific checklist
- **Cost Guide** (/support/cost): Construction cost and estimation guide
- **Schedule Guide** (/support/schedule): Construction duration guide
- **Pre-Construction** (/support/before-construction): Pre-construction checklist
- **A/S Guide** (/support/as): Defect and A/S information
- **FAQ** (/support/faq): Frequently asked questions
- **News** (/support/news): Company announcements

### Contact Page
- **Consultation** (/contact): Project consultation and quotation inquiry form

## Technology Stack

- **HTML5**: Semantic HTML structure
- **CSS3**: Custom CSS with CSS variables, Flexbox, and Grid
- **JavaScript (Vanilla)**: Client-side routing, form validation, animations
- **Google Fonts**: Noto Sans KR for Korean typography
- **Unsplash Images**: Professional construction and architecture imagery

## Color Palette

- **Primary Navy**: #1a2332
- **Dark Navy**: #0f1620
- **Charcoal Gray**: #2d3436
- **Charcoal Light**: #4a5568
- **White**: #ffffff
- **Light Gray**: #f7f9fc
- **Accent Blue**: #3182ce
- **Accent Orange**: #ed8936

## Typography

- **Primary Font**: Noto Sans KR (Google Fonts)
- **Font Sizes**: Responsive scaling from mobile to desktop

## Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1023px
- **Desktop**: ≥ 1024px

## Installation & Setup

1. Clone or download the project files
2. Open `index.html` in a web browser
3. No build process or dependencies required

## Customization

### Company Information
Update the following placeholders with actual company information:
- Company name and logo
- Address and contact details
- Business registration number
- CEO name and greeting
- Company history dates and milestones
- Organization chart names
- Certifications and licenses
- Project portfolio images and details
- Business performance data

### Images
Replace placeholder images with actual company images:
- Construction project photos
- Before/after images
- Team photos
- Office/building photos

### Contact Form
Update the form submission handler in `js/router.js` to connect to your backend or email service.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimization

- Lazy loading for images
- Optimized CSS and JavaScript
- Minimal external dependencies
- Fast loading times

## SEO Features

- Semantic HTML5 structure
- Proper heading hierarchy (H1, H2, H3)
- Korean search keywords in content
- Descriptive image alt text in Korean
- Mobile-friendly design

## Future Enhancements

- Backend integration for form submissions
- Dynamic content management system
- Additional project portfolio items
- Real-time chat integration
- Advanced analytics integration

## License

This project is created for 주식회사 청호건설. All rights reserved.

## Contact

For questions or support regarding this website, please contact 청호건설 through the contact form on the website or call 02-123-4567.
