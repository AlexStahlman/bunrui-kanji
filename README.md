# Bunrui Kanji (分類漢字)

A free, single-file kanji quiz app for learning Japanese.

## What it does

- Pulls real kanji definitions, readings, and JLPT levels from [kanjiapi.dev](https://kanjiapi.dev) and [jisho.org](https://jisho.org/)
- Quiz format: see a kanji, pick the correct meaning from 4 options
- JLPT level filter (N5–N1) for the general Vocab mode, with multi-select
- Topic-based decks instead of just raw JLPT lists: Daily Conversation, Sumo, HSR, Overwatch, an Anime dropdown (Shonen / Romance / Seinen / Slice of Life), and a Borderlands dropdown (BL1 / BL2 / Pre-Sequel / BL3 / BL4) with per-character filtering
- Mastery tracking — get a kanji right 3 times in a row and it's marked mastered and removed from rotation
- Pin/favorite specific kanji to keep them in your personal study set
- Mistake tracking with a one-click link out to [Jisho.org](https://jisho.org/) for deeper lookup
- Export your pinned kanji as a CSV
- Dark mode by default, with a light mode toggle
- Audio playback of readings via the browser's built-in speech synthesis
- All progress (mastery, pins, mistakes, stats) is saved locally in your browser via `localStorage` — nothing is sent to a server

## Running it

No install needed. Just click [here](https://alexstahlman.github.io/bunrui-kanji/)!

## Tech

- Plain HTML/CSS/JS — no frameworks, no bundler, no `node_modules`
- Data source: [kanjiapi.dev](https://kanjiapi.dev) (free, public, no key required)
- Dictionary lookups: links out to [Jisho.org](https://jisho.org)

## Notes on the topic decks

The JLPT-based Vocab mode uses kanji classifications that come directly from kanjiapi.dev / Jonathan Waller's JLPT resource list — those are sourced.

The themed topic decks (Sumo, Anime genres, Daily Conversation, and the game-inspired decks like HSR, Overwatch, and Borderlands) are original vocabulary lists put together by grouping kanji around the *concepts* and *themes* of each topic — not pulled from any official in-game text, localization, or copyrighted dialogue. Think of them as "kanji you might want to know before diving into a game/show in that genre," not as verified official terminology.
