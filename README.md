# Spell Mate

A responsive spelling-learning website and spelling-bee test, built with plain HTML, CSS, and JavaScript.

## Pages

- `index.html`: word library with meanings, historical roots/source forms, memory chunks, pronunciation, difficulty filters, and spelling practice.
- `Test.html`: random test rounds with meaning clues, spoken pronunciation, typed or spoken-letter answers, hints, encouragement, and scores.

All 499 supplied entries have original embedded vector picture clues and descriptive captions. Some scenes are symbolic memory aids for abstract ideas; related words can share motifs. In tests, pictures stay hidden until the learner asks for a clue. These are original illustrations, not images from the book.

Both pages contain their own data. There are no dependencies or build steps. GitHub Pages can publish the `main` branch from the repository root.

Learning cards include curated word-family examples where dictionary sources support the relationship. Historical roots, prefixes, suffixes, and modern base-word derivatives are labelled separately, with short meanings and source links. Examples may be outside the supplied spelling list. Rare or uncertain origins are not assigned invented relatives.

Parts of speech appear on learning and test cards. Published usage on learning cards contains short exact excerpts with source links, with inflections, foreign-language and historical contexts labelled. Unconfirmed quotations are marked explicitly. Created practice sentences are labelled separately. Quotations stay out of tests so they do not reveal the spelling.

## Content status

The supplied transcription has 499 entries and 493 distinct spellings. Position 500 is blank. Original book photos have not been available to verify spellings or order. Uncertain forms and histories are labelled in the learning cards; two unconfirmed spellings are withheld from practice. Repeated spellings are tested only once, leaving 491 eligible different spellings. Many spoken-syllable guides are still awaiting confirmation. Dictionary and other research references are linked in the learning cards.

Spelling difficulty is an estimated teaching aid, not an official rating.

## Audio

Pronunciation uses the browser's computer voice. Accent and unusual-word accuracy depend on the installed voices.

Spoken answers use the browser's speech-recognition service and microphone permission. Say each letter, review the captured spelling, then submit. Interim letters appear while speaking; Check spelling finishes the capture and grades it. Letter names and phonetic letters such as Alpha, Bravo and Charlie are accepted. Saying the whole word does not count as spelling. Browser support varies, and some recognition services process audio online. The live HTTPS Test page in a supported Chrome or Edge browser is recommended. Typing remains available when recognition is unsupported. Live microphone capture must be tested on the intended browser and device.

Test progress is held in memory for the current round; there are no accounts or backend services provided by this project.
