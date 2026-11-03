# Word-Level Speech Analysis

## Goal
Create a verified, time-aligned transcript that can drive cuts, captions, emphasis and sound design.

## Procedure
1. Access the original audio at the best available quality.
2. Detect speech regions and speakers.
3. Run Malayalam-capable speech recognition.
4. Align words to timestamps if forced alignment is available.
5. Listen again to uncertain segments and correct ASR errors.
6. Mark unresolved speech as `[unclear]`; never guess.

## Transcript fields
`start`, `end`, `text`, `speaker`, `confidence`, `emotion`, `emphasis`, `review_note`.

## Malayalam review
- Preserve Malayalam script.
- Verify chillus, conjuncts, vowel signs and punctuation.
- Check names, places, dates, acronyms and numerals manually.
- Preserve English code-switching as spoken unless translation is requested.
- Avoid accidental word duplication or omission.

## Editing use
Use word timing for karaoke highlighting and precise emphasis. Use phrase groups for readable captions. Treat pauses as editorial candidates, not automatic deletion targets.
