## Main Reference: *"Wisdom Within Words"* by Stephen Heine

Heine's work remains the only comprehensive work of Dōgen's Chinese poetry in English. While it's an invaluable research and resource, I find myself disagreeing with his readings quite a lot—not to mention aesthethic differences. :)

## Prompts Used

Used with ChatGPT and DeepSeek for this project:

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
```

</details>

<details>
<summary><strong>Chinese/Japanese/English Glossary Sheet Creator Prompt</strong></summary>

```markdown
Please create an Excel document for the following Chinese poem, one row per Chinese character or word, not by line. The columns should be formatted like this:

Row 1: Chinese characters for first line  
Row 2: Pinyin 
Row 3: Japanese hiragana rendering of the kanji (where possible) 
Row 4: Romaji of the hiragana
Row 5: English translation of the chinese character
Row 6: Repeat for next line

Do not group entire lines into one cell. Instead, break the poem down character by character, and assign each to a new column.

Here's the poem:
[INSERT POEM HERE]
```

</details>

## Various Chinese Language Tools

Chinese related tools I use to decipher the texts:

### [A Primer in Chinese Buddhist Writings](https://religiousstudies.stanford.edu/primer-chinese-buddhist-writings)

John Kieschnick's seminal work for students of Chinese Buddhist Writings.

### [A Dictionary of Chinese Buddhist Terms](https://mahajana.net/texts/soothill-hodous.html)

An excellent dictionary for Buddhist terms in Chinese, by William Edward Soothill and Lewis Hodous.

### [Charles Muller's Chinese Dictionaries](https://buddhism-dict.net)

One for Buddhist, one for general East Asian religions & philosophies, two great resources for any serious scholar. 

### [Buddhist Chinese - Sanskrit Dictionary](https://static.sariputta.com/pdf/tipitaka/867/a-buddhist-chinese_sanskrit-dict_hirakawa.pdf)

Hirakawa's fantastic dictionary for all the Chinese terms that were used for Sanskrit translations. 

### [CC-CEDICT Chinese Dictionary](https://www.mdbg.net/chinese/dictionary?page=cedict)

The word dictionary project started by Paul Denisowski with the aim to provide a complete downloadable Chinese to English dictionary with pronunciation in pinyin for the Chinese characters. An amazing tool for offline scripts.

### [Yomitan Pop-up Dictionary Plug-in for Chrome](https://chromewebstore.google.com/detail/yomitan-popup-dictionary/likgccmbimhjbgkjambclfkhldnlhbnn?hl=en)

A browser plug-in for dictionaries for various languages, notably for Chinese & Japanese. 

### [Mandarin Spot Annotations](https://mandarinspot.com/)

A great little wrapping around CC-CEDICT that provides easy to read annotations for a body of text, also giving a printable glossary. Has a simple API for your websites to use. 
