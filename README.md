# Blendi Website

This is the Blendi website project, ready to publish online.

## How to publish this (no coding needed)

### Step 1: Create accounts
- Go to https://github.com and create a free account
- Go to https://vercel.com and sign up using your GitHub account

### Step 2: Upload this project to GitHub
1. On GitHub, click the "+" in the top right, then "New repository"
2. Name it `blendi-website` (or anything you like), then click "Create repository"
3. On the new repository page, click "uploading an existing file"
4. Unzip this folder on your computer, then drag ALL the files and folders
   (package.json, index.html, src, vite.config.js, .gitignore, etc.) into
   the upload box
5. Click "Commit changes"

### Step 3: Deploy with Vercel
1. Go to https://vercel.com and click "Add New... > Project"
2. Find and select the `blendi-website` repository you just created
3. Vercel will automatically detect this is a Vite project. Leave the
   settings as they are.
4. Click "Deploy"
5. Wait a minute or two. Vercel will give you a live link like
   `blendi-website.vercel.app`, this is your real website!

### Updating the site later
Any time you want to change the website, edit the files on GitHub (or
upload new versions), and Vercel will automatically rebuild and update
your live site within a minute or two.

## Project structure
- `src/App.jsx` — the entire Blendi website and demo (this is the main file)
- `src/main.jsx` — entry point, do not need to edit
- `index.html` — page title and basic HTML shell
- `package.json` — project dependencies
