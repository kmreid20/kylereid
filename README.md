# Kyle Reid — Personal Site

A clean, one-page personal website built with [Jekyll](https://jekyllrb.com/) for GitHub Pages.

## Quick Start

### Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `kylemreid.github.io` for a user site, or any name for a project site)
2. Push this folder to the `main` branch
3. Go to **Settings → Pages → Source** and select `main` branch
4. Your site will be live at `https://<username>.github.io/`

### Run Locally

```bash
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000).

## Editing Content

All profile data lives in **`_data/profile.yml`**. Edit that file to update any info — no need to touch HTML or CSS.

## Structure

```
├── _config.yml          # Jekyll configuration
├── _data/
│   └── profile.yml      # All profile content (edit this!)
├── _layouts/
│   └── default.html     # Base HTML layout
├── assets/
│   └── css/
│       └── style.css    # Stylesheet
├── index.html           # Main page template
├── Gemfile              # Ruby dependencies
└── README.md
```
