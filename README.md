# Nenad Latinović - Personal Website

A clean, minimalist Jekyll website with autumn/winter color themes.

## Features

- **Homepage**: Profile picture (circular), name, tagline, and three CTAs (About, Now, Writing)
- **About Page**: Personal information page with winter blue/grey theme
- **Now Page**: What you're currently working on, with autumn brown/tan theme
- **Writing Page**: Blog posts listing with winter forest green theme
- **Blog Posts**: Individual post pages with burgundy/wine theme
- **Markdown Support**: Write posts in markdown with image embedding support

## Quick Start

### Customizing Your Site

1. **Replace the profile picture**:
   - Add your photo to `/assets/images/profile.jpg`
   - Current placeholder is an SVG - replace with your actual photo

2. **Update your information**:
   - Edit `_config.yml` to change your name and tagline
   - Edit `about.md` to write your about page
   - Edit `now.md` to share what you're currently doing

3. **Write blog posts**:
   - Create new markdown files in `_posts/` directory
   - Use the naming format: `YYYY-MM-DD-title.md`
   - Add front matter at the top:
     ```yaml
     ---
     layout: post
     title: "Your Post Title"
     date: YYYY-MM-DD
     ---
     ```

4. **Add images to posts**:
   - Place images in `/assets/images/`
   - Reference in markdown: `![Alt text](/assets/images/your-image.jpg)`

## Color Themes

Each page has a unique autumn/winter hue:
- Homepage: Warm autumn orange/rust (#f4e8dc)
- About: Deep winter blue/grey (#d8e3e7)
- Now: Soft autumn brown/tan (#e8ddd0)
- Writing: Winter forest green (#dde8e0)
- Posts: Deep burgundy/wine (#ebe0e3)

All text is hard black (#000000) for maximum readability.

## Local Development

To run the site locally:

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000` in your browser.

## Deployment

This site is configured for GitHub Pages. Simply push to the main branch and GitHub will automatically build and deploy your site.

## File Structure

```
.
├── _config.yml           # Site configuration
├── _layouts/             # Page templates
│   ├── default.html      # Base layout
│   ├── home.html         # Homepage layout
│   ├── page.html         # Regular pages (About, Now)
│   ├── writing.html      # Writing/blog list page
│   └── post.html         # Individual blog post
├── _posts/               # Blog posts
├── assets/
│   ├── css/
│   │   └── style.css     # All styles
│   └── images/           # Images
├── about.md              # About page
├── now.md                # Now page
├── writing.md            # Writing page
└── index.md              # Homepage
```

## License

Feel free to use this template for your own personal website.
