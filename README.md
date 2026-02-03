# Reflect and Rise Podcast Website

A minimalist, zen-inspired dark-mode website for the Reflect and Rise Podcast.

## 🎨 Design Philosophy

- **Color Palette**: Deep midnight navy (#050A14) background with off-white/silver text
- **Typography**: Cormorant Garamond (display) + Work Sans (body)
- **Aesthetic**: Minimalist, plenty of whitespace, emotional intelligence-focused
- **Mobile-First**: Fully responsive design with hamburger menu

## 📁 Website Structure

### Pages

1. **index.html** - Homepage with hero, latest episode, mission, and communication value
2. **starthere.html** - Combined onboarding and about us content
3. **episodelibrary.html** - Browse all episodes with YouTube/Spotify links
4. **guestsubmission.html** - Streamlined guest application form
5. **community.html** - Coming soon page for community features

### Key Features

✅ Logo-based navigation (no text logo)  
✅ "Reflect and Rise Podcast" branding throughout  
✅ Communication value added to homepage  
✅ Combined Start Here + About Us page  
✅ Streamlined Be a Guest page  
✅ New Join the Community coming soon page  
✅ Global audio player (bottom fixed bar)  
✅ Smooth animations and transitions  
✅ Mobile-responsive hamburger menu  

## 🚀 GitHub Pages Setup Instructions

### Step 1: Prepare Your Files

You have these 5 HTML files ready:
- index.html
- starthere.html  
- episodelibrary.html
- guestsubmission.html
- community.html
- Logo.png (your podcast logo)

### Step 2: Upload to GitHub

1. Go to: `https://github.com/cybersecurityclarity/reflectandrisepodcast`

2. Click "Add file" → "Upload files"

3. Upload ALL files:
   - index.html
   - starthere.html
   - episodelibrary.html
   - guestsubmission.html
   - community.html
   - Logo.png

4. Commit message: "Launch Reflect and Rise Podcast website"

5. Click "Commit changes"

### Step 3: Enable GitHub Pages

1. In your repository, click **Settings**

2. Scroll to **Pages** in the left sidebar

3. Under "Source":
   - Branch: **main** (or **master**)
   - Folder: **/ (root)**

4. Click **Save**

5. Wait 2-3 minutes for deployment

6. **Your site**: `https://cybersecurityclarity.github.io/reflectandrisepodcast/`

## ✏️ Customization Guide

### Updating Content

#### Homepage (index.html)
- **Line 230**: Update YouTube embed URL for latest episode
- **Lines 243-247**: Update episode title and description
- **Lines 249-259**: Update YouTube/Spotify/Apple Podcasts links

#### Start Here - About Us (starthere.html)
- **Lines 367-375**: Add your host bio
- **Line 363**: Update host photo (or upload actual image)

#### Episode Library (episodelibrary.html)
- **Lines 287+**: Add your actual episodes
- Replace `href="#"` with your YouTube/Spotify URLs
- Update episode titles, descriptions, and dates

#### Guest Submission (guestsubmission.html)
- **Lines 341-352**: Embed your Google Form
```html
<iframe 
    src="https://docs.google.com/forms/d/e/YOUR_FORM_ID/viewform?embedded=true"
    width="100%" 
    height="1200">
</iframe>
```

### Getting Your Google Form Embed Code

1. Create a Google Form
2. Click **Send** → Embed icon `</>`
3. Copy the entire `<iframe>` code
4. Replace the placeholder in guestsubmission.html

### Updating Your Logo

The logo should be:
- Named exactly: `Logo.png` (case-sensitive)
- Placed in the same directory as HTML files
- Recommended size: 200-400px width for optimal quality

### Theme Colors

All colors are in CSS variables at the top of each file:

```css
:root {
    --midnight-navy: #050A14;
    --deep-slate: #0D1621;
    --accent-gold: #C9A870;
    /* etc... */
}
```

Change these once to update colors site-wide.

## 📄 Page Descriptions

### index.html
Homepage featuring:
- Logo-based navigation
- Hero section with podcast logo
- Latest episode embed
- Mission statement
- Four core values: Self-Awareness, Emotional Intelligence, Resilience, **Communication** (NEW)
- Global audio player

### starthere.html (NEW - Combined Page)
Combined onboarding and about us page with:
- What is Reflect and Rise Podcast?
- Who is this for?
- Our story
- Our mission
- Host bio section
- Core values
- Getting started steps
- Recommended first episodes

### episodelibrary.html
Complete episode catalog:
- Filterable episode grid (All, Recent, Popular, Featured)
- Episode cards with YouTube/Spotify links
- Mobile-responsive layout

### guestsubmission.html (STREAMLINED)
Simplified guest application:
- Starts directly with "You Might Be a Great Fit If..."
- Six criteria cards
- Google Form placeholder
- What happens next process

### community.html (NEW)
Coming soon page featuring:
- Large "Coming Soon" announcement
- Preview of community features
- Links to episodes and start here page
- Beautiful, minimalist design

## 🎯 Navigation Updates

All pages now have consistent navigation:
- **Logo** (image) instead of text
- Home
- Start Here - About Us (combines old Start Here + About)
- Episodes
- Be a Guest
- Join the Community (NEW)

## 📱 Mobile Features

- Hamburger menu on mobile
- Touch-friendly buttons
- Optimized layouts for all screens
- Collapsible navigation

## 🔧 Troubleshooting

### Site Not Loading?
- Wait 3-5 minutes after enabling GitHub Pages
- Check Settings → Pages for correct branch
- Verify all files are in root directory

### Logo Not Showing?
- Filename must be exactly: `Logo.png`
- Check it's in the same folder as HTML files
- Verify the image uploaded successfully

### Form Not Appearing?
- Replace placeholder with your actual Google Form embed code
- Ensure iframe src URL is correct
- Test the form URL independently first

## 🎨 Design Highlights

**What Makes This Design Special:**
- Elegant serif (Cormorant Garamond) + clean sans-serif (Work Sans)
- Deep midnight navy creates a calming, zen atmosphere
- Gold accents (#C9A870) for warmth and emphasis
- Generous whitespace for breathing room
- Subtle hover animations and transitions
- Professional, podcast-quality aesthetic

## 📞 Support

For customization help, refer to HTML comments within each file. Key sections are clearly labeled for easy editing.

## 🎙️ Updates Made

**Latest Changes:**
1. ✅ Logo replaces text in navigation
2. ✅ "Podcast" added to all "Reflect and Rise" references
3. ✅ About Us page merged into Start Here
4. ✅ Communication value added to homepage
5. ✅ Guest page streamlined (removed intro text)
6. ✅ New "Join the Community" coming soon page
7. ✅ All navigation links updated across all pages

---

**Built with care for authentic conversations about emotional growth and self-awareness.**
