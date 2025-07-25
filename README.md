# Jekyll News Portal

This is a static news portal powered by Jekyll. It includes:

- Main page with top news (`index.html`)
- Articles page listing all posts (`articles.html`)
- CMS dashboard with instructions (`cms/index.html`)
- Advertisement block embedded between posts

## Run Locally

```bash
gem install bundler jekyll
jekyll serve
```

Then visit `http://localhost:4000/` in your browser.

## Deployment

To deploy on GitHub Pages:

1. Push this project to a public GitHub repository.
2. In the repo settings, go to "Pages" and choose the root (`/`) folder of the `main` branch.
3. GitHub will build and publish the site at:
   https://<your-username>.github.io/<repo-name>/

## Content Management

- Add posts to `_posts/` folder.
- Ads: Replace `ads/sample-ad.jpg` and customize `_includes/ad_block.html`.