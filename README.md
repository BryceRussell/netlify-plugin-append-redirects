# `netlify-plugin-append-redirects`

Use a `_redirect` file at the root of your Astro project (SSR/SSG)

> **Important**: If your using the SSR adapter ([`@astrojs/netlify`](https://docs.astro.build/en/guides/integrations-guide/netlify/)) with Astro's [Custom 404 Error Page](https://docs.astro.build/en/core-concepts/astro-pages/#custom-404-error-page) this may not work due to the way the adapter works

## How to Use

1) **Install plugin**: 

```
npm i netlify-plugin-append-redirects
```

2) **Add plugin to `netlify.toml`**:

```toml
[[plugins]]
    package = "netlify-plugin-append-redirects"
```

3) **Create a `_redirect` file at the root of your project**:

4) **Deploy to Netlify**
