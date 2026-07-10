# Rafael Soler Ortuño — personal scientific website

Quarto source for `rsolerortuno.github.io`.

## Local preview

```bash
quarto preview
```

## First publication

1. Create a public GitHub repository named `rsolerortuno.github.io`.
2. Push this project to the `main` branch.
3. From the local repository, run once:

```bash
quarto publish gh-pages
```

4. In GitHub, open **Settings → Pages** and select the `gh-pages` branch as the publishing source.
5. In **Settings → Actions → General → Workflow permissions**, enable **Read and write permissions**.

After the first setup, every push to `main` will trigger the Quarto publishing workflow.

## Add a new post

Create:

```text
posts/my-new-post/index.qmd
```

The blog listing will update automatically when the site is rendered.
