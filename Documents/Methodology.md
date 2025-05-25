<details>
<summary><strong>Chinese Analysis Prompt</strong></summary>

```markdown
Please analyze the following Chinese poem **line by line**, with the following method:

1. **Character-by-character glossing**:
   - For *each individual character* in a line (before compounds), give:
     - Core standalone meanings
     - 3 historical example sentences from 12th-century Chinese sources (or close era), each with:
       - The original sentence in Chinese
       - A faithful English translation
     - If a character has particularly varied or poetic meanings, include more examples.

2. **Compound identification**:
   - After individual glosses, identify any compounds, set phrases, or poetic constructions formed by combinations of the characters.
   - Repeat the same exemplar process for compounds:
     - Give 3 usage examples per compound if available, same format as above.

3. **Line translation**:
   - Offer a faithful, poetic English translation of the line.
   - Note alternate possible renderings if helpful.

4. **Aesthetic & poetic analysis**:
   - Comment on:
     - Imagery and symbolic motifs from Chinese, Japanese, and Zen poetic traditions.
     - Wordplay, double meanings, puns, or name references.
     - Any resonance with Dōgen’s other works, Buddhist imagery, or seasonal conventions.

⚠️ Do not skip steps or reorder them.  
⚠️ Use clear formatting to make glosses, examples, translations, and commentary easily distinguishable.  
⚠️ Maintain a balance of clarity and poetic sensitivity—this is a philological task, not a loose paraphrase.

We’ll work one line at a time to ensure fidelity and manageable token load.

Here's the poem:  
[INSERT POEM HERE]
</details>

<details>
<summary><strong>Chinese/Japanese/English Glossary Sheet Creator Prompt</strong></summary>

```markdown
Please create an Excel document for the following Chinese poem, one row per Chinese character or word, not by line. The columns should be formatted like this:

Row 1: Chinese characters for first line
Row 2: English translation
Row 3: Pinyin
Row 4: Japanese hiragana rendering of the kanji (where possible)
Row 5: Romaji of the hiragana
Row 6: Repeat for next line

Do not group entire lines into one cell. Instead, break the poem down character by character, and assign each to a new column.

Here is the poem:
</details>
