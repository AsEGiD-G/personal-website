# Personal Website with Jekyll & GitHub Pages

This is a personal website and blog built with Jekyll, ready for deployment on GitHub Pages.

## Features
- Responsive homepage with hero and about sections
- Blog with pagination
- Portfolio in a responsive grid (Tailwind CSS)
- Easy content editing with Markdown and YAML

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```

2. **Install dependencies (optional, for local development):**
   ```sh
   bundle install
   ```

3. **Run locally:**
   ```sh
   bundle exec jekyll serve
   ```
   Visit `http://localhost:4000` to view your site.

## Deployment on GitHub Pages

1. **Push your code to GitHub.**
2. Go to your repository settings > Pages.
3. Set the source branch to `main` (or `master`) and the root folder (`/`).
4. GitHub Pages will build and deploy your site automatically.

**Note:**
- All configuration for GitHub Pages is in `_config.yml`.
- For project pages (username.github.io/repo), set `baseurl` and `github.is_project_page` in `_config.yml`.

## Customization
- Edit `_config.yml` for site settings.
- Add blog posts in `_posts/`.
- Add portfolio items in `_data/portfolio.yml`.
- Customize layouts in `_layouts/` and styles in `assets/css/style.css`.

---
Built with ❤️ using Jekyll and GitHub Pages.
