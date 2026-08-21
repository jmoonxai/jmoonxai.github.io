# GitHub Pages Portfolio Starter

Minimal AI / Robotics portfolio starter for GitHub Pages.

## 1. Repository

Create a public GitHub repository named:

```text
YOUR_GITHUB_ID.github.io
```

Example:

```text
mimi123.github.io
```

## 2. Upload files

Upload the files in this folder to the repository root.

Expected structure:

```text
YOUR_GITHUB_ID.github.io/
├── index.html
├── css/
│   └── style.css
└── assets/
    ├── images/
    └── resume.pdf
```

## 3. Replace placeholders

In `index.html`, replace:

- `YOUR NAME`
- `YOUR_GITHUB_ID`
- `YOUR_EMAIL@example.com`
- LinkedIn URL
- Resume file
- Project links
- Project images

## 4. Project images

Replace:

```html
<a href="#" class="project-image placeholder">
  <span>PROJECT IMAGE</span>
</a>
```

with:

```html
<a href="./projects/project-name.html" class="project-image">
  <img src="./assets/images/project-name.png" alt="Project preview" />
</a>
```

## 5. Project pages

Recommended structure:

```text
projects/
├── fire-response.html
├── crime-scene-robot.html
├── ocr-data-centric.html
└── disaster-tweets.html
```

Recommended content:

- Overview
- Problem
- System Architecture / Approach
- Experiments
- Results
- Error Analysis
- Lessons Learned
- GitHub / Demo

## 6. GitHub Pages

For a repository named exactly:

```text
YOUR_GITHUB_ID.github.io
```

GitHub normally publishes the main branch automatically.

If not:

`Settings → Pages → Build and deployment → Deploy from a branch → main / root`

Then visit:

```text
https://YOUR_GITHUB_ID.github.io/
```
