# lukesavefrogs.github.io

Source of [lukesavefrogs.github.io](https://lukesavefrogs.github.io): a minimal [Astro](https://astro.build/) landing page that points to my [Curriculum Vitae](https://lukesavefrogs.github.io/curriculum-vitae/).

The CV itself is built and published from [LukeSavefrogs/curriculum-vitae](https://github.com/LukeSavefrogs/curriculum-vitae).

## Development

```bash
npm ci
npm run dev    # or: npm run build && npm run preview
```

## Deployment

The [deploy workflow](.github/workflows/deploy.yml) builds the site and deploys it to GitHub Pages on every push to `main` (pull requests are only built).

> [!IMPORTANT]
> In the repository settings, **Settings → Pages → Build and deployment → Source** must be set to **GitHub Actions**.
> With "Deploy from a branch" GitHub would ignore the Astro build and render this `README.md` with Jekyll instead.
