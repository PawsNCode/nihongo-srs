# Nihongo SRS 🎌

A web app for learning **Japanese (日本語)** from absolute beginner up to
roughly college / JLPT N1 level — spaced-repetition vocabulary, the complete
JLPT kanji set, hiragana & katakana practice, and a stroke-order handwriting
trainer. The whole thing is a single self-contained HTML file.

🔗 **Live app:** https://pawsncode.github.io/nihongo-srs/  *(update this to your own repo path)*

## Features

- **Spaced-repetition vocabulary — the full JLPT range (N5 → N1)** — roughly
  8,000 words organised into bite-size levels (e.g. *N5 · 1*, *N5 · 2* … through
  N1). Each card shows the word in kanji/kana, its reading, the English meaning,
  and tap-to-hear audio. WaniKani-style scheduling brings cards back at growing
  intervals, and reaching **Guru** on most of a level unlocks the next — or, if
  you already know the basics, tap **"I already know these — unlock Level N"**
  on the home screen to jump ahead whenever you're ready.
- **Romaji typed answers with a live kana preview** — type the reading in
  romaji and watch it turn into kana as you go. Both romaji and kana input are
  accepted, and long vowels (e.g. *ou / uu*) count.
- **Kanji by JLPT level — the complete set (N5 → N1)** — every kanji in the
  standard JLPT lists: **2,211 characters** (N5 79, N4 166, N3 367, N2 367,
  N1 1,232). Browse a grid and tap any character to see its readings, meaning,
  and a full **stroke-order diagram** (numbered starts, pink direction arrows);
  **study** with a lesson loop that teaches 5 new kanji at a time — each with its
  stroke order — then quizzes them; quiz yourself freely in either direction
  (kanji → meaning or meaning → kanji); and trace each character with the same
  stroke-order guidance. Many common kanji also include an example word with
  audio. Kana practice uses the same learn-5-then-quiz lesson rhythm.
- **Search** — a search bar in the Kanji browser and the vocabulary list lets
  you find anything instantly by English meaning, the character itself, kana
  reading (hiragana or katakana), or romaji. Kanji search spans all JLPT levels
  at once and tags each result with its level.
- **Script reference** — the full hiragana and katakana charts with a
  pronunciation key, stroke counts, and notes on the tricky kana (し・ち・つ,
  particle は→wa, を→o, へ→e).
- **Kana quiz** — match kana to sounds (or sounds to kana), with live score,
  accuracy, and streaks.
- **Handwriting trainer with stroke order** — trace any kana *or kanji* over a
  guide that shows the real stroke order: numbered start points, direction
  arrows on each stroke, and the exact stroke shapes (from the KanjiVG project).
  A Quiz mode hides the guide and asks you to write the character from memory.
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

## Credits & licence

Stroke-order data (the numbers, arrows, and stroke shapes in the handwriting
trainer) comes from the **[KanjiVG](https://kanjivg.tagaini.net)** project by
Ulrich Apel, used under the **Creative Commons Attribution-ShareAlike 3.0**
licence (CC BY-SA 3.0).

Kanji readings, meanings, and JLPT levels are derived from
**[davidluzgouveia/kanji-data](https://github.com/davidluzgouveia/kanji-data)**,
which builds on KANJIDIC. Vocabulary lists come from
**[open-anki-jlpt-decks](https://github.com/jamsinclair/open-anki-jlpt-decks)**,
which is based on JMdict/EDICT (© the Electronic Dictionary Research and
Development Group, used under CC BY-SA). Because several of these sources are
share-alike, if you redistribute this app please keep this attribution and
license any modifications to that data under the same terms.

## Hosting on GitHub Pages

1. Create a repository (e.g. `nihongo-srs`) and add `index.html` to it.
2. In **Settings → Pages**, set the source to your default branch, root folder.
3. Your app will be live at `https://<your-username>.github.io/<repo>/` —
   update the **Live app** link above to match.
