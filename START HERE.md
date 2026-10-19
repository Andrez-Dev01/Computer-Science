# Start Here

**This vault is for learning computer science.** You do not need to maintain indexes, dashboards, or a different note for every concept.

## Where to put a note

- **Taking a class?** Open `Courses` → your class → its chapter. Each **textbook section is one note**. Its subsections are **headings inside that note**, not separate files.
- **Learning on your own?** Open the relevant subject folder (Python, DSA, Software Engineering, AI, DevOps, etc.) and make one note for the topic or lesson.
- **Programming projects?** Keep the full projects in your **separate Projects vault**. In these learning notes, use short code examples and optionally mention the real source-file path.

## Create your first textbook section note

1. Open `Courses/Assembly Language/Chapter 02` (or the chapter you are studying).
2. Create a new note. Name it **exactly by its real section**: `2.2 - Your Section Title`. (Do not assume the demo section titles are from your book.)
3. In **Settings → Core plugins**, enable **Templates**. In **Settings → Templates**, set the folder to `Templates`.
4. Open your new note, run **Templates: Insert template** from the Command palette, and select `Textbook Section`.
5. Change the first `##` heading to your textbook's first actual subsection, such as `2.2.1 — First Subsection`.
6. Read a little, write your explanation, add vocabulary or code where it helps, and create the next `##` subsection heading when you reach it.

**You do not need to fill in all the suggested blocks for every subsection.** Add what the material actually needs. Your textbook's subsections are the organization, not a checklist of seven identical fields.

## How headings work in Obsidian

| Markdown you type | What it means |
| --- | --- |
| `# 2.2 — CPU Registers` | The section's big title (one per file) |
| `## 2.2.1 — What are registers?` | A textbook subsection **inside** that file |
| `### Worked example` | Smaller detail inside the current subsection |
| `**important phrase**` | Bold text |
| Three backticks, `cpp`, your code, then three closing backticks | A C++ code block (use `python`, `go`, or `asm` for other languages) |
| `> [!warning] Common mistake` | A visibly distinct callout box |

Under **Settings → Core plugins**, ensure **Outline** is enabled, then open the Outline panel in the sidebar. Click a subsection to jump directly to it **without creating another file**.

For a clean writing experience, try **Settings → Editor → Default editing mode → Live Preview**.

## What the visual blocks mean

> [!info] Key words
> A definition or important term, only if the section contains vocabulary.

> [!example] Why this example matters
> An explanation of what a short code snippet demonstrates. Put runnable code in a normal fenced code block beneath it.

> [!warning] Common mistake
> A bug, misconception, or unsafe assumption and how to fix it.

> [!tip] My experiment
> What you changed in your editor, what you predicted, and what happened.

These callouts are built into Obsidian—**no extra plugins or styling files are required**.

## Two templates only

- `Templates/Textbook Section.md` — one section note with as many `##` textbook subsections as you need.
- `Templates/Independent Topic.md` — one note for a self-studied topic, tutorial, or technical concept.

Look at `Courses/Assembly Language/Chapter 02/EXAMPLE - 2.2 CPU Registers.md` for a complete, visually distinct example. **The section number and headings in the demo are illustrative, not claimed to match your textbook.**

## Public GitHub reminder

The learning vault is intended to be **public**. Write in your own words, link to sources where useful, and check everything before publishing. Never upload paid textbook pages, restricted class materials, passwords, or private assets. `.gitignore` only blocks *untracked* matching files; it does not erase files already committed or content pasted into Markdown. Keep your full programming projects in their **separate vault**.

**Git syncing has not been configured.** This is the starting vault only; publishing and mobile syncing are separate setup steps.
