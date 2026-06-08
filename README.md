# Private Talent Group static site with image assets

Upload these files/folders to the root of your GitHub repo:

- `index.html`
- `style.css`
- `script.js`
- `assets/images/hero-vegas-sphere.png`
- `assets/images/lounge-trio.png`

Important: the `assets/images/` folder must stay in the same repo root as `index.html`.

The CSS references images like this:

```css
url("assets/images/hero-vegas-sphere.png")
url("assets/images/lounge-trio.png")
```

So your GitHub repo should look like:

```text
privatetalentgroup.com/
├── index.html
├── style.css
├── script.js
└── assets/
    └── images/
        ├── hero-vegas-sphere.png
        └── lounge-trio.png
```
