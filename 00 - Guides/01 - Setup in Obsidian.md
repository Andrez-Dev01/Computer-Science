# Setup in Obsidian — Beginner Walkthrough

## 1. Open the correct folder
1. Extract `CS-Knowledge-Obsidian-Vault.zip`.
2. In Obsidian, select **Open folder as vault** and choose the extracted `CS-Knowledge-Vault` folder.
3. Open [[START HERE]]. Do **not** open the parent directory containing both vaults as a single vault.


## If you already have an Obsidian vault
- Make a backup of your existing vault first.
- Open this starter as a **separate** vault to explore it, or copy selected subject folders plus `95 - Templates`, `00 - Guides`, and `START HERE.md` into your own vault.
- **Do not overwrite existing notes that share a filename.** If you merge, rename/reconcile conflicting paths first.
- Then point the core Templates plugin to the correct template folder in your destination vault.

## 2. Activate the built-in Templates feature
1. Open **Settings → Core plugins** and enable **Templates**.
2. Under **Settings → Templates**, set **Template folder location** to `95 - Templates`.
3. Create a new note in the section's chapter folder (e.g. `3.2 - General Purpose Registers (Assembly)`).
4. Open the command palette (`Ctrl+P` on Windows/Linux) and use **Templates: Insert template**.
5. Pick **01 - College Section**. At the next topic, insert **02 - Repeatable Topic Block** *inside the same note*.

> [!tip] Basic Markdown
> `#` creates the note title; `##` a topic heading; `###` subheadings; `-` a bullet; `- [ ]` a checkbox. Code uses triple backticks and a language name (`cpp`, `python`, `go`, `asm`, `sql`, `bash`).

## 3. Write while reading
- Keep the textbook open and the section note open.
- When a topic appears, insert the Topic Block and fill its headings as you read. Use your own words; do not copy textbook paragraphs.
- Add professor insights and assignment lessons to the **same topic block**.
- Write complete programs in your programming editor. Record a small relevant snippet plus safe program location/repository URL in your note.

## 4. Start independent learning
- In a subject's `02 - Independent Learning` folder, use **05 - Independent Topic** for research spanning multiple resources.
- Use **06 - Independent Lesson** for a book chapter/video-course lesson with an established order.
- Insert Topic Blocks as needed. Don't automatically write a second quick-reference note.

## 5. Use the optional shared reference
- Create a note in `03 - Quick Reference` only when you repeatedly need to look something up.
- Use **07 - Quick Reference**, summarize briefly, then link your full college/independent notes.

## 6. Optional Obsidian quality-of-life settings
- **Settings → Files and links → Automatically update internal links:** on, if available.
- Use **Search** on the left sidebar. Try `file:registers` and `content:"common errors"`.
- Use **Graph** and **Canvas** only if they help; neither is required to take notes.
- Don't install community plugins on day one. The built-in Templates plugin is sufficient to begin.

## 7. Edit this setup over time
- Rename headings or add fields to templates when a real learning problem demands it.
- Template edits affect **new insertions**, not old notes.
- Existing chapter maps for Assembly are scaffolds; replace labels with your actual textbook's headings. Do not assume this pack knows your book's actual table of contents.
