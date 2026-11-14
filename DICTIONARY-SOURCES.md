# Word Haven dictionary sources

The Android build combines these English word lists into one bundled offline validation file. The game filters entries to alphabetic words of 2–6 letters.

## Wordnik Wordlist
- Source: https://github.com/wordnik/wordlist
- File: wordlist-20210729.txt
- Licence: MIT
- Purpose: English vocabulary intended for word games.
- Attribution: Wordnik, copyright 2020. The MIT licence notice is available in the source repository.

## ENABLE
- Source: https://github.com/dolph/dictionary
- File: enable1.txt
- Licence: Public domain, as released by the ENABLE authors.
- Purpose: English word-game lexicon.

## dwyl English words
- Source: https://github.com/dwyl/english-words
- File: words_alpha.txt
- Purpose: supplementary broad English vocabulary.
- The build filters this source to alphabetic entries of 2–6 letters.

## Processing
The Android workflow lowercases, filters, combines, and deduplicates these sources into `www/words_alpha.txt`. The resulting file is bundled with the app for offline play.

## Important
This combined list is a broad English word-acceptance list, not an official Scrabble, Words With Friends, or tournament lexicon. Rare, archaic, technical, regional, and offensive terms may still occur in upstream sources. Puzzle answers should continue to be curated separately from bonus-word validation.
