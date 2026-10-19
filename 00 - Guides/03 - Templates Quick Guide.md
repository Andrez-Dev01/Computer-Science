# Templates — Which One and When?

**Templates are copy-in snippets, not separate files you must maintain.** The `95 - Templates` folder stores originals. A newly created study note receives the contents of a template when you insert it.

| Template | Use when | Where |
|---|---|---|
| 01 - College Section | Studying one real textbook section | Subject → 01 - College Courses → Course → Chapter |
| 02 - Repeatable Topic Block | Another topic appears in the same section; insert at cursor | Inside College Section or Independent Lesson |
| 03 - Course Home | Starting a new college class | Subject → 01 - College Courses → Class |
| 04 - Chapter Map | Starting a chapter, before you know every section | Within the class's Chapter NN folder |
| 05 - Independent Topic | Researching a topic from multiple sources | Subject → 02 - Independent Learning |
| 06 - Independent Lesson | Following a course, documentation tutorial, video, or book | Subject → 02 - Independent Learning |
| 07 - Quick Reference | Need a concise lookup page | Subject → 03 - Quick Reference |
| 08 - Coding Experiment Block | Running a separate small program or troubleshooting | Insert inside the relevant note, only when useful |
| 09 - Topic Error Log Block | Multiple error/fix cases within one topic | Insert inside the relevant topic |

## Template shortcut workflow
1. Create note in the correct folder and name it before inserting a template.
2. Run **Templates: Insert template**.
3. Replace `[instructions in square brackets]` and remove unused help text.
4. For each new topic in the same note, insert **02 - Repeatable Topic Block**.
5. The built-in Templates plugin supports `{{title}}`, `{{date}}`, `{{time}}`. It does **not** support advanced custom variables by default.

## Naming conventions
- College section: `4.2 - Loops and Iteration (C++).md` — the number is the **actual** textbook section.
- Structured independent lesson: `03 - Docker Networking (Course Name).md`.
- Independent research: `Python - Decorators.md` or `Docker - Container Networking.md`.
- Quick reference: `C++ - Loop Patterns.md`.
- Avoid two files with exactly the same title when you want to use short `[[wikilinks]]`.

If you have to copy entire explanatory paragraphs into a reference note, you're duplicating too much. Keep the full explanation in the primary study note.
