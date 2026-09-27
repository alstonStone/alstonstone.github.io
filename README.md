# Personal site (Jekyll + GitHub Pages)

## Add a project (about 1 minute)
1. Upload a picture to `assets/images/projects/`.
2. Copy any file in `_projects/` (e.g. `example-project-one.md`), rename it,
   and edit the top section (title, date, status, image path) and the text.
3. Commit. The Projects page updates itself - no other file to touch.

## Add a blog post
Create `_posts/YYYY-MM-DD-title.md` starting with:

    ---
    title: My Post Title
    ---
    Your text here.

## Publish
Push to GitHub, then Settings > Pages > Deploy from a branch > main, / (root).
GitHub runs Jekyll for you. You can create files and upload images right in
the GitHub website, so you don't need Git installed to add content.

## Preview locally (optional)
Install Ruby, then: `gem install bundler jekyll` and `jekyll serve`
(open http://localhost:4000). If your site lives at username.github.io/repo,
set `baseurl: "/repo"` in `_config.yml`.

## Folders
- `_layouts/` page templates   - `_includes/nav.html` the sidebar (edit once)
- `_posts/` blog posts         - `_projects/` one file per project
- `assets/` CSS and images     - `_config.yml` site settings
