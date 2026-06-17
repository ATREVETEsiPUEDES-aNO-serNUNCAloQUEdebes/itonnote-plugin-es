# Itonnote plugin for TidGi desktop + TiddlyWiki5

## Funcion

Se preconfigura una serie de contenidos triviales, generalmente de cada complemento.ReadmeDiscute en foros, pero la mayoria de la gente es demasiado vaga para leer.Readme，Por lo tanto, te ayudare a configurarlo directamente aqui.。

La introduccion especifica del contenido preestablecido se puede encontrar en[Estacion de documentacion](https://tiddly-gittly.github.io/itonnote-plugin/)。

## Development

See [tiddly-gittly/Tiddlywiki-WikiText-Plugin-Template](https://github.com/tiddly-gittly/Tiddlywiki-WikiText-Plugin-Template) for detail.

There are some scripts you can run to boost your development.

After `npm i`:

- `npm run dev` to auto pack the plugin and run a demo site. Your change in the src directory will automatically refresh the site.
- `npm run dev-html` to see demo site with packed plugin after you finish your development, this can be your final check, this runs slower than `npm run dev`

### After the plugin is complete

#### Publish

Enable github action in your repo (in your github repo - setting - action - general) if it is not allowed, and when you tagging a new version `vx.x.x` in a git commit and push, it will automatically publish to the github release.

#### Demo

You will get a Github Pages demo site automatically after publish. If it is 404, you may need to manually enable Github Pages in your github repo:

Settings - Pages (on left side) - Build and deployment- Source - choose `"Github Actions"`

Next time you trigger a publish, the site will be updated. You can see the site link in Settings - Pages
