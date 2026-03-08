# cwu.to

Personal project portfolio and creative hub.

## Live

**[cwu.to](https://cwu.to)**

## Projects

| Project | Path | Description | Stack | Date |
|---------|------|-------------|-------|------|
| bev18 | [/bev18](https://cwu.to/bev18) | Beverly's 18th birthday surprise | HTML/CSS/JS, Spline 3D | March 2026 |

## Deployment

- Hosted on **Vercel** — auto-deploys on push to `main`
- Domain: **cwu.to** via Namecheap

## Adding a new project
mkdir your-project
add index.html + assets
git add .
git commit -m "add your-project"
git push

live at cwu.to/your-project

## Repo Structure

```
/
├── index.html          ← homepage
├── bev18/              ← each project gets its own folder
│   ├── index.html
│   └── assets/
├── your-next-project/
│   ├── index.html
│   └── assets/
├── .gitignore
└── README.md
```

Each project is self-contained — its own HTML, CSS, JS, and assets all in one folder. Delete a folder, the project is gone. Add a folder, it's live.
