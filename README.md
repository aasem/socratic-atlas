# Socratic Dialogue Atlas

Twenty-four Platonic dialogues set side by side: the question, setting and scene, method, where each one arrives, the strongest pushback, what became of the speakers, and the intended lesson. A timeline also arranges them as a single story, from the young Socrates of the *Parmenides* (c. 450 BCE) to the hemlock (399 BCE).

Live site: https://aasem.github.io/socratic-atlas/

## Files

| File | What it is |
|---|---|
| `index.html` | The whole atlas: content, styles and script. |
| `readings.js` | The reader's own opinion on each dialogue, shown as "*Name*’s Reading". This is the part to edit. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. |

## Your own readings

The readings are the one part of the atlas meant to be personal. Each one appears under its dialogue with the reader's name, for example **Bakhshi’s Reading**.

**To change the name**, edit this line in `readings.js`:

```js
window.READINGS_AUTHOR = `Bakhshi`;
```

Anyone who copies or forks the atlas can put their own name there. A name ending in *s* is shown correctly (*Socrates’ Reading*).

**To change the readings**, either:

1. **On GitHub:** open `readings.js`, click the pencil icon, change the text between the backticks, and commit. A blank line starts a new paragraph.
2. **On the page:** type a name in the **Reader** box above the dialogues, click **Edit** under any dialogue, write, and **Save**. These changes stay in your browser only. When you're done, click **Copy readings.js**, paste it over `readings.js` on GitHub, and commit.

## Publishing with GitHub Pages

In the repository, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save. The site updates a minute or two after each commit.

## Credits

Compiled by Asim D. Bakhshi with Claude, Anthropic's AI model. Each Reading belongs to the reader named above it, and can be constantly evolved as you read, reflect and reread the dialogues.

## License

Text and readings: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Code: MIT. See [LICENSE.md](LICENSE.md).
