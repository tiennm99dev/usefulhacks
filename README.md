# Useful Hacks

Useful tips and tricks for everyday tech and internet use, published at
<https://tiennm99dev.github.io/usefulhacks/>.

Built with [Hugo](https://gohugo.io) and the
[Hextra](https://github.com/imfing/hextra) theme, loaded as a Hugo module.

## Quick start

Needs Hugo extended (0.146 or newer) and Go.

```sh
hugo server
```

Then open <http://localhost:1313/usefulhacks/>.

## Adding a tip

Add a Markdown file under `content/docs/<category>/`, with a `title` in its
front matter. The sidebar, search and "last updated" date pick it up on their
own. A new category is a new folder with an `_index.md`.

Pushing to `main` builds the site with the latest Hugo and deploys it to
GitHub Pages. Update the theme with `hugo mod get -u && hugo mod tidy`.
