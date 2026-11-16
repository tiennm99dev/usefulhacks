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

Add a Markdown file under `content/docs/<category>/`, with a `title` and
`tags` in its front matter, and its Vietnamese copy beside it as
`<name>.vi.md`. The sidebar, search, tag pages and "last updated" date pick it
up on their own. A new category is a new folder with `_index.md` and
`_index.vi.md`.

Terms used with `{{< term "..." >}}` are defined in `data/en/termbase.yaml`
and `data/vi/termbase.yaml`, which also feed the Glossary page. News posts go
in `content/blog/`.

Comments use [Giscus](https://giscus.app) on the repository's Discussions
(category "Announcements").

Pushing to `main` builds the site with the latest Hugo and deploys it to
GitHub Pages. Update the theme with `hugo mod get -u && hugo mod tidy`.
