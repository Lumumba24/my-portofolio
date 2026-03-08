# Portfolio Configuration Guide

Easily customize your portfolio by editing these sections:

## 🎨 Colors & Branding
**File:** `style.css` (Lines 1-50)
```css
--primary: #your-color;
--secondary: #your-color;
--accent: #your-color;
```

## 📝 Personal Information
**File:** `index.html` (Lines ~9-40)
- **Name:** Line 6, 95
- **Title:** Line 104
- **Email:** Line 34, 599, 708
- **Phone:** Line 41, 606, 709
- **LinkedIn:** Line 42, 614
- **GitHub:** Line 43, 621, 711

## 🖼️ Hero Section
**File:** `index.html` (Lines 83-145)
- **Photo:** Change `photo.JPG` to your image filename
- **Main Title:** "Paul Lumumba." (Line 95)
- **Tagline:** Bridging Cloud... (Line 99-101)
- **Skills Tags:** Python, SQL, Power BI, AWS (Lines 107-110)
- **CV Download Link:** Line 117

## 📄 About Section
**File:** `index.html` (Lines 149-210)
- **About Text:** Edit the 3 paragraphs (Lines ~170-190)
- **Quick Facts:** Lines 195-198
- **Stats Cards:** Lines 202-215

## 💼 Skills Section
**File:** `index.html` (Lines 220-360)
- **Skill Categories:** 4 categories with descriptions
- **Progress Bars:** Change `--pct:XX%` value (e.g., `--pct:85%`)

## 🎯 Projects Section
**File:** `index.html` (Lines 370-480)
- **Project Title:** "Healthcare Management System" (Line 373)
- **Problem/Solution:** Edit case study cards

## 🏆 Certifications Section
**File:** `index.html` (Lines 490-650)
- **Add/Edit Certificates:** 5 certification cards
- **Certificate Links:** Replace `YOUR_CERT_LINK_HERE`

## 📬 Contact Section
**File:** `index.html` (Lines 660-750)
- **Email:** nyangwesoprudence2@gmail.com
- **Phone:** +254111622968
- **Calendar Link:** Calendly URL

## ⚙️ EmailJS Setup (Contact Form)
**File:** `script.js` (Lines ~1-20)
1. Create account at https://www.emailjs.com
2. Add Gmail service (get Service ID)
3. Create email template (get Template ID)
4. Copy Public Key from Account > API Keys
5. Replace these 3 values in `script.js`:
```javascript
EMAILJS_SERVICE_ID = "service_xxxxx"
EMAILJS_TEMPLATE_ID = "template_xxxxx"
EMAILJS_PUBLIC_KEY = "user_xxxxxx"
```

## 🔧 Quick Edit Tips
- Use `Ctrl+F` to find text quickly
- Colors use `--pct:XX%` for skill bars
- `&amp;` = `&` in HTML
- `<br>` = line break
- Images must be in same folder as `index.html`

---
**Reload the page after saving changes | Use Ctrl+Shift+Delete to clear browser cache if changes don't appear**
