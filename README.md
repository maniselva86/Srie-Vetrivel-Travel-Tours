# Sri Vetrivel Travels & Tours 🛕

Official website for **Sri Vetrivel Travels & Tours**, Coimbatore, Tamil Nadu.

## 📁 Folder Structure

```
sri-vetrivel-travels/
├── index.html          ← Main website file
├── assets/
│   └── logo.png        ← ⚠️ Add your logo here
└── images/
    ├── slide1.jpg      ← ⚠️ Add your slider images here
    ├── slide2.jpg
    ├── slide3.jpg
    ├── slide4.jpg
    └── slide5.jpg
```

## ⚠️ Before You Go Live

1. **Add your logo** → Place your logo file inside `assets/` and name it `logo.png`
2. **Add slider images** → Place 5 travel photos inside `images/` named `slide1.jpg` through `slide5.jpg`
   - Recommended size: **1600 × 900px**, under 300KB each
3. **Update captions** → Open `index.html`, find the `captions` array in the `<script>` tag and update destination names
4. **Update contact details** → Replace phone, email, and address with your real details

## 🚀 Hosting on GitHub + Cloudflare Pages

### Step 1 — Push to GitHub
1. Go to [github.com](https://github.com) → **New repository**
2. Name it `sri-vetrivel-travels` → Create
3. Upload all files (drag & drop in GitHub UI)

### Step 2 — Deploy on Cloudflare Pages
1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Click **Create a project** → **Connect to Git**
3. Select your GitHub repo
4. Build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/`
5. Click **Save and Deploy**

Live at: `https://sri-vetrivel-travels.pages.dev`

### Step 3 — Custom Domain (Optional)
1. In Cloudflare Pages → **Custom domains** → Add your domain
2. Point your domain's nameservers to Cloudflare

## ✏️ Quick Customisation

| What | Search for in index.html |
|---|---|
| Phone number | `+91 98765 43210` |
| Email | `info@srivetriveltravels.com` |
| Address | `123, Anna Salai` |
| Package prices | `₹3,499` / `₹7,999` / `₹14,999` |
| Slider captions | `const captions = [` in script |
| Slider filenames | `images/slide1.jpg` etc. |
