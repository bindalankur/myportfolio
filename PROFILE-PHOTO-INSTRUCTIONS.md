# Profile Photo Instructions

## Current Setup
- Your portfolio currently uses a placeholder image: `placeholder-profile.svg`
- The image is displayed as a circular profile picture in the hero section

## How to Add Your Real Photo

### Option 1: Replace the Placeholder (Recommended)
1. **Add your photo** to the project folder
2. **Rename it** to `profile-photo.jpg` (or .png, .webp)
3. **Update the HTML** in `index.html`:
   ```html
   <img src="profile-photo.jpg" alt="Ankur Bindal" class="profile-image">
   ```

### Option 2: Use a Different Filename
1. **Add your photo** to the project folder with any name (e.g., `ankur-photo.jpg`)
2. **Update the HTML** in `index.html`:
   ```html
   <img src="ankur-photo.jpg" alt="Ankur Bindal" class="profile-image">
   ```

## Photo Requirements
- **Size**: At least 300x300 pixels (larger is better)
- **Format**: JPG, PNG, or WebP
- **Style**: Professional headshot or business photo
- **Background**: Clean, professional background
- **Aspect ratio**: Square or close to square works best

## CSS Styling
The profile image is automatically styled with:
- Circular shape (border-radius: 50%)
- White border
- Subtle shadow
- Hover effect (slight zoom)
- Responsive sizing

## Example File Structure
```
myport/
├── index.html
├── styles.css
├── script.js
├── placeholder-profile.svg          # Current placeholder
├── profile-photo.jpg               # Your actual photo (add this)
└── Ankur Bindal_CSM_QA Lead_Resume.pdf
```

## Quick Steps
1. **Take or select** a professional photo
2. **Save it** in your `myport` folder
3. **Update the image source** in `index.html`
4. **Test** by opening `index.html` in your browser

That's it! Your portfolio will now display your actual photo instead of the placeholder.
