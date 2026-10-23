# Korean word list (adapted from 한국어기초사전)

The word data used by the app **Tano: Korean Flashcards**: 5,671 cards (Korean words and a few phrases)
with levels, a learning order, frequency ranks, English and Ukrainian glosses and example sentences.
It is adapted from the National Institute of Korean Language's Basic Korean Dictionary
(한국어기초사전, https://krdict.korean.go.kr), licensed under CC BY-SA 2.0 KR, and shared here under
**CC BY-SA 4.0** (see LICENSE.md and ATTRIBUTION.md).

## Files

| File | What |
|---|---|
| `words.csv`, `words.json` | One row per card. |
| `level-check-words.csv` | 167 more words used only in the app's level check (Korean, level, glosses). |
| `categories.csv` | The app's topics, for the `categories` column. |
| `ATTRIBUTION.md` | The sources, their licenses and what was changed. |
| `LICENSE.md` | The license of this data. |

## Columns of `words.csv`

- `id`: the app's id (`kd:<n>` = the dictionary entry's id `<n>`; `ph:<n>` = a phrase written for the app).
- `source_id`: the dictionary's entry id (target_code); `korean`, `homograph`: the headword and its homograph number.
- `type`: `word` or `phrase`; `pos`: part of speech; `grade`: the dictionary's grade (초급 / 중급 / 고급).
- `level`: the app's level 1–6; `position`: the app's learning order; `frequency_rank`: the rank in NIKL's frequency lists.
- `categories`: the app's topics (`|` between them); `pronunciation`: the standard pronunciation in Hangul, where it differs from the spelling; `romanization`.
- `subtitle_share`: the word's share of content words in Korean subtitles (OpenSubtitles 2018 via FrequencyWords).
- `example_ko`, `example2_ko`: the dictionary's learner example sentences (unchanged); `example2` exists where two cards with the same word and meaning were joined.
- Per language (`en`, `uk`): `gloss`, `gloss2` (a joined card's second meaning), `short` (a shorter form for small spaces), `note`, `example`, `example2` and `exampleAiDraft` / `example2AiDraft` (`true` = the translation was drafted with AI).

Example translations marked as AI drafts were checked by an AI reviewer pass, and in part by hand; please report mistakes.

## Українською

Дані про слова, які використовує застосунок **Tano: Korean Flashcards**: 5,671 карток (корейські
слова й кілька фраз) з рівнями, порядком вивчення, частотними рангами, англійськими й українськими
значеннями та реченнями-прикладами. Їх адаптовано з «Базового словника корейської мови»
Національного інституту корейської мови (한국어기초사전, https://krdict.korean.go.kr), який
поширюється на умовах CC BY-SA 2.0 KR; тут вони поширюються на умовах **CC BY-SA 4.0** (див.
LICENSE.md і ATTRIBUTION.md). Опис стовпців — вище, англійською.

Contact / Контакт: tanokorean.support@gmail.com
