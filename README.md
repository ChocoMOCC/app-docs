# App Documentation

## Structure

Each application owns one directory at the repository root:

```text
/
├── CNAME
├── index.html
├── socmed/
│   ├── index.html
│   ├── docs.css
│   ├── docs.js
│   └── topic-name/
│       └── index.html
├── gatapp/
│   ├── index.html
│   ├── docs.css
│   ├── docs.js
│   └── topic-name/
│       └── index.html
└── another-app/
    └── index.html
```

The root `index.html` is the application directory. Each guide uses one directory per topic, plus shared CSS and JavaScript at the application root. Relative asset and navigation paths keep every page deployable beneath its assigned URL.

## Add a guide

1. Create a lowercase directory such as `another-app/`.
2. Add its overview, shared assets, and individual topic directories.
3. Add its card to the root `index.html`.
4. Commit and push to `main`.

Keep `CNAME` at the repository root. It configures the GitHub Pages custom domain.
