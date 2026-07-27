# Rafael Soler Ortuño — scientific portfolio

Source for [rsolerortuno.github.io](https://rsolerortuno.github.io), built with Quarto and published with GitHub Pages.

## What is included

- a responsive professional homepage;
- public research-software case studies;
- a concise experience and capabilities page;
- selected peer-reviewed publications;
- a Quarto blog with an RSS feed.

## Local preview

```bash
quarto preview
```

## Production build

```bash
quarto render
```

Every push to `main` renders the site and publishes `_site/` to the `gh-pages` branch through the pinned GitHub Actions workflow.

## Add a project

Create a new `.qmd` file under `projects/`, link it from `projects.qmd`, and add a corresponding card to `index.qmd`.

## Add a post

Create:

```text
posts/my-new-post/index.qmd
```

The writing page and RSS feed update automatically at render time.
