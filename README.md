
VMXFlix - Hugo site skeleton
============================

What is included:
- config.toml pre-configured for vmxflix.com
- archetypes for movies
- example content: content/movies/sample-movie-title.md
- layouts: index.html (homepage list), single movie template with JSON-LD
- taxonomy templates for genre and year
- static assets folder with CSS and posters placeholder
- Decap CMS admin at /admin with a basic config (edit USERNAME/REPO in static/admin/config.yml)

How to use:
1. Install Hugo (extended recommended): https://gohugo.io/getting-started/installing/
2. Place this project in your machine.
3. (Optional) Update config.toml baseURL if testing locally.
4. Initialize a new git repo and push to GitHub.
5. Update static/admin/config.yml -> backend.repo to "yourusername/yourrepo"
6. Deploy to Netlify or Cloudflare Pages. For CMS login & Git commits, Netlify with Identity + Netlify CMS (Decap) is easiest.

Files are exported into this zip for download.

