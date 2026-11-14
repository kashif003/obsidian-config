# Obsidian config

My Obsidian settings: themes, CSS snippets, hotkeys, and plugin settings.

## How to install?
1. Install Obsidian and open (or create) your vault folder once, then close Obsidian.
2. Replace the vault's settings with this repo:
   ```bash
   cd /path/to/your/vault
   rm -rf .obsidian
   git clone https://github.com/kashif003/obsidian-config.git .obsidian
   ```
3. Open Obsidian → Settings → Community plugins → click **Turn on community plugins** if asked.
4. Restart Obsidian. Plugins, themes, hotkeys and settings are all back.

To save changes later: `cd .obsidian && git add . && git commit -m "update" && git push`

## Task setup (TaskNotes)
- New tasks go to `Tasks/Open`, finished tasks move to `Tasks/Done` automatically.
- `Alt+T` creates a new task.
