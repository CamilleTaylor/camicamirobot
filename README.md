# camicamirobot

Camille Taylor's art site. One file, no build step.

## Put it online with GitHub Pages (free)

1. Create a new public repository on GitHub, for example `camicamirobot`.
2. Upload `index.html` (and later an `art/` folder with your images).
3. In the repo: **Settings → Pages → Build and deployment → Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute the site is live at `https://<your-username>.github.io/camicamirobot/`.

## Change the collection

Open `index.html` and find the `WORKS` list near the top of the script. Each line is one piece:

```js
{ title: "Dream Visitor", year: "2023", medium: "Acrylic on canvas", size: "16 × 20 in", note: "", src: "art/dream-visitor.jpg" },
```

Leave `year`, `medium`, `size` or `note` as `""` to hide that line.

## Use camicamirobot.com

Once the site is live on GitHub, add `camicamirobot.com` under **Settings → Pages → Custom domain**, then point the domain's DNS at GitHub Pages. The domain is managed in your WordPress.com account, so Claude can make the DNS change for you when you're ready.
