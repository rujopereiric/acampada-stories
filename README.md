# acampada-stories

Temporary hosting for Instagram story images of [Acampada Pixel](https://acampadapixel.pt), and nothing else.

`instagram/publish.sh` in [rujopereiric/games](https://github.com/rujopereiric/games) copies a story image into `ig/`,
waits for GitHub Pages to serve it at `https://rujopereiric.github.io/acampada-stories/ig/<name>` so Instagram can fetch
it, then deletes it with a second commit. The repo should normally be empty apart from this README and `.nojekyll`
(which makes Pages skip the Jekyll build, so it deploys faster).

Don't put anything else here: no pages, no other files. It exists so stories don't redeploy the game's own site.
