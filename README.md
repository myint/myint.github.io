# stevenmyint.com

Personal portfolio site for Steven Myint, hosted on GitHub Pages.

It is plain static HTML and CSS, with no build step or JavaScript.

## Local preview

    python3 -m http.server 8000

Then open <http://localhost:8000>.

## Deploy

GitHub Pages serves the `main` branch of this repository
(Settings → Pages → Deploy from a branch → `main` / root). Updates are
published from a separate source repository by force-pushing a single
"Deploy" commit, so this repository has no history and changes made here
directly will be overwritten.
