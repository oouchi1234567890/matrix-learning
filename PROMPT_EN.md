# IT & AI Learning HTML Creation Prompt

Use the following prompt with an AI coding tool to recreate or extend an application equivalent to this project. Adjust the item count, subjects, colors, or speed range when needed.

## English prompt

```text
Create a browser-based study application named “IT & AI Learning” using HTML Canvas.

[Goal]
Display terms and concise definitions for the JDLA G Test, artificial intelligence, Japan's Applied Information Technology Engineer Examination, security, networking, databases, cloud computing, law, ethics, and management as Matrix-style cards flowing from the top to the bottom of a black screen. The app should support passive and repeated study while remaining easy to read.

[File structure]
- index.html: Japanese interface
- index_en.html: English interface
- knowledge.js: Japanese study data
- knowledge_en.js: English study data
- Use only static files. Do not require a framework, package installation, or build tool.
- Use relative paths so the app works from a GitHub Pages project subdirectory.

[Study data]
Provide exactly 2,000 display items:
- AI and JDLA G Test: 700
- Applied IT and computer-science fundamentals: 600
- Security: 300
- Networking, databases, and cloud: 250
- Law, ethics, and management: 150

Format every item as “Term: concise and accurate definition.” Cover the same concepts in Japanese and English, using natural language in each version. At startup, validate each category count, the 2,000-item total, and uniqueness of every display item in JavaScript. Throw an error when validation fails.

[Display rules]
- Shuffle all 2,000 items with the Fisher–Yates algorithm.
- Show each display item only once within a cycle.
- Reshuffle only after all 2,000 items have appeared.
- Prevent the final item of one cycle from immediately repeating as the first item of the next cycle.
- Arrange cards in multiple vertical lanes and prevent cards in the same lane from overlapping.
- Calculate the number of lanes that fully fit the viewport so the leftmost and rightmost cards are never clipped.
- Recalculate lane count, card width, and spacing when the window is resized.
- Wrap Japanese definitions by character count and English definitions by measured word width, using no more than two lines.

[Card design]
- Use black as the default page background.
- Use a dark translucent green card fill and a green border.
- Show the term in bold on the first line.
- Show the concise definition below it.
- Preserve a Matrix-inspired green aesthetic while prioritizing readability.
- Clear each frame sufficiently so long text does not overlap through excessive trails.

[Top controls]
1. Upper-left: color settings panel
   - Term color
   - Definition and border color
   - Page background color
   - Card fill color
   - Reset colors button
2. Top center: Pause / Resume button
   - Keep every card at its current position while paused.
3. To the right of Pause: language switch
   - Japanese page: “English” links to index_en.html
   - English page: “日本語” links to index.html
4. Upper-right: speed panel
   - Slider from 0.25x to 3.0x in 0.25x steps
   - Display the selected multiplier.
   - Estimate and display the cycle duration using 1.0x = approximately 22 minutes.
   - Display cycle number, issued item count, and percentage, such as “Cycle 1: 840 / 2,000 (42.0%).”
   - Include a visual progress bar.
   - After 2,000 items, increment the cycle number and restart progress with a newly shuffled order.

[Interaction]
- Clicking the study background toggles full-screen mode.
- Interacting with color pickers, the speed slider, Pause, or the language switch must not toggle full screen.
- Reposition controls such as the language switch on narrow screens so controls do not overlap.
- Use appropriate accessibility attributes, including aria-live, aria-pressed, label associations, and aria-hidden.

[Smartphone support]
- Include the viewport meta tag and prevent horizontal scrolling.
- Switch to a dedicated mobile layout at viewport widths of 600px or less.
- Compact the color and speed panels and keep them fully inside the upper-left and upper-right edges.
- Apply box-sizing: border-box so panel widths include padding and borders.
- Move Pause to the lower-left and the language switch to the lower-right.
- Hide the small full-screen hint on mobile.
- Draw cards only below the top settings and above the bottom buttons. Use a Canvas clipping region so moving card text cannot appear underneath the controls.
- When the viewport is narrower than laneWidth, still create at least one lane and limit card width to the viewport width minus 16px.
- Center each card within its lane and preserve at least 8px of margin on both sides.
- Support portrait layouts from 320px wide and verify common sizes such as 390×844.
- Keep identical responsive behavior in the Japanese and English pages.

[Icons]
- Use Lucide icons such as Palette, Pause, Gauge, and Languages.
- Include icons as inline or local SVG so the app does not depend on an external CDN.
- Include Lucide attribution in a third-party notices file.

[Quality requirements]
- Keep HTML, CSS, and JavaScript readable and well organized.
- Validate that JavaScript contains no syntax errors.
- Mechanically verify all category counts, the 2,000-item total, and 2,000 unique display strings.
- Keep feature parity between the Japanese and English pages.
- Visually test at desktop 1600×900 and mobile 320×568 and 390×844. Controls, cards, and buttons must not be clipped or overlap.
- Produce a complete result that can be published directly with GitHub Pages.
```

## Usage notes

- Check terminology against authoritative syllabi such as IPA and JDLA publications.
- When generating 2,000 items with an AI tool, generation is more reliable when data is created by subject, then merged and validated.
- When applying the prompt to an existing project, back up files first and verify both language versions in a real browser.

日本語版：[PROMPT.md](PROMPT.md)
