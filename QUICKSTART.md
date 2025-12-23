# LL&J Consulting Website - Quick Start Guide

## 🚀 Getting Started in 3 Steps

### Step 1: Open the Website
Simply double-click `index.html` to open the website in your default browser, OR right-click and select "Open with" your preferred browser.

### Step 2: Explore the Pages
- **Home** - Main landing page with services overview
- **About Us** - Company information and values
- **Services** - Detailed service descriptions
- **Contact** - Contact form and business location

### Step 3: Test Mobile Responsiveness
Open the website and press `F12` (or right-click → Inspect) to open Developer Tools. Click the mobile device icon to view how the site looks on phones and tablets.

---

## 📝 Quick Customization

### Change the Company Phone Number
Search for `(505) 555-1234` in these files and replace:
- `index.html`
- `about.html`
- `services.html`
- `contact.html`

### Change the Company Email
Search for `info@lljconsulting.com` and replace with your email.

### Update Company Address
Search for `500 4th St NW, Suite 102, Albuquerque, NM 87102` and update.

### Change Colors
Edit `assets/css/styles.css` and update the CSS variables at the top:
```css
:root {
    --primary-dark: #1a3a52;    /* Navy Blue */
    --accent-color: #0984e3;     /* Accent Blue */
    /* ... other colors ... */
}
```

---

## 🎨 Design Features

✓ **Professional Color Scheme** - Navy and charcoal with blue accents
✓ **Fully Responsive** - Works on all devices (phones, tablets, desktops)
✓ **Mobile Menu** - Hamburger navigation on small screens
✓ **Contact Form** - With validation and success messages
✓ **SEO Optimized** - Meta tags for search engines
✓ **Smooth Animations** - Fade-in effects on scroll
✓ **Embedded Map** - Shows business location

---

## 📱 Browser Testing Checklist

- [ ] Home page loads correctly
- [ ] Navigation menu works
- [ ] Mobile menu appears on small screens
- [ ] Contact form validates inputs
- [ ] Links navigate to correct pages
- [ ] All pages display properly on mobile
- [ ] Footer appears on all pages
- [ ] Images load (if added)
- [ ] Colors display correctly
- [ ] Responsive design works (resize browser to test)

---

## 🔧 Making the Contact Form Work

**Currently:** Form shows success message but doesn't send emails

**To send emails, choose one option:**

**Option A: Formspree (Easiest)**
1. Go to https://formspree.io
2. Create a free account
3. Create a new form and get your form ID
4. In `contact.html`, change:
   ```html
   <form id="contactForm" class="contact-form">
   ```
   To:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
   ```

**Option B: Netlify Forms (Free Hosting)**
1. Deploy on Netlify (drag & drop the folder)
2. Add `netlify` attribute to form
3. Forms automatically work!

**Option C: Your Own Email Service**
Update `assets/js/script.js` to send data to your backend API

---

## 📂 File Structure

```
llj-consulting/
│
├── index.html              # Home page
├── about.html              # About Us page
├── services.html           # Services page
├── contact.html            # Contact & Map page
├── README.md               # Full documentation
├── QUICKSTART.md           # This file
│
└── assets/
    ├── css/
    │   └── styles.css      # All styling
    ├── js/
    │   └── script.js       # All functionality
    └── images/             # Add your images here
```

---

## 🎯 SEO Keywords

The website is optimized for:
- "Business management consultant Albuquerque"
- "Small business consulting NM"
- "Business consulting services Albuquerque"

To add more keywords, edit the `<meta name="keywords">` tag in each HTML file.

---

## 🚀 Deployment Options

### Local Server (for testing)
```bash
# Python 3.x
python -m http.server 8000

# Then visit: http://localhost:8000
```

### GitHub Pages (Free)
1. Create a GitHub account
2. Create a new repository named `your-username.github.io`
3. Upload all files
4. Website automatically live at `https://your-username.github.io`

### Netlify (Free with form support)
1. Go to netlify.com
2. Drag and drop the `llj-consulting` folder
3. Website goes live instantly!

---

## ✨ Features Included

### Homepage
- Hero section with large headline
- 4 value propositions
- 4 service preview cards
- 3 client testimonials
- Call-to-action section

### About Page
- Company overview
- Experience highlights
- Philosophy & values
- 4 key benefits

### Services Page
- 5 detailed service descriptions
- 4-step process visualization
- Service-specific benefits

### Contact Page
- Contact information
- Contact form with validation
- Google Maps integration
- Business hours

---

## 📞 Support & Help

For issues or questions:
1. Check the README.md for detailed documentation
2. Review the HTML files - they're well-commented
3. CSS variables at top of styles.css control colors
4. JavaScript is in assets/js/script.js

---

## 🎓 Learning Resources

If you want to customize further:
- **HTML**: Learn tags and structure
- **CSS**: Modify colors, fonts, spacing
- **JavaScript**: Add more interactivity

All code is clean, well-organized, and includes comments.

---

## ✅ What's Included

✓ 4 HTML pages (Home, About, Services, Contact)
✓ Professional CSS styling
✓ JavaScript for mobile menu & form validation
✓ Responsive design for all devices
✓ SEO optimization
✓ Google Maps integration
✓ Contact form with validation
✓ Smooth animations and transitions
✓ Professional color palette
✓ Complete documentation

---

## 📈 Next Steps

1. **Customize content** - Update company info and descriptions
2. **Test on mobile** - Use browser DevTools or real devices
3. **Set up email** - Configure Formspree or email service
4. **Deploy** - Upload to web hosting or use Netlify
5. **Monitor** - Add Google Analytics for tracking
6. **Promote** - Submit to search engines

---

**Happy Building! Your professional consulting website is ready to use.** 🎉

For more help, see README.md in the project folder.
