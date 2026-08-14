# rding870.github.io

Personal academic site. Plain HTML + CSS, no build step — GitHub Pages serves it directly.

```
index.html   all page content
style.css    all styling (colors live in the :root block at the top)
rachel.jpg   portrait shown in the About section
cv.pdf       linked from the CV section
```

## Editing

Open `index.html` and replace the placeholders — `University Name`, `Advisor Name`,
the three example publications, the education/experience rows, and the `#`/`YOUR_ID`
link targets. Everything is inline in one file, so there's nothing to hunt for.

The portrait is `rachel.jpg`, cropped to a square by the `.portrait` rule in
`style.css` — if you swap the photo, adjust `object-position` there to reframe it.
A CV still needs to go at `cv.pdf`, or delete the CV links if you don't want them.

## Previewing locally

```sh
python3 -m http.server 8000   # then open http://localhost:8000
```

## Publishing

Commit and push to `main`. GitHub Pages picks it up at https://rding870.github.io
within a minute or so. If the site doesn't appear, check
Settings → Pages and confirm the source is set to `main` / root.
