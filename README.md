# Carter Yott

I make tools to improve how I study, such as a quizbowl clue-retrieval program and a few Anki flashcard decks.

You can reach me by [email](mailto:carteryott@icloud.com), or read my trivia blog on [Substack](https://substack.com/@carteryott).

## Projects

### [QBCards & StockFisher](https://github.com/tygerthelyon/qbcards)

Quizbowl tossups follow a strict convention: clues start obscure and get progressively more famous until the giveaway at the end. When you study a new topic, the hard part is figuring out which clues actually come up in tournaments, how early in the question they appear, and whether they belong to high school packets or open-level play.

This repository holds my five-year Anki collection (11,921 notes and 34,848 cards across fine arts, geography, philosophy, history, and the sciences) along with two tools built around it:

- [StockFisher](https://github.com/tygerthelyon/qbcards#stockfisher) mirrors 670,000+ question units from 700+ tournament sets on QBReader into a local SQLite/FTS5 database. Give it an answerline and it extracts the recurring stock clues, orders them by importance—weighing frequency, pyramidal position, and difficulty alongside answer exclusivity—and diffs the result against your Anki decks so you can see which clues you're missing.
- [Buzz Drill](https://github.com/tygerthelyon/qbcards#buzz-drill) is a browser-based tossup reader that pulls real tournament questions for the cards in your deck, streams them word by word at your chosen reading speed, and tracks your buzz depth and power rate over time.

| StockFisher | Anki cards | Buzz Drill |
| :---: | :---: | :---: |
| [![StockFisher clue research interface](https://raw.githubusercontent.com/tygerthelyon/qbcards/main/docs/images/stockfisher-app.png?v=20261114)](https://github.com/tygerthelyon/qbcards#stockfisher) | [![Back of the Fur Traders Descending the Missouri card](https://raw.githubusercontent.com/tygerthelyon/qbcards/main/docs/images/cards-v2/art-back.png?v=fur-traders)](https://github.com/tygerthelyon/qbcards/blob/main/docs/card-gallery.md) | [![Buzz Drill setup and practice interface](https://raw.githubusercontent.com/tygerthelyon/qbcards/main/docs/images/buzz-drill.png)](https://github.com/tygerthelyon/qbcards#buzz-drill) |

---

### [CEDT Health & Safety Portal](https://github.com/tygerthelyon/cedt-safety) — [Live Site](https://tygerthelyon.github.io/cedt-safety/)

The laboratory safety handbook and emergency reference site for the Centre for Emerging Device Technologies (CEDT) and the Department of Engineering Physics at McMaster University.

Built as a fast, plain HTML/CSS/JS site with no framework dependencies so someone looking up an HF acid spill procedure or laser interlock rule isn't waiting on a bundler. Includes a shared client-side layout script across all 34 safety sections, instant full-text search over 150+ protocols and headings, and Python scripts to audit internal links and rebuild the search index.

[![CEDT Health and Safety Portal preview](https://raw.githubusercontent.com/tygerthelyon/cedt-safety/main/assets/images/cedt-home-preview.png)](https://tygerthelyon.github.io/cedt-safety/)
