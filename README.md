# RidgelineGlow

**Professional Sauna and Plunge Pool Services in Summit County**

Ridgeline Enterprises, LLC - Licensed and Insured  
Serving Commercial and Residential Properties

---

## 🌐 Live Website

Your website will be available at: `https://smpmcmk071.github.io/RidgelineGlow/`

---

## 🚀 Deployment Instructions

### Step 1: Enable GitHub Pages

1. Go to your repository settings: https://github.com/smpmcmk071/RidgelineGlow/settings/pages
2. Under **"Source"**, select **main** branch
3. Click **Save**
4. Your site will be live in 1-2 minutes!

---

## 📧 Email Form Setup (Formspree)

To receive form submissions via email, complete these steps:

### Step 2: Create Formspree Account

1. Go to https://formspree.io
2. Sign up for a **free account** (50 submissions/month)
3. Verify your email address

### Step 3: Create Two Forms

#### Form 1: Project Requests
1. Click **"New Form"**
2. Name it: **"RidgelineGlow - Project Requests"**
3. Set email to: **ridgelinesummitco@gmail.com**
4. Copy the **Form ID** (format: `abc123XYZ`)

#### Form 2: Contractor Applications
1. Click **"New Form"** again
2. Name it: **"RidgelineGlow - Contractor Applications"**
3. Set email to: **ridgelinesummitco@gmail.com**
4. Copy the **Form ID**

### Step 4: Update Your Website

1. Open `index.html`
2. Find line ~408 and replace `YOUR_PROJECT_FORM_ID` with your actual Project Form ID
3. Find line ~484 and replace `YOUR_CONTRACTOR_FORM_ID` with your actual Contractor Form ID
4. Save the file

### Step 5: Commit and Push Changes

```bash
git add index.html
git commit -m "Add Formspree form IDs"
git push origin main
```

Your forms will now email submissions to **ridgelinesummitco@gmail.com**!

---

## ✨ Features

- **Project Request Form** - Customers can request quotes for saunas and plunge pools
- **Contractor Network Application** - Contractors can apply to join your network
- **Email Notifications** - All submissions sent to your email via Formspree
- **Local Storage** - Submissions also saved in browser for quick reference
- **QR Code** - Easily shareable for mobile access
- **Responsive Design** - Works on all devices

---

## 📞 Contact Information

**Stephen Maher**  
Email: ridgelinesummitco@gmail.com  
Phone: 904-896-0163

---

## 💰 Costs

- **GitHub Pages**: FREE ✅
- **Formspree**: FREE (up to 50 submissions/month) ✅
- **Domain (optional)**: ~$12/year if you want a custom domain

---

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript
- No server required
- localStorage for client-side data persistence
- Formspree for email delivery
- QRCode.js for QR code generation

---

## 📝 License

© 2026 Ridgeline Enterprises, LLC. All rights reserved.
