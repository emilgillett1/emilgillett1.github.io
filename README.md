# Personal Academic Website

A clean, professional academic website template for researchers and academics.

## Setup Instructions for GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `YOUR_USERNAME.github.io` (replace YOUR_USERNAME with your actual GitHub username)
   - Example: If your username is `emilresearcher`, name it `emilresearcher.github.io`
4. Make sure the repository is set to **Public**
5. Click "Create repository"

### Step 2: Upload Your Website Files

1. In your new repository, click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `style.css`
   - `profile.jpg` (your profile photo)
   - `cv.pdf` (optional: your CV as a PDF)
3. Click "Commit changes"

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings** (top menu)
2. Scroll down to **Pages** section (left sidebar)
3. Under "Source", select:
   - **Branch:** main (or master)
   - **Folder:** / (root)
4. Click **Save**

### Step 4: Access Your Website

Your website will be live at: `https://YOUR_USERNAME.github.io/`

It may take a few minutes for the site to go live after your first commit.

## Customization Guide

### Update Your Information

Edit `index.html` and replace:

1. **Name and Contact Info:**
   - Replace "Your Name" with your actual name
   - Update email, Google Scholar, and GitHub links
   - Update affiliation and title

2. **About Me Section:**
   - Customize the bio paragraphs with your research interests
   - Update research description

3. **Research Section:**
   - Edit research interests list
   - Update project descriptions
   - Add or remove projects as needed

4. **Publications:**
   - Add your publications
   - Update titles, authors, venues
   - Add links to PDFs, DOIs, code repositories

5. **CV Section:**
   - Update education information
   - Add your degrees and institutions
   - Update skills, awards, and honors

### Add Your Profile Photo

1. Prepare a square profile photo (recommended: 400x400px or larger)
2. Name it `profile.jpg`
3. Upload it to your repository
4. The website will automatically display it

If you use a different filename or format (e.g., `profile.png`), update this line in `index.html`:
```html
<img src="profile.jpg" alt="Profile Photo" class="profile-photo">
```

### Add Your CV PDF

1. Export your CV as a PDF
2. Name it `cv.pdf`
3. Upload it to your repository
4. The "Download Full CV" button will automatically work

### Customize Colors

Edit `style.css` to change colors:

- **Primary color (blue):** Search for `#3498db` and replace with your preferred color
- **Dark background:** Search for `#2c3e50` and replace
- **Hover color:** Search for `#2980b9` and replace

### Add More Sections

To add new sections:

1. Add a navigation link in the navbar:
```html
<li><a href="#newsection">New Section</a></li>
```

2. Add the section content:
```html
<section id="newsection" class="section">
    <h2>New Section Title</h2>
    <p>Your content here...</p>
</section>
```

## Tips

- **Keep it updated:** Regularly update your publications and projects
- **Optimize images:** Compress photos to improve loading speed
- **Test responsiveness:** View your site on mobile devices
- **Use Google Analytics:** Add tracking to see visitor statistics
- **Add favicon:** Create a small icon that appears in browser tabs

## Example Sites

- [Original inspiration](https://congxu96.github.io/)
- Many academic researchers use GitHub Pages for professional websites

## Troubleshooting

**Site not loading?**
- Wait 5-10 minutes after first push
- Check that repository name is exactly `USERNAME.github.io`
- Ensure repository is set to Public

**Images not showing?**
- Check file names match exactly (case-sensitive)
- Ensure images are in the same directory as `index.html`

**Need custom domain?**
- You can use a custom domain (e.g., yourname.com)
- See [GitHub Pages custom domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

## License

This template is free to use and modify for your personal academic website.
