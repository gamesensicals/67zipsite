# 67zipsite

The website of [67zip](https://github.com/gamesensicals/67zip), the sandboxed
archive manager for Linux. Now that's a sick 7-Zip! 🤲

It's one static page with no build step and no JavaScript:

- `index.html`: the page and its styles
- `assets/img/`: the logo and screenshots of the app
- `assets/fonts/`: the Inter typeface, bundled so the page looks the same everywhere

To preview it, open `index.html` in a browser, or run
`python3 -m http.server` in this folder and visit <http://localhost:8000>.

## Hosting

GitHub Pages serves it from the root of the `main` branch. Any static host
works too (Cloudflare Pages, Netlify, your own server): upload the folder as it is.

## Licenses

The page is released under the MIT license (see `LICENSE`). The Inter fonts
are © The Inter Project Authors and licensed under the SIL Open Font License
1.1 (see `assets/fonts/LICENSE-Inter.txt`).

Not affiliated with 7-Zip, any league or any song.
