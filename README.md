# JMoon Portfolio — Final Layout

Current structure:

1. Top Bar
2. About
3. My Projects
4. Expertise
5. Contact

## File structure

```text
jmoonxai.github.io/
├── index.html
├── css/
│   └── style.css
└── assets/
    ├── images/
    │   ├── profile.jpg
    │   ├── fire-response.jpg
    │   ├── crime-scene.jpg
    │   ├── ocr.jpg
    │   └── disaster-tweets.jpg
    └── resume.pdf
```

## Add a project image

Replace:

```html
<a href="#" class="project-image placeholder">
  <span>ADD PROJECT IMAGE</span>
</a>
```

with:

```html
<a href="#" class="project-image">
  <img src="./assets/images/fire-response.jpg" alt="Multi-Robot Fire Response System">
</a>
```

## Add the Contact profile image

Replace:

```html
<div class="profile-placeholder">
  <span>PROFILE<br />IMAGE</span>
</div>
```

with:

```html
<div class="profile-placeholder">
  <img src="./assets/images/profile.jpg" alt="Jae Moon Hwang">
</div>
```

## Replace these placeholders

- `YOUR_GITHUB_ID`
- `YOUR_EMAIL@example.com`
- LinkedIn URL
- Project links
- Project image filenames
- Resume PDF
