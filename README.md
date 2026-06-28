# Nihongo SRS 🎌

A web app for learning **Japanese (日本語)** from absolute beginner up to
roughly college / JLPT N1 level — spaced-repetition vocabulary, the complete
JLPT kanji set, hiragana & katakana practice, and a stroke-order handwriting
trainer. The whole thing is a single self-contained HTML file..

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
- **Kanji — the complete everyday set (N5 → N1 + Jōyō)** — **2,383 characters**:
  the full JLPT lists (N5 79, N4 166, N3 367, N2 367, N1 1,232) plus the
  remaining 172 everyday-use (常用/Jōyō) kanji that finish off what a Japanese
  college graduate is expected to read. The running total is shown in the
  header. Browse a grid and tap any character to see its readings, meaning, and
  a full **stroke-order diagram** (numbered starts, pink direction arrows);
  **study** with a lesson loop that teaches 5 new kanji at a time — each with its
  stroke order — then quizzes them; quiz yourself freely in either direction
  (kanji → meaning or meaning → kanji); and trace each character with the same
  stroke-order guidance. Many common kanji also include an example word with
  audio. Kana practice uses the same learn-5-then-quiz lesson rhythm.
- **Mnemonics for every kanji** — each kanji now comes with a memory aid in the
  proven *meaning-story + reading-hook* style (the approach popularized by Heisig
  and WaniKani): a short visual story that ties the character's shape to its
  meaning, plus a sound-alike hook for its on'yomi reading. All 79 N5 kanji have
  hand-written original mnemonics; every other kanji gets an automatically
  generated reading hook (clearly labelled "auto hint"). These are **original
  mnemonics written for this app** — they follow the same *method* as WaniKani but
  are not WaniKani's copyrighted text. They show up on the kanji study card and in
  the Browse detail view, in a collapsible 🧠 panel.
- **Custom quiz** — tap the **✚** on any word (in the Vocab list) or any kanji
  (in Kanji → Browse) to add it to your own collection — or select several at
  once (tap multiple Vocab rows, or use "Select multiple to add" in the kanji
  grid) and add them in one go. Then drill exactly those items from the Reviews
  tab — words and kanji each get their own quiz, and you can clear the set
  anytime. Your collection is saved on your device.
- **Reviews hub** — the Reviews tab lets you choose what to practice: your due
  **vocabulary** (spaced-repetition), **kanji** you've learned (meaning quiz),
  **hiragana**, or **katakana**. Each shows a count, and you can jump back to the
  chooser anytime. (Phrase decks aren't included yet — the current dataset is
  single words.)
- **Themes** — pick from the bottom of the Home screen: cute light palettes
  (Sakura, Lavender, Peach, Matcha, Sky) and dark modes (Midnight, Dark Violet,
  Dark Forest), including violet options. The cherry-blossom logo recolors to
  match. Your choice is saved and applies across the whole app.
- **Tap any kanji to look it up** — in lessons, reviews, and the vocabulary
  dictionary, the individual kanji inside a word are tappable (shown with a
  dotted underline). Tapping one jumps straight to the Kanji page and opens that
  character's full entry — readings, meaning, example, and stroke order — and a
  **"‹ Back to …"** button returns you to exactly where you tapped it.
- **Trace remembers the last kanji you opened** — open a character anywhere on
  the Kanji page, then switch to **Trace** and it starts on that same character.
  The Trace tab also has its own **search**, so you can pull up any kanji to
  practice writing it (by English, the character, kana, or romaji).
- **Build-your-own quizzes** — the Kanji **Quiz** opens with a selection screen:
  tap the characters you want (or search to add any), and start. If you select
  nothing, it quizzes only the kanji you've **learned** by default. The Vocab
  tab works the same way — tap learned words to pick exactly what to drill, or
  just hit **Practice learned words** to review everything you've learned.
- **Vocabulary dictionary (Vocab tab)** — the whole ~8,000-word deck in one
  searchable place, with the running total shown and a JLPT band selector
  (N5–N1) to browse a level at a time. Long lists are capped to the first 200
  with a prompt to narrow by search or level. This is separate from the
  **Lessons / Reviews** spaced-repetition flow, which feeds from the same words
  level by level.
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
  The **Test (SRS)** mode is a spaced-repetition writing test: you write the
  character from memory, self-grade, and each character is then scheduled for
  review (due characters come first, with the usual SRS stages). Works for
  hiragana, katakana, and kanji.
- **Trace tests prompt from text, not sound** — the writing tests now show you
  what to write *in writing*: the kana test gives you the romaji reading ("write
  the kana for this reading"), and the kanji test gives you the English meaning
  ("write the kanji that means …"). The 🔊 speaker is still there if you want to
  hear it, but you're no longer relying on a synthesized voice that can mispronounce
  some characters.
- **Practice before you commit** — in both the kana and kanji lessons, before you
  tap **Learn it** you get a practice pad right on the teaching card: trace the
  character over the stroke-order guide (with a *Hide guide* toggle so you can test
  yourself), and/or type it on your own keyboard to check you've got it. Nothing
  is graded — it's a no-pressure warm-up so the character sticks before it enters
  your review schedule.
- **Script chart lookups** — in the Script → Chart, tap any kana to see its
  details (reading, note, stroke count) and a stroke-order diagram; tap the
  diagram to jump into tracing it, with a back button to return to the details.
- **Stats dashboard** — a progress view with percentages throughout: overall
  vocabulary and kanji mastery bars, a per-JLPT kanji breakdown (N5 → N1 + Jōyō),
  hiragana/katakana coverage, your SRS stage distribution, a 7-day review chart
  with an all-time total, and a level-progress grid.
- **Study calendar (consistency heatmap)** — the Stats screen now includes a full
  month calendar where each day is shaded by how much you studied that day —
  darker = more reviews — so you can see your streak and consistency at a glance.
  Today is outlined, each day shows its review count, and you can page back through
  previous months.
- **Missed items come back** — in a typed quiz, anything you get wrong is
  re-asked again later in the same session (a couple more times), and at the end
  you can retake just the items you missed so they actually stick.
- **At-a-glance accuracy** — words (Vocab list), kanji (Kanji → Browse), and kana
  (Script → Chart) show a colored border: green = solid, amber = shaky, red =
  needs review. One look tells you what to focus on.
- **Backup & restore** — from the Home screen you can download your whole
  progress as a file (or copy it as a code), and restore it on another device or
  after clearing data. No account needed; the backup lives wherever you save it.
- **Refresh & version info** — a **Refresh** button on the Home screen pulls the
  latest version of the app without touching your progress — handy when the app
  is installed to your iPhone home screen and an update isn't showing up yet.
  Just below it, the app shows its **version number** and the **exact date and
  time it was last updated** (detected automatically from the deployed file).
- **Auto-play pronunciation toggle** — a switch on the Home screen turns the
  automatic read-aloud on or off. The 🔊 button always plays even when it's off.
- **Mastery system (0–100%)** — every item carries a single mastery percentage.
  A correct review raises it (with diminishing returns near 100%); **a miss cuts
  it in half**. The percentage and a color band show up on vocab, kanji, kana,
  the trace tests, and the Stats screen. Color bands: **Learning** (red, 0–19%),
  **Shaky** (orange, 20–44%), **Familiar** (gold, 45–69%), **Strong** (light
  green, 70–89%), **Mastered** (green, 90–100%).
- **Master-it quizzes** — a quiz or review session now ends only once **every
  item has been answered correctly twice in a row**. Miss one and it goes back in
  the pile (and its mastery halves). On-screen instructions explain the rule, and
  there's no false "well done" when you've been struggling.
- **Stroke order while learning** — the kana lesson card now shows a numbered
  stroke-order diagram so you can see how each character is written.
- **Trace test = SRS with retake** — the ✍️ Trace test feeds the same spaced-
  repetition schedule; a miss halves mastery and immediately asks you to rewrite
  that same character.
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

---

Made by Niza.
