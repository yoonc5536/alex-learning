# Alex's Learning Hub

A home for Alex's learning materials, published as a website via GitHub Pages.

**Site:** https://yoonc5536.github.io/alex-learning/

## What's here

| Folder | Page |
|---|---|
| `python-curriculum/` | Python Learning Curriculum — the 8-week plan + self-study guide |
| `lesson-plans/` | 8-Week Mini-Project Lesson Plans — weekly projects |
| `snake-guide/` | Snake Game Completion Guide — the capstone project |

The root `index.html` is a landing page linking to each section.

## Adding new content

Each new topic gets its own folder containing an `index.html`:

```
new-topic/
  index.html
```

Then add a card linking to it on the root `index.html` landing page.

All pages are plain static HTML (no build step). Keep every page's assets
inline or relative so it works on GitHub Pages as-is.
