# Astro Pratyush Kashyap website

This is a static website. There is no build step: publish `index.html` and `logo.webp` together from the repository root.

A GitHub Actions workflow in `.github/workflows/deploy.yml` deploys the site to GitHub Pages whenever a commit is pushed to `main`. Create or choose a GitHub repository, push these files to its `main` branch, then set the repository's Pages source to **GitHub Actions** under **Settings → Pages**. GitHub Pages is available for public repositories on GitHub Free; private repositories require a qualifying paid plan.

For a local preview, run a static file server from the repository root (for example, `python -m http.server 8000`) and open `http://localhost:8000`.

The page loads Tailwind CSS and Google Fonts from their CDNs, so those styling resources require an internet connection. Booking inquiries open WhatsApp with the entered details; they are not stored by this site.
