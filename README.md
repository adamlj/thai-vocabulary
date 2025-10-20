# Thai Vocabulary Audio Files

Audio pronunciation files for Thai vocabulary, extracted from Anki shared decks.

## Contents

- 7,530 unique Thai vocabulary words with audio
- Sequential numbering (1-7530)
- Includes `thai-to-audio.txt` mapping file

## Source Files

Audio files were extracted from the following 6 Anki decks:

- `Manee_Books_1-5_Audio_Transliteration.apkg` (2,283 words)
- `Pocket_Thai_Vocabulary.apkg` (168 words)
- `Thai_1000_Common_Words_incl_Audio_Phonetics_Examples.apkg` (438 words)
- `Thai_Vocabulary_Core_1k_from_Ling_by_Soi.apkg` (0 words - structure not compatible)
- `Thai_vocabulary_frequency_4000.apkg` (2,421 words)
- `Unity_Thai_Language_School_UTL_Flashcards.apkg` (2,220 words)

## Structure

```
audio/
  ├── 1.mp3
  ├── 2.mp3
  └── ... (7,530 files total)
thai-to-audio.txt  # Thai word → audio file number mapping
```

## thai-to-audio.txt Format

Each line contains a Thai word and its corresponding audio file number:
```
กรกฎาคม,12
แมลง,3777
```

## Attribution

These audio files were extracted from publicly available Anki shared decks for Thai language learning.
