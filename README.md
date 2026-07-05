# guoqikevin.github.io

Personal homepage of **Guo Qi (郭奇)** — live at [guoqikevin.github.io](https://guoqikevin.github.io).

Built with [Astro](https://astro.build) as a minimal, single-page static site: no client-side JavaScript, system fonts, dark-mode aware.

## Development

```sh
npm install
npm run dev      # local dev server at localhost:4321
npm run build    # production build to ./dist/
```

## Deployment

Every push to `main` is built and published to GitHub Pages by the workflow in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

## Notes

- `public/cn.m3u` and `public/gq_cn.m3u` are IPTV playlists served at the site root — keep them, their URLs are in active use.
