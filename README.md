# Nihongo SRS 🎌

A small web app for learning **Japanese (日本語)** — spaced-repetition
flashcards, hiragana & katakana practice, and a handwriting trainer. The whole
thing is a single self-contained HTML file.

🔗 **Live app:** https://pawsncode.github.io/nihongo-srs/  *(update this to your own repo path)*

## Features

- **Spaced-repetition flashcards** (WaniKani-style stage scheduling) for
  high-frequency Japanese — each card shows the word in kanji/kana, its reading,
  the English meaning, and tap-to-hear audio. Reach **Guru** on most of a level
  to unlock the next one.
- **Romaji typed answers with a live kana preview** — type the reading in
  romaji and watch it turn into kana as you go. Both romaji and kana input are
  accepted, and long vowels (e.g. *ou / uu*) count.
- **Kanji by JLPT level (N5–N1)** — a dedicated section with the **complete
  N5, N4, and N3 kanji lists** (79 + 166 + 367 = 612 characters, following the
  standard JLPT groupings), plus a representative sample for N2 and N1. Browse a
  grid and tap any character for its on'yomi / kun'yomi readings and meanings;
  study them as flashcards and mark what you've learned; quiz yourself in either
  direction (kanji → meaning or meaning → kanji); and trace each character by
  hand over a faint guide with practice and from-memory quiz modes. Common kanji
  also include an example word with audio.
- **Search** — a search bar in the Kanji browser and the vocabulary list lets
  you find anything instantly by English meaning, the character itself, kana
  reading (hiragana or katakana), or romaji. Kanji search spans all JLPT levels
  at once and tags each result with its level.
- **Script reference** — the full hiragana and katakana charts with a
  pronunciation key, stroke counts, and notes on the tricky kana (し・ち・つ,
  particle は→wa, を→o, へ→e).
- **Kana quiz** — match kana to sounds (or sounds to kana), with live score,
  accuracy, and streaks.
- **Handwriting trainer** — trace kana with your finger over a faint guide glyph
  and centre lines, plus a Quiz mode that asks you to write a kana from memory.
- **Progress saves on your device** and the app installs to your home screen.

## How to use

- Open the live link above, or download `index.html` and open it in any browser.
- **On iPhone:** open the link in Safari → **Share** → **Add to Home Screen**
  for a full-screen, app-like icon.
- Start in **Lessons** to learn a batch of words, then come back for **Reviews**
  as they fall due. Use the **Script** tab to drill hiragana and katakana
  separately.

## Built with

- A single HTML file using React + Babel (loaded from a CDN)
- Pronunciation via the browser's Web Speech API (uses your device's Japanese
  voice; install a `ja-JP` voice for the best results)
- Progress stored locally with `localStorage` — nothing leaves your device

## Hosting on GitHub Pages

1. Create a repository (e.g. `nihongo-srs`) and add `index.html` to it.
2. In **Settings → Pages**, set the source to your default branch, root folder.
3. Your app will be live at `https://<your-username>.github.io/<repo>/` —
   update the **Live app** link above to match.
