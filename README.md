# Academic Portfolio Website

A clean, professional Jekyll-based academic portfolio website optimized for GitHub Pages hosting.

## Features

- Responsive design optimized for academic content
- Professional typography and styling
- Social media integration
- Publication listing
- Research portfolio
- Teaching experience section
- Contact information

## Quick Setup

1. **Fork/Clone this repository**
   ```bash
   git clone <your-repo-url>
   cd academic-website
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Configure your site**
   Edit `_config.yml` with your information:
   - Personal details (name, email, position)
   - Institution information
   - Social media handles
   - Research interests

4. **Add your content**
   - Replace profile image: `assets/images/profile.jpg`
   - Update pages: `about.md`, `research.md`, `publications.md`, etc.
   - Add your CV: `assets/files/cv.pdf`

5. **Test locally**
   ```bash
   bundle exec jekyll serve
   ```
   Visit `http://localhost:4000` to preview

## GitHub Pages Deployment

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial academic website setup"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save

3. **Access your site**
   Your site will be available at: `https://yourusername.github.io/repository-name`

## Customization

### Colors and Styling
Edit `assets/css/style.scss` to customize:
- Color scheme (CSS variables in `:root`)
- Typography
- Layout spacing
- Component styling

### Navigation
Update `_config.yml` `header_pages` to modify navigation menu.

### Content Structure
- `index.md` - Homepage content
- `about.md` - About page
- `research.md` - Research interests and projects
- `publications.md` - Academic publications
- `teaching.md` - Teaching experience
- `contact.md` - Contact information

### Assets
- `assets/images/profile.jpg` - Your profile photo
- `assets/files/cv.pdf` - Your CV/resume
- `assets/images/favicon.ico` - Site favicon

## Requirements

- Ruby 2.7+
- Bundler
- Jekyll 3.9+

## License

This template is available as open source under the terms of the MIT License.