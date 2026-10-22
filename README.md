# AWS S3 Practice Website

A beginner-friendly static website built with HTML and CSS. You can publish it on GitHub Pages or upload the files to an Amazon S3 bucket.

## Project files

- `index.html` — website content
- `style.css` — website styling

## Run locally

1. Download or clone this repository.
2. Open `index.html` in your browser.

## Upload to GitHub

1. Create a new repository on GitHub.
2. Upload `index.html`, `style.css`, and `README.md` to the repository root.
3. Commit the files.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then save.
5. Wait for the deployment link to appear on the Pages screen.

## Upload to Amazon S3

Upload `index.html` and `style.css` to your bucket. For a public website, configure an appropriate website-delivery approach. For secure production hosting, keep the bucket private and use CloudFront with Origin Access Control.

This project contains no credentials or backend code.
