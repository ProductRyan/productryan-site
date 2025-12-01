# productryan-site

This repository hosts a Jekyll site using the [Chirpy theme](https://github.com/cotes2020/jekyll-theme-chirpy) generated from a WordPress export.

## Getting started
1. Install Ruby (3.2) and Bundler.
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the site locally:
   ```bash
   bundle exec jekyll serve
   ```

If you are deploying to GitHub Pages, set `url` and `baseurl` in `_config.yml` and configure a Pages workflow to build with `bundle exec jekyll build`.
