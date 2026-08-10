# tappolabs.github.io

Studio site for **TappoLabs** — a single static page listing the three Android apps.

Live at <https://tappolabs.github.io/>.

## Contents

| Path | Purpose |
| --- | --- |
| `index.html` | The whole site. No build step, no dependencies beyond Google Fonts. |
| `favicon.svg` | Studio mark — three dots, one per app. |
| `assets/*.png` | App launcher icons (Tappo, adrift, Watercolor Sort). |
| `app-ads.txt` | AdMob authorised-sellers file. Must stay at the domain root. |

## Apps

| App | Play listing | Package |
| --- | --- | --- |
| Tappo | [Auto Tapper - Tappo](https://play.google.com/store/apps/details?id=com.tappo.autotapper) | `com.tappo.autotapper` |
| adrift | [adrift - cognitive shuffle](https://play.google.com/store/apps/details?id=com.tappolabs.adrift) | `com.tappolabs.adrift` |
| Watercolor Sort | [Watercolor Sort: Paint Puzzle](https://play.google.com/store/apps/details?id=com.tappo.watersort) | `com.tappo.watersort` |

Privacy policies live in their own repos (`tappo-privacy`, `adrift-privacy`, `watersort-privacy`) and are linked from the footer.

## Deploying

GitHub Pages serves `main` at the repo root. Push to `main` and the change is live in about a minute.

## Design notes

Paper/ink foundation (`#FBF7EF` on `#1B1A17`), 2.5px keylines with hard offset shadows, Fredoka for headings and DM Sans for body — the same visual language as the Tappo landing page. Each app card carries its own accent colour so the three read as distinct products inside a consistent studio frame.

`app-ads.txt` is required by AdMob for the domain listed as the developer website on Play. Do not delete it.
