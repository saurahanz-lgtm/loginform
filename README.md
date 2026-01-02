# Karaoke Login Form

A modern, responsive Bootstrap-based login form for a Karaoke application.

## Features

- 🎤 Professional karaoke-themed design
- 📱 Fully responsive layout
- ✨ Smooth animations and hover effects
- 🔒 Form validation
- 💜 Gradient purple background
- Bootstrap 5.3 integration

## Files

- `index.html` - Main login form page
- `vercel.json` - Vercel deployment configuration
- `.gitignore` - Git ignore rules

## Deployment to Vercel

### Option 1: Using Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Login to Vercel
vercel login

# Deploy
vercel
```

### Option 2: Using GitHub + Vercel Web

1. **Initialize Git Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Karaoke login form"
   ```

2. **Create GitHub Repository**
   - Go to https://github.com/new
   - Create a new repository named `karaoke`
   - Copy the repository URL

3. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/karaoke.git
   git branch -M main
   git push -u origin main
   ```

4. **Deploy to Vercel**
   - Go to https://vercel.com
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"
   - Your site will be live at `karaoke.vercel.app`

## Live Demo

After deployment, access your karaoke login form at:
- `https://karaoke.vercel.app`

## Customization

Edit `index.html` to customize:
- Colors and gradients
- Branding (change "Karaoke Hub")
- Form fields
- Backend integration endpoints

## License

MIT
