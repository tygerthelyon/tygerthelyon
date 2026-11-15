# Carter Yott

I make tools to improve how I study, such as a quizbowl clue-retrieval program and a few Anki flashcard decks.

If you have any questions, you can contact me by [email](mailto:carteryott@icloud.com). I also write a trivia blog on [Substack](https://substack.com/@carteryott).

## Projects

### [QBCards & StockFisher](https://github.com/tygerthelyon/qbcards)

This repository holds my Anki collection, built up across the last five years or so. As of November 2026, it contains 11,921 notes and 34,848 cards across fine arts, geography, philosophy, history, and the sciences. It also holds two tools:

- [StockFisher](https://github.com/tygerthelyon/qbcards#stockfisher) mirrors 670,000+ question units from 700+ tournament sets on QBReader into a local SQLite/FTS5 database. It takes an answerline and extracts the recurring clues, orders them by importance—weighing frequency, pyramidality, and difficulty alongside answer exclusivity—and diffs the result against your Anki decks so you can see which clues you're missing.
- [Buzz Drill](https://github.com/tygerthelyon/qbcards#buzz-drill) is a browser-based tossup reader that pulls clues from your deck, matches them to real instances of that clue in QBReader, and reads it in real-time, tracking your buzz depth and power rate over time.

| StockFisher | Anki cards | Buzz Drill |
| :---: | :---: | :---: |
| [![StockFisher clue research interface](https://raw.githubusercontent.com/tygerthelyon/qbcards/main/docs/images/stockfisher-app.png?v=20261114)](https://github.com/tygerthelyon/qbcards#stockfisher) | [![Back of the Fur Traders Descending the Missouri card](https://raw.githubusercontent.com/tygerthelyon/qbcards/main/docs/images/cards-v2/art-back.png?v=fur-traders)](https://github.com/tygerthelyon/qbcards/blob/main/docs/card-gallery.md) | [![Buzz Drill setup and practice interface](https://raw.githubusercontent.com/tygerthelyon/qbcards/main/docs/images/buzz-drill.png)](https://github.com/tygerthelyon/qbcards#buzz-drill) |

---

### [CEDT Health & Safety Portal](https://github.com/tygerthelyon/cedt-safety) • [Live Site](https://tygerthelyon.github.io/cedt-safety/)

The health & safety site for the Centre for Emerging Device Technologies (CEDT) and the Department of Engineering Physics at McMaster University.

Built as a fast, plain HTML/CSS/JS site with no dependencies. Includes a shared layout script across 34 safety sections, full-text search over 150+ protocols and headings, and Python scripts to audit internal links and rebuild the search index.

[![CEDT Health and Safety Portal preview](https://raw.githubusercontent.com/tygerthelyon/cedt-safety/main/assets/images/cedt-home-preview.png)](https://tygerthelyon.github.io/cedt-safety/)
