# productryan-site

This repository hosts a Jekyll site using the [Chirpy theme](https://github.com/cotes2020/jekyll-theme-chirpy) generated from a
WordPress export.

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

If you are deploying to GitHub Pages, set `url` and `baseurl` in `_config.yml`. The included GitHub Actions workflow builds with
Jekyll 4 using the repository Gemfile and publishes the generated `_site` output to the GitHub Pages environment. You can mirror
that locally with:
```bash
bundle exec jekyll build
```
