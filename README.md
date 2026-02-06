# Wilson Caterpillar Nigeria Enterprises Website

A premium, industrial-grade website for Wilson Caterpillar Nigeria Enterprises (Wilsoncat) - Nigeria's trusted supplier of genuine Caterpillar spare parts and heavy equipment.

## 🏗️ Features

- **Premium Industrial Design**: Bold Caterpillar-inspired aesthetics with yellow/black color scheme
- **Fully Responsive**: Optimized for mobile, tablet, and desktop
- **Complete Pages**: Home, About, Services, Equipment Gallery, Contact
- **Interactive Elements**: Smooth animations, hover effects, filter gallery
- **Professional Layout**: Corporate-grade design with attention to detail
- **Contact Integration**: WhatsApp floating button, contact form, embedded map
- **Lexend Font**: Professional typography throughout

## 📁 File Structure

```
wilsoncat-website/
├── index.html          # Homepage with hero, services, equipment showcase
├── about.html          # Company story, values, commitment
├── services.html       # Detailed service offerings
├── equipment.html      # Filterable equipment gallery
├── contact.html        # Contact form and map
├── style.css           # Complete stylesheet
├── script.js           # Interactive functionality
└── README.md           # This file
```

## 🚀 Deployment Instructions

### Option 1: Basic Web Hosting (Recommended)

1. **Upload Files**
   - Upload all HTML, CSS, and JS files to your web hosting via FTP/cPanel
   - Maintain the file structure as provided
   - Ensure all files are in the root directory or a subdirectory

2. **Configure Domain**
   - Point your domain to the hosting directory
   - Set `index.html` as the default page

3. **Test**
   - Visit your domain
   - Check all navigation links
   - Test contact form functionality
   - Verify WhatsApp button works

### Option 2: GitHub Pages (Free)

1. **Create GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/wilsoncat.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages
   - Select main branch as source
   - Save and wait for deployment

3. **Access Site**
   - Visit: `https://yourusername.github.io/wilsoncat`

### Option 3: Netlify (Easy Drag & Drop)

1. **Visit Netlify**: https://www.netlify.com
2. **Drag & Drop**: Drop all files into Netlify drop zone
3. **Deploy**: Site goes live immediately
4. **Custom Domain**: Add your domain in site settings (optional)

### Option 4: Vercel

1. **Install Vercel CLI**:
   ```bash
   npm i -g vercel
   ```

2. **Deploy**:
   ```bash
   vercel
   ```

3. **Follow prompts** to complete deployment

## 🔧 Customization Guide

### Update Contact Information

Edit the following in ALL HTML files (search and replace):

- **Phone**: `08094825394` → Your number
- **Phone 2**: `08138622278` → Your second number
- **Address**: `Shop 13, New Zuba Motor Spare Parts Market, FCT Abuja` → Your address
- **Instagram**: `@wilsoncatng` → Your handle
- **WhatsApp**: `2348094825394` → Your WhatsApp number

### Change Colors

Edit `style.css` CSS variables:

```css
:root {
    --cat-yellow: #FDDA24;     /* Primary yellow */
    --cat-black: #1A1A1A;       /* Dark background */
    --cat-charcoal: #2D2D2D;    /* Secondary dark */
}
```

### Add More Equipment Items

In `equipment.html`, duplicate this block:

```html
<div class="gallery-item" data-category="heavy-equipment">
    <div class="gallery-item-image-wrapper">
        <div class="gallery-item-badge">Category</div>
        <img src="image-url.jpg" alt="Description">
        <div class="gallery-item-overlay">
            <span>View Details</span>
        </div>
    </div>
    <h3 class="gallery-item-title">Equipment Name</h3>
    <p class="gallery-item-category">Category</p>
</div>
```

### Update Google Map

In `contact.html`, replace the map iframe with your location:

1. Go to Google Maps
2. Search for your address
3. Click "Share" → "Embed a map"
4. Copy iframe code
5. Replace existing iframe in `contact.html`

## 📱 Contact Integration

### WhatsApp
- Floating button links to: `https://wa.me/2348094825394`
- Update number in all instances

### Contact Form
- Currently shows alert on submission
- To connect to backend:
  - Add form action URL
  - Integrate with FormSpree, Netlify Forms, or custom backend
  - Example (FormSpree):
    ```html
    <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    ```

## 🎨 Design Philosophy

This website embodies:
- **Industrial Strength**: Bold typography, strong contrasts
- **Professional Trust**: Corporate color palette, clean layouts
- **Caterpillar Brand**: Yellow/black theme inspired by CAT equipment
- **Nigerian Market**: Optimized for local construction industry needs

## 📞 Real Contact Details

- **Office**: Shop 13, New Zuba Motor Spare Parts Market, FCT Abuja
- **Phone 1**: 08094825394
- **Phone 2**: 08138622278
- **Instagram**: @wilsoncatng
- **WhatsApp**: https://wa.me/2348094825394

## 🔍 SEO Optimization

To improve search rankings:

1. **Add meta descriptions** to each page:
   ```html
   <meta name="description" content="Your description here">
   ```

2. **Add keywords**:
   ```html
   <meta name="keywords" content="caterpillar parts nigeria, heavy equipment abuja, CAT spare parts">
   ```

3. **Create sitemap.xml**
4. **Submit to Google Search Console**

## 🌐 Browser Compatibility

Tested and optimized for:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

© 2024 Wilson Caterpillar Nigeria Enterprises. All rights reserved.

## 💡 Support

For technical support or customization requests:
- WhatsApp: +234 809 482 5394
- Instagram: @wilsoncatng

---

**Built with precision for Nigeria's construction industry** 🏗️
