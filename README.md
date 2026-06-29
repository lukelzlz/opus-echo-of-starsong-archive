# OPUS: Echo of Starsong — Data Archive

Complete game data extracted from OPUS: Echo of Starsong by SIGONO (Unity 2020.3.35f1).

## Data

| Category | Count |
|---|---|
| Story Dialogues | 4,728 lines |
| Scripted Incidents | 615 (457 include choices) |
| Characters | 81 |
| Items | 283 |
| Locations | 118 |
| Sublocations | 75 |
| Mail Messages | 51 |
| Languages | EN, 简体中文, 繁體中文, 日本語 |

## Viewer

Open `index.html` in any browser to browse the interactive data archive.

Or serve locally:
```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Extraction Method

Game assets extracted from Unity `.assets` and Addressable `.bundle` files using UnityPy.

Key source files:
- `StoryLocalization.txt` — main dialogue (2MB JSON, 4,728 lines)
- `SheetIncidentLocalization.txt` — scripted events with character/effect markers
- `StringDataLocalization.txt` — character name registry
- `SheetItemsLocalization.txt` — item database
- `SheetLocLocalization.txt` — location database
- `SheetMailLocalization.txt` — in-game mail system
- `SheetSubLocLocalization.txt` — sublocation descriptions

## License

Game content is copyright SIGONO. This archive is for reference/documentation purposes.