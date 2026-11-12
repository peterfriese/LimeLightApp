# LimeLight

**Markdown-first presentation studio for macOS.**

Write slides in plain Markdown with instant syntax styling, 3-phase `@code` diff choreography, hand-drawn ink callouts, interactive 3D isometric diagrams, and live macOS window & iOS Simulator projection.

---

## Download & Unlock Beta

- **[Download Latest LimeLight Beta (.dmg)](https://github.com/peterfriese/LimeLightApp/releases/latest)**
- Requires **macOS 26.0+** (Apple Silicon)

### Installation & Beta Key Activation
1. Download the `.dmg` from the [latest release](https://github.com/peterfriese/LimeLightApp/releases/latest).
2. Open the disk image and drag **LimeLight.app** to **Applications**.
3. Open the **Sample Decks** folder inside the disk image (or choose **File -> Open LimeLight Showcase Deck** in the app) to explore sample presentations.
4. To unlock unlimited slides with your `LL1-...` Beta Invite Key, choose **LimeLight -> License / Unlock Beta...** (or press `⌘K` and type `License`) and paste your key.

---

## The 60-Second Mental Model

| What You Type in the Editor | Where It Appears |
| :--- | :--- |
| **Unindented paragraphs** | **Teleprompter Only** (Your private spoken script; never projected to the audience) |
| **`# Heading`** or **`⇥ Tab`-indented lines** | **On the 16:9 Stage** (Headings, indented bullets, tables, media, and `@` blocks) |
| **Single Return (`↵`)** between `Tab` lines | **Same Stage Card** (Grouped together inside one visual container) |
| **Blank Line (`↵↵`)** between `Tab` blocks | **Side-by-Side Columns / Bento Grid** (Automatically splits into 2, 3, or 4 columns) |
| **Three Returns (`↵↵↵`)** or `---` | **New Slide Break** |

- **Click any `@` line** (`@code`, `@video`, `@simulator`, `@mermaid`, `@diagram`, `@timeline`, `@qrcode`, or `[^id]` callout) to configure options visually via the **Liquid Glass Flyout Bar**.
- **Press `⌘/` anytime** to open the floating **LimeLight Quick Reference HUD** and insert `@` components or slide recipes in one click.
- **Use Your AI Coding Agent**: Choose **Help -> Install AI Agent Skills...** to install all 4 `limelight-*` skills into **Claude Code**, **Google Antigravity**, **OpenCode & OpenChamber**, or **Cursor** in one click.

---

## Essential Keyboard Shortcuts

| Action | Shortcut |
| :--- | :--- |
| Quick Reference Cheat Sheet HUD | `⌘/` |
| Command Palette | `⌘K` or `⇧⌘P` |
| Play / Stop Presentation | `⌥⌘P` |
| Toggle Windowed Rehearsal Stage | `⇧⌘W` |
| Step Through Slide Builds & `@code` Stages | `⌥⌘←` / `⌥⌘→` |
| New Slide / Duplicate / Skip Slide | `⇧⌘N` / `⇧⌘D` / `⇧⌘H` |
| Show / Hide Slide Navigator | `⌘0` |
| Show / Hide Inspector | `⌥⌘I` |
| Show / Hide Stage Preview Canvas | `⌥⌘↩` |
| Single-Slide Focus vs. Full-Deck Script | `⇧⌘E` |
| Live Stage: Freeze / Blackout / Zoom Loupe | `F` / `B` / `Z` |
| Live Stage: Daylight Rescue (Dark/Light Flip) | `A` / `⇧A` |

---

## Feedback & Bug Reports

Found a bug or have a feature idea?
- **[Open a Bug Report](https://github.com/peterfriese/LimeLightApp/issues/new?template=bug_report.md)**
- **[Request a Feature](https://github.com/peterfriese/LimeLightApp/issues/new?template=feature_request.md)**
- In LimeLight, you can also use **Help -> Reveal Diagnostic Logs in Finder** to attach diagnostic logs to an issue.
