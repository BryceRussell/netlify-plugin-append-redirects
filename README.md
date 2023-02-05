# `netlify-plugin-append-redirects`

Use a `_redirect` file at the root of your Astro project (SSR/SSG)

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