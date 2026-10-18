# Light Bee — Homepage

The homepage for Light Bee, a web, app and AI development studio.

This is a plain static site: just HTML, CSS and image assets. There is no
framework, package manager, build step or server-side code. What you see in the
repository is exactly what gets served.

## Deployment

The site is published with [GitHub Pages](https://pages.github.com/) at
[lightbee.dev](https://lightbee.dev). Any change merged to the `main` branch is
deployed automatically — no manual publishing or build is required. Open a pull
request for your changes and, once merged, the live site updates shortly after.

The custom domain is declared in the `CNAME` file at the repository root. Keep
that file in version control so Pages doesn't lose the domain association on
subsequent deploys.

## Structure

```
index.html      # Single-page site (inline CSS, no build step)
assets/
  logo.svg                    # Bee + spotlight hero mark
  spotify-ify-artists.png     # Decibel project screenshot
  spotify-ify-analytics.png   # Decibel project screenshot
```

## Run locally

Open `index.html` directly, or serve the folder:

```sh
python3 -m http.server 4173
# then visit http://localhost:4173
```

## Editing

Everything lives in `index.html`. Copy and styles are inline; tweak the hero
copy, the services cards, or the CSS variables in `:root` (colors, accent).
