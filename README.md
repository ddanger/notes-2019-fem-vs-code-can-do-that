# notes-2019-fem-vs-code-can-do-that
Notes from watching frontendmasters.com's workshop [VS Code Can Do That?](https://burkeholland.gitbook.io/vs-code-can-do-that/)
Many of these area opinions of the presenter. I'm just recording the ones I'm interested in (ignoring others).

## Themes
Themes to try:
- Light: Hop Light, Night Owl Light
- Dark: Night Owl, Cobalt 2

## Icons
- [Material Icon Themes](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) very VS Code aware

## Opinionated Settings
- Minimap: Turn it off (Settings -> Minimap). Takes too much space, isn't too useful.
- Sidebar: Move it to the right side (CMD+SHIFT+P: Toggle Side Bar Position). Because now your code won't move around when you open close the sidebar!
- Open Editors feature of side bar: Turn it off (Settings -> open editors visible, change the number to 0)

## Emmet
I've always known it has tons and tons of things I should use and his presentation confirms that again for me.
- lots of CSS property shortcuts like `h100p` -> `height: 100%`, `mh` -> `min-height`, etc.
- balance inward/outward (auto-selecting the containing element) plus map those to keyboard shortcuts
- wrap with abbreviation plus map to keyboard

## Prettier
He extolls the virtues of Prettier, but I'm already on that bandwagon. Moving on...

## Side Bar
- NPM Scripts: why have I never looked at it?

## Extensions
- Version Lens: adds prompts in your package.json telling you what the latest version is
- Simple React Snippets: presenters own package of snippets

## When Things Don't Seem Right
- CMD+SHIFT+P Reload Window

## Folding
- Folding persists through file closing/opening
- Custom folding regions can be created with
```
//#region
a lot of code
//#endregion
```
or in HTML
```
<!--#region
a lot of code
#endregion-->
```

## Multiple Cursors
- Skipping instances: Ooo, when you're using `CMD+D` to add a matching cursor you can skip a match by pressing `CMD+K` then when you hit `CMD+D` again it'll add a cursor for the next match but also skip the one you were on when you pressed `CMD+K`. Nice!
- When in file Find, pressing `OPT+ENTER` adds a cursor for each match in your current document. That's awesome bc it's a good way to use regular expressions to find then get a cursor to each match. Very nice!

## File Switching
- `CMD+P` the list you see there is the recently used files and if you just hit `P` again (so `CMD+PP`) it highlights the last one you were one. Therefore `CMD+PP` toggles between the two most recent files you've been in. Useful!
