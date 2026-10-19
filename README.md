# Paint Collection

> ## What's there
> * **701 paint folders.** All 660 wiki paints have their folder.
> * **647 paints are complete:** preview, real texture and game data. 151 of them are animated and have their frame data.
> * **No damaged files:** nothing is empty or unreadable, and every animated texture matches its frame data.

---

> ## What's still not complete
> * **54 wiki paints have no game files.** 43 of them are the wiki's numbered alternate versions (like "Aurora (2)" or "For Players (3)"), which don't exist as separate game items. The other 11 are retired or special paints the garage no longer lists: Armor Blocks, Bears, Best Helper of 2019, Birthday Hat, Goliafffffffff, KALASH68RUS, Kasim, Lions, S-N-E-G, Sun and Wolves.
> * **40 game paints aren't on the wiki.** They have their own folders with full textures, just no wiki info.

# paints

One folder per paint (660 from the wiki's Paints list, 2026-10-18).

- `wiki.json` - the wiki page: type, price { amount, currency }, garage categorization (rarity), container rarity,
  description, interesting facts, every info field (`allFields`) and the page's text (`pageText`). No wiki images.
- `index.json` - all paints: name, folder, rarity, price, currency, type; `notParsed` = list links whose page had no paint
  info block.
- The game's name is written as `{GAME_NAME}` / `{GAME}` and its domain as `{GAME_HOST}`

GAME_HOST = "tankionline.com";
GAME_NAME = "tanki";
