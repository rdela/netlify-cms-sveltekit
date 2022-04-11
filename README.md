# netlify-cms-sveltekit

A SvelteKit skeleton app with Netlify CMS living in `/admin`. Netlify CMS is configured to directly edit `/routes/*.md` files, which are preprocessed by [mdsvex](https://mdsvex.com).

## Developing

Once you've downloaded this repo and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create the production version of your app, run:

```bash
npm run build
```

> You can preview the built app with `npm run preview`. However, this should _not_ be used to serve your app in production.

## History

This repo was originally cloned from <https://github.com/buhrmi/sveltekit-netlify-cms> on 2022-04-11
