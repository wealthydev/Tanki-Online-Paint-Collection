# paints

One folder per paint (660 from the wiki's Paints list, 2026-10-18).

- `wiki.json` - the wiki page: type, price { amount, currency }, garage categorization (rarity), container rarity,
  description, interesting facts, every info field (`allFields`) and the page's text (`pageText`). No wiki images.
- `index.json` - all paints: name, folder, rarity, price, currency, type; `notParsed` = list links whose page had no paint
  info block.
- The game's name is written as `{GAME_NAME}` / `{GAME}` and its domain as `{GAME_HOST}` (the project never stores them -
  the server fills them from its env GAME_NAME / GAME_HOST when shown).
- Game files per paint (texture `image.webp`, animated `frame.json`, the garage preview, the item's server data) are added
  by `tools/paints-collect.mjs` from the garage downloads (see docs/classic-ui.md).
