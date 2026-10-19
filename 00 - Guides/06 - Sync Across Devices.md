# Git/GitHub Sync Across Windows, Ubuntu, Android, and Tablet

**Preference:** automatic Git-backed synchronization with version history, without manually typing Git commands during everyday studying.

## What is included in this starter?
- Portable Markdown note files, a `.gitignore`, and reusable templates.
- **No configured credentials, remote, automatic background jobs, or GitHub repo.** Those must be set up on your devices; we avoid shipping a broken or unsafe sync setup.

## Desktop-first approach
1. Inspect files for public safety; create your own public repo on GitHub.
2. Clone the same repository on each computer or connect the local vault to its remote.
3. After reliable manual pull/commit/push is verified, consider the **Obsidian Git** community plugin for scheduled desktop pull/backup/push.
4. Use a test note to check that edits made on Ubuntu appear on Windows and vice versa.
5. Let one device finish syncing before editing the same file elsewhere.

## Android/tablet warning
The Obsidian Git plugin's maintainers describe **mobile support as experimental and unstable**, with authentication, performance, and repository-size limitations. Don't assume desktop auto-sync settings will work on every mobile device.

Test mobile synchronization with a disposable note *before* relying on it. A different mobile-friendly sync service combined with Git for desktop version history may be more reliable if mobile Git proves problematic, but avoid syncing the same vault through two competing tools without understanding their conflict handling.

## Avoid common sync problems
- Keep the main learning vault relatively small; do not commit PDFs, large recordings, build artifacts, or private assets.
- Do not edit the same note simultaneously on two offline devices.
- Git only syncs **tracked** files. Ignored local-only attachments stay local unless backed up separately.
- `.obsidian/` device settings are ignored in this starter; configure preferred plugins/settings per device.

## Reference links
- Obsidian Git project: https://github.com/Vinzent03/obsidian-git
- Obsidian's Templates documentation: https://obsidian.md/help/Plugins/Templates
