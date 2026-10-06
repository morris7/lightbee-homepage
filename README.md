# Light Bee — Homepage

Static homepage for Light Bee, a web, app and AI development studio.

## Structure

```
index.html      # Single-page site (inline CSS, no build step)
assets/
  logo.svg      # Bee + spotlight hero mark
  bee.svg       # Alternate bee illustration
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
