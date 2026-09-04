# Moxfield Decks

A personal repository for managing **Magic: The Gathering decklists, primers, combo documentation, and Moxfield-compatible Markdown**.

The repository serves as a version-controlled home for deck information that can be copied into or maintained alongside decks on [Moxfield](https://www.moxfield.com/).

## Repository Structure

Each directory represents an individual deck or deck project.

```text
moxfield/
├── b57 combos/
│   ├── combos.md
│   └── decklist.txt
│
├── br chainer/
│   ├── decklist.txt
│   └── primer.md
│
├── grixis amass/
│   └── decklist.txt
│
├── r gooblins/
│   └── decklist.txt
│
└── ur starn ping/
    └── decklist.txt
```

## File Types

### `decklist.txt`

Contains the current decklist for a deck.

These files provide a simple text representation of the cards in each list and can be used for:

* Deck tracking
* Version history
* Comparing deck revisions
* Importing or referencing lists in Moxfield
* Maintaining a local copy of a deck outside of Moxfield

### `primer.md`

Contains a deck primer written using Markdown intended for use with Moxfield.

Primers may include information such as:

* Deck strategy
* Card choices
* Synergies
* Win conditions
* Mulligan considerations
* Gameplay notes
* Matchup information
* Other deck-specific documentation

### `combos.md`

Contains documented card combinations and combo lines.

Combo documentation may include:

* Cards required
* Prerequisites
* Step-by-step execution
* Combo results
* Mana or board-state requirements
* Moxfield card references
* Moxfield accordion and panel formatting

For example:

```markdown
===accordion
===panel: Sensei's Divining Top

[[symbol:c]]

Cards Required:
- [[Sensei's Divining Top]]
- [[Foundry Inspector]]
- [[Mystic Forge]]

Prerequisites:
- All permanents on the battlefield.

Steps:
1. Activate Sensei's Divining Top by tapping it, causing you to draw a card and put Sensei's Divining Top on top of your library.
2. Cast Sensei's Divining Top from the top of your library by paying {0}.
3. Repeat.

Results:
- Infinite card draw

===endpanel
===endaccordion
```

## Decks

### b57 combos

Combo documentation and decklist storage.

Includes:

* `combos.md`
* `decklist.txt`

### br chainer

Decklist and full primer documentation.

Includes:

* `decklist.txt`
* `primer.md`

### grixis amass

Decklist storage for the Grixis Amass deck.

Includes:

* `decklist.txt`

### r gooblins

Decklist storage for the mono-red Goblins deck.

Includes:

* `decklist.txt`

### ur starn ping

Decklist storage for the Izzet ping/burn deck.

Includes:

* `decklist.txt`

## Moxfield Markdown

Some Markdown files in this repository are written specifically with **Moxfield's primer formatting** in mind.

Common syntax includes card references:

```markdown
[[Card Name]]
```

Mana symbols:

```markdown
[[symbol:c]]
[[symbol:w]]
[[symbol:u]]
[[symbol:b]]
[[symbol:r]]
[[symbol:g]]
```

And collapsible sections:

```markdown
===accordion
===panel: Panel Title

Content goes here.

===endpanel
===endaccordion
```

This makes the Markdown suitable for copying directly into Moxfield primer and deck-description sections while still remaining readable and version-controlled in GitHub.

## Purpose

The goal of this repository is to keep deck documentation separate from Moxfield itself so that changes can be:

* Version controlled with Git
* Reviewed through commit history
* Edited in a normal text editor
* Backed up independently of Moxfield
* Organized consistently between decks
* Easily regenerated or reformatted when decklists and combos change

## Workflow

A typical workflow is:

1. Update a deck on Moxfield.
2. Export or update the corresponding `decklist.txt`.
3. Update `primer.md` or `combos.md` when strategy or combo lines change.
4. Commit the changes to this repository.
5. Copy updated Markdown back into Moxfield when necessary.

## Notes

This repository is primarily intended for personal deck management and documentation.

Magic: The Gathering, Magic, card names, mana symbols, and related properties are trademarks of Wizards of the Coast LLC.

Moxfield is a third-party deckbuilding platform and is not affiliated with this repository.
