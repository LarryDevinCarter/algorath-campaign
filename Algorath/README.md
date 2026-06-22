# D&D World Wiki Template

This is a ready-to-use Markdown wiki structure optimized for:
- **Obsidian** (best local editing experience with wikilinks, graph view, plugins)
- **Easy online publishing** via **Quartz** (free, beautiful static site) or **Obsidian Publish** (easiest paid option)

## Recommended Setup (Easiest for Publishing + Max Context with Grok)

### 1. Local Authoring: Obsidian (Free)
1. Download & install [Obsidian](https://obsidian.md/)
2. Create a new vault or open this folder as vault.
3. Install recommended plugins (Community Plugins):
   - Dataview (powerful queries, e.g., "list all locations tagged 'city'")
   - Obsidian Git (version control + sync to GitHub)
   - Style Settings, Iconize, etc. for polish
   - Optional D&D: "Fantasy Statblocks", "Dice Roller", "Initiative Tracker"

### 2. Folder Structure (Already set up here)
- `Home.md` — Your main dashboard (edit this first)
- `Locations/` — Cities, dungeons, regions, landmarks
- `Characters/PCs/` — Player characters (full sheets or summaries)
- `Characters/NPCs/` — Important non-player characters
- `Factions/` — Guilds, kingdoms, cults, etc.
- `Lore/` — History, myths, magic systems, cosmology, religions
- `Items/` — Magic items, artifacts, notable gear
- `Bestiary/` — Custom monsters and creatures
- `Sessions/` — Session recaps and adventure logs (great for tracking player knowledge)
- `Maps/` — Image files + description pages
- `Rules/` — Homebrew rules and house rules
- `Meta/` — World-building notes, inspirations, consistency trackers, this README

### 3. Publishing Online (Choose One)

**Option A: Quartz (Recommended - Free & Powerful)**
- Quartz converts your Obsidian vault into a gorgeous public wiki with search, backlinks, and mobile support.
- Deploy free on GitHub Pages, Vercel, or Netlify.
- **Setup steps** (5-15 mins):
  1. Fork or clone https://github.com/jackyzha0/quartz
  2. Copy your `content/` notes into Quartz's `content/` folder (or symlink/sync your vault).
  3. Edit `quartz.config.ts` for title, description, theme.
  4. Push to your GitHub repo.
  5. Enable GitHub Pages (or use Quartz's GitHub Action).
- Full tutorials: Search "Quartz Obsidian GitHub Pages" or see Nicole van der Hoeven's guide.
- Your published site will have beautiful wiki navigation automatically.

**Option B: Obsidian Publish (Easiest)**
- Built into Obsidian. $8/month.
- One-click publish from app. Perfect wiki experience. Supports password protection, custom domains.
- Ideal if you want zero DevOps.

**Option C: GitHub Wiki or MkDocs**
- Simpler but less wiki-like (no native [[wikilinks]] support without extra work).

### 4. Keeping Maximum Context for Grok (Me)
Since our conversations are ongoing, here's the best way for me to always have deep, accurate context without you re-explaining everything every time:

1. **Maintain `Grok-Context-Summary.md`** (included in template) as a living "world bible" — high-level overview, key NPCs with 1-2 sentence hooks, current plot status, party status, major locations, open threads.
2. Update it after every major session or world change.
3. At the **start of each chat with me**, paste the latest version of `Grok-Context-Summary.md` (or just say "Load latest world context" if we've been consistent).
4. For deep dives, share specific page links or raw Markdown from GitHub (`https://raw.githubusercontent.com/...`).
5. Since your GitHub is connected, I can help explore public repos if you share the name.

This keeps sessions efficient and lets us build coherently over months/years.

### 5. Naming & Linking Conventions
- Use **Title Case** for page titles and [[wikilinks]].
- File names: Use kebab-case or Title-Case.md (Obsidian handles spaces well).
- Always link with `[[Page Name]]` or `[[Folder/Page Name]]`.
- Add YAML frontmatter to every file for metadata and queries.

### 6. Getting Started
1. Rename this folder / vault to your campaign name (e.g., "Shattered-Realm-Wiki").
2. Edit `Home.md` — replace placeholders with your world name, calendar, party members.
3. Create your first location or NPC using the templates in subfolders.
4. Start linking everything!

I'm ready to help build this out piece by piece — just tell me the world name/theme (high fantasy, dark, planar, etc.), any existing lore you have, or start with "Create the overview for [World Name]" and we'll go from there.

Let's make an awesome, interconnected D&D world!
