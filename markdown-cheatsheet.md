# Markdown Cheat Sheet

Each line shows what the formatting is for, then what to type to get it.

## Standard Markdown

- Main heading (level 1): `# Heading`
- Subheading (level 2): `## Heading`
- Smaller headings (levels 3 to 6): `### Heading` up to `###### Heading`
- Paragraph: leave a blank line between blocks of text
- Line break within a paragraph: end the line with two spaces, or use `<br>`
- Bold text: `**bold**`
- Italic text: `*italic*` or `_italic_`
- Bold and italic together: `***bold italic***`
- Inline code (commands, filenames): `` `code` ``
- Code block: put ` ``` ` on the line above and the line below the code
- Code block with syntax colouring: ` ```yaml ` (or `bash`, `python`, etc.) on the opening line
- Bullet list: start the line with `- ` or `* `
- Numbered list: start the line with `1. `
- Nested list item: indent the line by two or four spaces
- Quote: start the line with `> `
- Nested quote: start the line with `>> `
- Link: `[link text](https://example.com)`
- Link with hover text: `[link text](https://example.com "hover text")`
- Link to another file in the repo: `[Setup notes](docs/setup.md)`
- Link to a heading on the same page: `[Go to Tables](#tables)`
- Image: `![description](path/to/image.png)`
- Clickable image: `[![description](image.png)](https://example.com)`
- Horizontal divider line: `---` on its own line
- Show a symbol literally instead of formatting: put a backslash before it, e.g. `\*not italic\*`
- Hidden comment (not shown when rendered): `<!-- comment -->`

## GitHub extras

- Strikethrough: `~~crossed out~~`
- Table: `| Column 1 | Column 2 |` then `|---|---|` then `| value | value |`
- Table column alignment: `|:---|` left, `|:---:|` centre, `|---:|` right
- Task list (tickable checkbox): `- [ ] to do` and `- [x] done`
- Automatic link: just paste a URL, e.g. `https://github.com`
- Footnote marker: `Some text[^1]`
- Footnote text: `[^1]: The footnote content` (anywhere in the file)
- Emoji: `:rocket:` or `:white_check_mark:`
- Mention a GitHub user: `@username`
- Link to an issue or pull request: `#123`
- Collapsible section: `<details><summary>Click to expand</summary>` hidden content `</details>`
- Note box: `> [!NOTE]` on the first line, then `> your text`
- Tip box: `> [!TIP]` on the first line, then `> your text`
- Important box: `> [!IMPORTANT]` on the first line, then `> your text`
- Warning box: `> [!WARNING]` on the first line, then `> your text`
- Caution box: `> [!CAUTION]` on the first line, then `> your text`
- Diagram: a code block starting with ` ```mermaid `, e.g. `graph LR; A-->B`
- Maths formula inline: `$E = mc^2$`
- Maths formula on its own line: `$$` on the line above and below the formula
- Keyboard key: `<kbd>Ctrl</kbd> + <kbd>C</kbd>`
- Superscript: `<sup>2</sup>`
- Subscript: `<sub>2</sub>`
