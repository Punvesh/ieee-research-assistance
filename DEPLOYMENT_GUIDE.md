# Deploy to Vercel - Quick Guide

## 3 Simple Steps

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in (or create account)
2. Click **New Repository** button
3. Name it: `ieee-paper` (or any name)
4. Click **Create Repository**

### Step 2: Push Your Code to GitHub
Open terminal in your project folder (`/home/punvesh/Desktop/ieee-paper`) and run:

```bash
# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - IEEE Research Paper website"

# Add remote (replace YOUR_USERNAME and REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/ieee-paper.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Connect to Vercel
1. Go to [vercel.com](https://vercel.com)
2. Click **Sign Up** → Use GitHub (easiest)
3. Authorize Vercel to access your GitHub
4. Click **Import Project**
5. Select your `ieee-paper` repository
6. Click **Import**
7. Vercel will detect it's a static site (no config needed)
8. Click **Deploy**

**Done!** ✅ Your site is now live in ~30 seconds.

---

## What You Get (Free)
- ✅ Live URL like: `ieee-paper.vercel.app`
- ✅ Auto-deploys when you push to GitHub
- ✅ Free HTTPS/SSL
- ✅ Global CDN
- ✅ Custom domain support (optional)

---

## Troubleshooting

**If you don't have Git installed:**
```bash
# On Ubuntu/Debian
sudo apt-get install git

# On macOS
brew install git
```

**Quick alternative (no Git needed):**
1. Go to [vercel.com](https://vercel.com)
2. Sign up
3. Drag and drop your project folder
4. Done!

---

## Next Steps
- Update WhatsApp number in all files (1234567890 → your number)
- Update email (contact@ieeeresearch.com → your email)
- Test the contact form on your live site
- Add custom domain (optional, via Vercel dashboard)
