# fingo.digital

A builder's journal — learning to make digital things by actually making them.

## Stack

- HTML + CSS (no framework, no build step)
- Deployed on [Netlify](https://netlify.com)
- Domain: [fingo.digital](https://fingo.digital)

## Structure

```
index.html          — Home page (projects, journal index, about)
style.css           — All styles
journal/            — Individual journal entries
  first-entry.html
netlify.toml        — Netlify routing config
```

## Adding a new journal entry

1. Copy `journal/first-entry.html` to `journal/your-slug.html`
2. Update the title, date, and content
3. Add a link on `index.html` in the journal section
4. Add a redirect in `netlify.toml` for clean URLs
5. Push to GitHub — Netlify deploys automatically

## Local preview

Open `index.html` in a browser. That's it.
