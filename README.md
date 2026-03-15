# Staticnest Docs

Documentation site for [Staticnest](https://github.com/Dev-kitx/staticnest-docs) — a Python static site generator for polished documentation.

## Prerequisites

- Python 3.12
- [Pipenv](https://pipenv.pypa.io/)

## Setup

```bash
pipenv install
```

## Local preview

```bash
pipenv run staticnest preview
```

Then open `http://127.0.0.1:8000`.

## Build

```bash
pipenv run staticnest build
```

Output is written to `dist/`.

## Deploy to GitHub Pages

```bash
pipenv run staticnest gh-deploy
```

## Project structure

```
site.toml          # Site settings and theme configuration
navigation.yml     # Sidebar and header navigation
content/           # Markdown source pages
  index.md
  docs/
    getting-started.md
    configuration.md
    authoring.md
    deployment.md
    customization/
      index.md
      theme-overrides.md
```
