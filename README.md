# Reflect and Rise Podcast Website

A minimalist, zen-inspired dark-mode website for the Reflect and Rise Podcast.

## 🎨 Design Philosophy

- **Color Palette**: Deep midnight navy (#050A14) background with off-white/silver text
- **Typography**: Cormorant Garamond (display) + Work Sans (body)
- **Aesthetic**: Minimalist, plenty of whitespace, emotional intelligence-focused
- **Mobile-First**: Fully responsive design

## 📁 Website Structure

1. **index.html** - Homepage with hero, latest episode, and mission
2. **starthere.html** - Onboarding page for new listeners
3. **episodelibrary.html** - Browse all episodes with YouTube/Spotify links
4. **aboutus.html** - About the podcast and host
5. **guestsubmission.html** - Guest application form with Google Form embed

## 🚀 GitHub Pages Setup Instructions

### Step 1: Prepare Your Files

1. Make sure you have all 5 HTML files ready
2. Upload your podcast logo as `Logo.png` (you already have this!)

### Step 2: Upload to GitHub

1. Go to your repository: `https://github.com/cybersecurityclarity/reflectandrisepodcast`

2. Click "Add file" → "Upload files"

3. Upload these files:
   - index.html
   - starthere.html
   - episodelibrary.html
   - aboutus.html
   - guestsubmission.html
   - Logo.png (your podcast logo)

4. Add a commit message like "Initial website launch" and click "Commit changes"

### Step 3: Enable GitHub Pages

1. In your repository, click "Settings"

2. Scroll down to "Pages" in the left sidebar

3. Under "Source", select:
   - Branch: **main** (or **master**)
   - Folder: **/ (root)**

4. Click "Save"

5. Wait 2-3 minutes for deployment

6. Your site will be live at: `https://cybersecurityclarity.github.io/reflectandrisepodcast/`

## ✏️ Customization Guide

### Adding Your Logo

The logo is already referenced in the HTML as `Logo.png`. Just make sure your logo file is named exactly that (case-sensitive).

### Updating Content

#### Homepage (index.html)
- Line 230: Update the YouTube embed URL
- Lines 243-247: Update episode title and description
- Lines 249-259: Update listen links (YouTube, Spotify, Apple Podcasts)

#### Episode Library (episodelibrary.html)
- Lines 287-327 (and similar blocks): Add your actual episodes
- Replace `#` in `href="#"` with your YouTube/Spotify URLs

#### About Us (aboutus.html)
- Lines 231-247: Add your host bio
- Update the host image section (line 227)

#### Guest Submission (guestsubmission.html)
- Lines 341-352: Replace with your actual Google Form embed code
- To get your form embed:
  1. Create a Google Form
  2. Click "Send" → Embed icon `</>`
  3. Copy the entire `<iframe>` code
  4. Replace the placeholder section

### Embedding Your Google Form

```html
<!-- Replace the placeholder section with your actual form -->
<iframe 
    src="https://docs.google.com/forms/d/e/YOUR_FORM_ID/viewform?embedded=true"
    width="100%" 
    height="1200" 
    frameborder="0" 
    marginheight="0" 
    marginwidth="0">
    Loading…
</iframe>
```

### Updating Colors

All colors are defined in CSS variables at the top of each file:

```css
:root {
    --midnight-navy: #050A14;
    --accent-gold: #C9A870;
    /* etc... */
}
```

Change these values once to update colors across the entire page.

## 🎯 Next Steps

1. **Add Real Content**:
   - Upload actual episode info
   - Add your YouTube/Spotify embed codes
   - Write your host bio
   - Create and embed your Google Form

2. **Test Thoroughly**:
   - Check all links
   - Test on mobile devices
   - Verify form submission works

3. **Optional Enhancements**:
   - Add Google Analytics
   - Set up a custom domain
   - Add an RSS feed
   - Integrate with podcast hosting platforms

## 📱 Mobile Responsive Features

- Hamburger menu on mobile
- Collapsible navigation
- Touch-friendly buttons
- Optimized layouts for all screen sizes

## 🎨 Theme Customization

The entire design uses a consistent theme defined by CSS variables. To maintain the aesthetic across all pages:

1. Keep the navigation HTML identical
2. Use the same CSS variable names
3. Maintain consistent spacing using the defined spacing variables

## 📄 File Descriptions

- **index.html**: Landing page with hero section and latest episode
- **starthere.html**: New visitor onboarding with recommended episodes
- **episodelibrary.html**: Filterable grid of all podcast episodes
- **aboutus.html**: Mission, values, and host information
- **guestsubmission.html**: Application form for potential guests

## 🔧 Troubleshooting

**Site not loading?**
- Wait 3-5 minutes after enabling GitHub Pages
- Check that your branch is set correctly in Settings → Pages
- Verify all files are in the root directory (not in a subfolder)

**Logo not showing?**
- Ensure the file is named exactly `Logo.png`
- Check that it's in the same directory as your HTML files

**Form not appearing?**
- Make sure you've replaced the placeholder with your actual Google Form embed code
- Check that the iframe src URL is correct

## 📞 Support

For issues or questions about this website template, please refer to the HTML comments within each file or create an issue in the repository.

---

**Built with care for authentic conversations about emotional growth and self-awareness.**
