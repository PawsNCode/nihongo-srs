# Nihongo SRS 🎌

A web app for learning **Japanese (日本語)** from absolute beginner up to
roughly college / JLPT N1 level — spaced-repetition vocabulary, the complete
JLPT kanji set, hiragana & katakana practice, and a stroke-order handwriting
trainer. The whole thing is a single self-contained HTML file..

🔗 **Live app:** https://pawsncode.github.io/nihongo-srs/  *(update this to your own repo path)*

## Features

**Latest updates**

- **Choose your kanji & kana quiz direction** — the Kanji quiz now offers six
  directions you can switch between mid-session: **kanji → meaning**, **kanji →
  rōmaji**, **kanji → kana reading**, and the reverse of each (**meaning →
  kanji**, **rōmaji → kanji**, **kana → kanji**). The kana quiz flips between
  **kana → rōmaji** and **rōmaji → kana**. Every quiz has a 🔊 button so you can
  hear the answer, and after you pick, the **correct choice turns green** (and a
  wrong pick turns red).
- **Type it and write it in every lesson** — words, kanji, and kana all get a
  practice card before **Learn it**: a **"try writing"** pad (trace over a faint
  guide of the whole word/character) and a **"try typing"** box with a **Check**
  button that accepts kana, kanji, or rōmaji.
- **Two example sentences everywhere** — every word and kanji shows at least two
  example sentences while you learn it and when you look it up; kana show real
  words that use them.
- **Home shows vocab *and* kanji** — separate Lessons and Reviews counts for
  vocabulary and for kanji, each tappable.
- **Kanji taught simplest-first** — within each JLPT level, kanji are introduced
  in order of stroke count so a kanji's mnemonic can build on the simpler kanji
  and radicals you've already met.
- **Consistent, lighter trace guide** — every tracing surface uses the same soft
  pink guide with a thin pen, so your strokes never bury the character.

- **Spaced-repetition vocabulary — the full JLPT range (N5 → N1)** — roughly
  8,000 words organised into bite-size levels (e.g. *N5 · 1*, *N5 · 2* … through
  N1). Each card shows the word in kanji/kana, its reading, the English meaning,
  and tap-to-hear audio. WaniKani-style scheduling brings cards back at growing
  intervals, and **the next level unlocks the moment you've learned every word in
  your current one** (no need to wait for reviews) — or, if
  you already know the basics, tap **"I already know these — unlock Level N"**
  on the home screen to jump ahead whenever you're ready. Kanji work the same
  way: finishing every character in a JLPT level moves you straight on to the next.
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
  grid) and add them in one go. **Anything you add is unlocked and marked as
  learned right away**, so you can build a custom set even from words or kanji you
  haven't formally studied yet. You can also **quick-add by level of mastery**:
  the Vocab list has a chip row that adds every learned word at a chosen **SRS
  stage** (Apprentice, Guru, Master, Enlightened, Burned — tap several to combine
  them), and the kanji Browse grid has the same by **mastery band** (Learning →
  Mastered). Then drill exactly those items from the Reviews
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
- **Practice before you commit (words, kana & kanji)** — in every lesson — kana,
  kanji, *and now vocabulary words* — before you tap **Learn it** you get a
  practice pad right on the teaching card. **Try writing it:** draw the character
  or word over the stroke-order guide (with a *Hide guide* toggle so you can test
  yourself from memory). **Try typing it:** type it on your own keyboard —
  hiragana, katakana, kanji, or romaji — and hit **Check** to verify you got it
  right. Nothing here is graded; it's a no-pressure warm-up so it sticks before it
  enters your review schedule.
- **Example sentences everywhere** — every word, kanji, and kana now shows it used
  in context, both while you're learning it and when you look it up:
  - **Words & kanji** get at least two short example sentences (with audio, a kana
    reading, and an English gloss). They appear on the lesson card and — for vocab
    — when you tap the 📝 button on any row in the Vocab dictionary, and for kanji
    in the Kanji Browse detail card. These are **auto-generated example patterns**
    (clearly labelled *auto*): the sentence frames were chosen to stay grammatical
    across nouns, adjectives, verbs, and set phrases, so they're reliable reading
    practice rather than hand-curated native sentences.
  - **Kana** can't form a sentence on their own, so each kana instead shows two
    real dictionary words that use it (with reading, romaji, meaning, and audio) —
    on the kana lesson card and in the Script → Chart detail view.
- **Script chart lookups** — in the Script → Chart, tap any kana to see its
  details (reading, note, stroke count), a stroke-order diagram, and example
  words; tap the diagram to jump into tracing it, with a back button to return.
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
- **Mastery = your streak of correct answers (0–100%)** — every item carries one
  mastery percentage that is simply **your current run of correct answers across
  every quiz type** (recognition, reading, rōmaji, kana, trace, review…). Each
  correct answer adds **1%**; a single miss **resets it to 0%**. So 100% means a
  hundred correct answers in a row with no slip, and **"Mastered" (90%+) is
  genuinely earned** rather than handed out after a few lucky guesses. Because
  every quiz type feeds the *same* streak, mastering an item means you can read
  it, recognise it, and write it. The percentage and a color band show up on
  vocab, kanji, kana, the trace tests, and the Stats screen. Color bands:
  **Learning** (red, 0–19%), **Shaky** (orange, 20–44%), **Familiar** (gold,
  45–69%), **Strong** (light green, 70–89%), **Mastered** (green, 90–100%).
- **Master-it quizzes** — a quiz or review session ends only once **every item
  has been answered correctly twice in a row**. Miss one and it goes back in the
  pile (and its mastery resets to 0%).
- **Stroke order while learning** — the kana lesson card shows a numbered
  stroke-order diagram so you can see how each character is written.
- **Trace test = SRS with retake** — the ✍️ Trace test feeds the same spaced-
  repetition schedule and the same mastery streak; a miss resets mastery and
  immediately asks you to rewrite that same character. The kanji trace test shows
  the meaning **plus the kana reading and its rōmaji** so you can write from any
  cue.
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
