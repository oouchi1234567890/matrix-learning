<p align="center">
  <img src="docs/icons/computer.svg" width="72" alt="Computer">
</p>

<h1 align="center">IT &amp; AI Learning</h1>

<p align="center">
  Practice for Japan's Applied Information Technology Engineer Examination and the JDLA G Test with flowing study cards.
</p>

<p align="center">
  <strong>2,000 items</strong> · <strong>No repeats per cycle</strong> · <strong>Device-aware cycle and remaining time</strong>
</p>

<p align="center">
  <a href="README.md">日本語</a> · <strong>English</strong>
</p>

<p align="center">
  <a href="https://oouchi1234567890.github.io/matrix-learning/index_en.html"><strong>▶ Open IT &amp; AI Learning</strong></a>
  &nbsp;|&nbsp;
  <a href="https://oouchi1234567890.github.io/matrix-learning/">日本語版を開く</a>
</p>

![IT & AI Learning main screen](docs/images/matrix-learning-overview-en.png)

## <img src="docs/icons/book-open.svg" width="24" alt="Book Open"> About this app

This browser-based study app presents IT and AI concepts related to Japan's Applied Information Technology Engineer Examination and the JDLA G Test as Matrix-style flowing cards. All 2,000 items appear once before the deck is reshuffled, so an item never repeats within the same cycle.

Open the [English app](index_en.html) to study with an English interface and English content.

## <img src="docs/icons/bot.svg" width="24" alt="Bot"> Study areas

| Icon | Area | Items |
|:---:|---|---:|
| <img src="docs/icons/bot.svg" width="22" alt="Bot"> | AI & JDLA G Test | 700 |
| <img src="docs/icons/computer.svg" width="22" alt="Computer"> | Applied IT & fundamentals | 600 |
| <img src="docs/icons/shield-check.svg" width="22" alt="Shield Check"> | Security | 300 |
| <img src="docs/icons/database.svg" width="22" alt="Database"> | Networking, databases & cloud | 250 |
| <img src="docs/icons/scale.svg" width="22" alt="Scale"> | Law, ethics & management | 150 |
|  | **Total** | **2,000** |

## <img src="docs/icons/gauge.svg" width="24" alt="Gauge"> Key features

| Icon | Feature | Description |
|:---:|---|---|
| <img src="docs/icons/shuffle.svg" width="22" alt="Shuffle"> | No repeats | Reshuffles only after all 2,000 items have appeared |
| <img src="docs/icons/gauge.svg" width="22" alt="Gauge"> | Speed control | Adjustable from 0.25× to 3.0× with an estimated cycle time |
| <img src="docs/icons/gauge.svg" width="22" alt="Gauge"> | Cycle progress | Shows the cycle number, issued item count, percentage, and progress bar |
| <img src="docs/icons/pause.svg" width="22" alt="Pause"> | Pause | Stops and resumes every card at its current position |
| <img src="docs/icons/palette.svg" width="22" alt="Palette"> | Color settings | Customize terms, definitions, borders, page background, and card fill |
| <img src="docs/icons/maximize.svg" width="22" alt="Maximize"> | Full screen | Click the study area to enter or leave full-screen mode |
| <img src="docs/icons/computer.svg" width="22" alt="Computer"> | Mobile layout | Keeps controls and cards within the screen from 320px wide |

## <img src="docs/icons/computer.svg" width="24" alt="Computer"> Quick start

1. Download or clone this repository.
2. Open `index_en.html` in a browser.
3. Adjust the speed in the upper-right corner and start studying.

No external libraries, package installation, or build step is required. Keep `index_en.html` and `knowledge_en.js` in the same directory.

## <img src="docs/icons/book-open.svg" width="24" alt="Book Open"> Documentation

- Detailed illustrated instructions: [English User Guide](USER_GUIDE_EN.md)
- English creation prompt: [PROMPT_EN.md](PROMPT_EN.md)
- Japanese creation prompt: [PROMPT.md](PROMPT.md)
- Japanese project page: [README in Japanese](README.md)
- Lucide icon attribution: [Third-Party Notices](THIRD_PARTY_NOTICES.md)

## Project structure

```text
matrix-learning/
├─ index.html                 # Japanese app
├─ index_en.html              # English app
├─ knowledge.js               # Japanese study content
├─ knowledge_en.js            # English study content
├─ README.md                  # Japanese project page
├─ README_EN.md               # English project page
├─ USER_GUIDE.md              # Japanese illustrated guide
├─ USER_GUIDE_EN.md           # English illustrated guide
├─ PROMPT.md                  # Japanese creation prompt
├─ PROMPT_EN.md               # English creation prompt
└─ docs/
   ├─ images/                 # Screenshots
   └─ icons/                  # Lucide SVG icons
```
