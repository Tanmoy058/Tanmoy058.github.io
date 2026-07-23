# Tanmoy Sen Academic Website

A GitHub Pages academic website prepared from the Academic Pages design pattern and customized with Tanmoy Sen’s CV, profile photo, Google Scholar profile, and GitHub account.

## Website address

After deployment, the site will be available at:

`https://tanmoy058.github.io`

## Publish with GitHub’s web interface

1. Sign in to GitHub as `Tanmoy058`.
2. Create a **public** repository named exactly `Tanmoy058.github.io`.
3. Upload all files and folders from this package to the repository root.
4. Commit the uploaded files to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select `main` and `/ (root)`, then click **Save**.

GitHub may take a few minutes to publish the first version.

## Publish from the command line

```bash
git init
git add .
git commit -m "Create academic website"
git branch -M main
git remote add origin https://github.com/Tanmoy058/Tanmoy058.github.io.git
git push -u origin main
```

Then enable GitHub Pages from `main` and `/ (root)` in the repository settings.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

## Main files

- `index.md`: homepage and profile links
- `research/index.md`: research overview
- `publications/index.md`: selected publications
- `teaching/index.md`: teaching history
- `service/index.md`: professional service
- `files/Tanmoy_Sen_CV.pdf`: downloadable CV
- `assets/images/tanmoy-sen.jpg`: profile photograph
