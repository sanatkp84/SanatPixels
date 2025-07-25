# Profile Photo Replacement Instructions

## 📸 How to Replace Your Profile Photo

### Step 1: Prepare Your Photo
- **Recommended size**: 400x400 pixels or larger (square format)
- **File format**: JPG, PNG, or WebP
- **Quality**: High resolution for crisp display
- **Style**: Professional headshot or creative portrait

### Step 2: Replace the File
1. Navigate to: `portfolio/assets/images/`
2. Replace `profile-sample.jpg` with your photo
3. **Keep the same filename** (`profile-sample.jpg`) OR
4. **Update the HTML** if you use a different filename

### Step 3: Update HTML (if using different filename)
If you want to use a different filename, update line in `index.html`:

```html
<!-- Change this line -->
<img src="assets/images/profile-sample.jpg" alt="Profile Photo" loading="lazy">

<!-- To your filename -->
<img src="assets/images/your-photo-name.jpg" alt="Profile Photo" loading="lazy">
```

### Step 4: Optimize Your Photo (Optional)
For best performance, you can:
- **Compress** the image to reduce file size
- **Convert to WebP** format for better compression
- **Use tools** like TinyPNG or ImageOptim

## 🎨 Photo Guidelines

### ✅ Good Photo Characteristics:
- **Clear face visibility**
- **Good lighting**
- **Professional appearance**
- **Centered composition**
- **Minimal background distractions**

### ❌ Avoid:
- **Blurry or low-quality images**
- **Very dark or overexposed photos**
- **Busy backgrounds**
- **Extreme close-ups or distant shots**

## 🔧 Technical Details

### Current Profile Photo Features:
- **Circular crop** applied automatically
- **Glassmorphism border** effect
- **Hover animations** (scale and glow)
- **Responsive sizing**:
  - Desktop: 300x300px
  - Tablet: 250x250px  
  - Mobile: 200x200px

### File Location:
```
portfolio/
└── assets/
    └── images/
        └── profile-sample.jpg  ← Replace this file
```

## 🚀 Quick Replacement Method

**Easiest way**: Simply drag and drop your photo into the `assets/images/` folder and rename it to `profile-sample.jpg` (replacing the existing file).

---

**Need help?** The current sample photo is a professional placeholder that you can replace with your own photo anytime!
