# Before Publishing This Public Vault

> [!danger] Assume every committed Markdown file is public
> `.gitignore` prevents only **untracked** matching files from being added normally. It cannot censor copyrighted paragraphs, private paths, credentials, personal information, or copied assignment text embedded in a tracked `.md` file. Deleting a secret in a later commit does not necessarily remove it from history.

## Allowed content examples
- Your own summaries in your words; original explanations and diagrams.
- Your own short, tested code examples (respect course/assignment restrictions).
- Citations and hyperlinks to official documentation and original sources.
- Publicly shareable images kept in `90 - Assets/00 - PUBLIC - ORIGINAL DIAGRAMS`.

## Keep OUT of the public repository
- Paid textbook pages, scans, course PDFs, copyrighted instructor slides, subscription-only documents, and copies of restricted assignment material.
- Student IDs, grades, instructor-only materials, credentials, tokens, `.env` files, and private links.
- Confidential work data or details from commercial projects; those belong outside this vault.
- Entire project repositories — your **Software Projects** vault is separate.

## Safe placement
- Private local attachments: `90 - Assets/99 - PRIVATE - LOCAL ONLY` (ignored).
- Public original diagrams: `90 - Assets/00 - PUBLIC - ORIGINAL DIAGRAMS` (included when added).
- Paid/source documents are ignored by extension as a precaution, **but not all restricted content can be identified by filename**.
- The README and `.gitignore` are public too; always inspect them.

## Before the first push
1. Create a **new empty public GitHub repository** only after you've reviewed this folder; do not mix it with your Software Projects repo.
2. In a terminal inside `CS-Knowledge-Vault`, run `git init` (only if it is not already a repo).
3. Run `git add .` and **inspect the proposed files** with `git status --short` and `git diff --cached --name-only` before committing.
4. To inspect the actual staged text, use `git diff --cached` and search for sensitive strings.
5. Commit and add the remote only after verifying what's being published.
6. Check the resulting GitHub repository as a stranger would.

> [!warning] Already tracked a file you now want ignored?
> `git rm --cached "path/to/file"` stops tracking it in future commits, but **prior public Git history remains accessible**. For sensitive data, revoke/rotate credentials and follow GitHub's sensitive-data removal guidance.

## `.gitignore` caveat
Because this is intended to be public, common PDF/doc/archive formats and images outside the deliberately public image folder are ignored by default. Ignored local content is **not synchronized by Git**, so don't rely on GitHub for backing it up.

## Licensing
Being publicly visible does not automatically grant others the right to reuse your notes. Decide whether to add an explicit license later; do not automatically assume textbook content is redistributable.
