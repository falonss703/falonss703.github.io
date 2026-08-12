# Jingze Wu's Personal Academic Website

This is the source code for my personal academic website, forked from an academic pages template.

## Website Setup

This website is built using Jekyll and hosted on GitHub Pages.

### Local Development

To run the website locally:

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000 in your browser
```

### Updating Content

#### Personal Information
Edit `_config.yml` to update:
- Name, email, social media links
- Google Scholar, GitHub, LinkedIn profiles

#### Main Page Content
Edit `_pages/about.md` to update:
- Research interests and bio
- News and updates
- Publications
- Awards and achievements

#### Publications
Add publication images to `images/publications/` directory and update the publications section in `_pages/about.md`.

### Deployment

This site is automatically deployed via GitHub Pages when you push to the main branch.

## TODO

Before going live, please complete the following tasks (see `INFO_NEEDED.md` for details):

- [ ] Add personal profile photo (`images/profile.png`)
- [ ] Update email address in `_config.yml`
- [ ] Add Google Scholar profile link
- [ ] Add GitHub username
- [ ] Add publication preview images (see `IMAGE_INSTRUCTIONS.md`)
- [ ] Update paper links (arXiv, code repositories)
- [ ] Add complete author lists for all papers
- [ ] Verify all dates and information

## File Structure

```
├── _config.yml           # Site configuration
├── _pages/
│   └── about.md          # Main homepage content
├── _includes/            # Reusable page components
├── _layouts/             # Page templates
├── images/
│   ├── profile.png       # Your profile photo
│   └── publications/     # Publication preview images
├── INFO_NEEDED.md        # List of information to fill in
└── IMAGE_INSTRUCTIONS.md # Guide for preparing images
```

## Credits

This website template is based on the [academicpages](https://github.com/academicpages/academicpages.github.io) template.

## License

The template is licensed under MIT License. Your personal content and research work remain your own.

---

Last updated: August 2026
