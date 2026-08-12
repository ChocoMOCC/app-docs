# GAT App Documentation

Documentation hub published at `docs.binusgat.com`.

## Structure

Each application owns one directory at the repository root:

```text
/
├── CNAME
├── index.html
├── socmed/
│   └── index.html
└── another-app/
    └── index.html
```

The root `index.html` is the application directory. Application guides use relative asset paths so they work beneath their assigned URL path.

## Add a guide

1. Create a lowercase directory such as `another-app/`.
2. Put the deployable site and its `index.html` in that directory.
3. Add its card to the root `index.html`.
4. Commit and push to `main`.

Keep `CNAME` at the repository root. It configures the GitHub Pages custom domain.
