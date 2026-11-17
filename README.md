# Anki Deck: German Schreiben

Storage of German C1 writing flashcards (Redemittel, structural formulas, and academic collocations) generated from essay drafts.

The flashcards are generated with the `german-schreiben-flashcards` skill.

After generation, the artifacts are available in [releases](https://github.com/KTFish/anki-deck-german-schreiben/releases). Download the latest version of this deck to import into Anki.

The deck is stored in [`deck.txt`](deck.txt).

## Target Deck Hierarchy

- **Deck Name**: `german-generated::german-schreiben`
- **Parent Deck**: `german-generated`

All flashcards in this repository target the `german-generated::german-schreiben` Anki deck under the unified `german-generated` collection hierarchy:

```
german-generated
├── german-kindle        (Reading highlights)
└── german-schreiben     (Writing Redemittel & collocations)
```

The `#deck:german-generated::german-schreiben` header directive is encoded directly in [`deck.txt`](deck.txt) so that imported flashcards are automatically directed to the correct nested deck in Anki.

## How to Import into Anki

1. Download `deck.txt` from the latest [GitHub Release](https://github.com/KTFish/anki-deck-german-schreiben/releases).
2. In Anki Desktop, select **File** → **Import...**
3. Select `deck.txt`. Anki reads the `#deck:` directive and automatically imports cards into `german-generated::german-schreiben` using the built-in **Cloze** notetype.

## Contributing Flashcards

Flashcards in this deck are generated using the [`german-schreiben-flashcards`](https://github.com/KTFish/german-schreiben-flashcards) APM skill:

1. Create a feature branch: `feat/add-schreiben-<topic-slug>`.
2. Extract and validate new cards from your essay notes.
3. Open a Pull Request for review.
4. When merged to `main`, GitHub Actions automatically publishes a new release tag and attaches `deck.txt`.
