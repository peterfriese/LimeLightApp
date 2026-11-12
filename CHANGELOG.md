# Changelog

All notable changes to **LimeLight** are documented in this file.

## [0.2.0] - 2026-11-12

### Added
- **In-App Quick Reference HUD (`⌘/`)**: Press `⌘/` (or choose `Help -> LimeLight Quick Reference...`) to open a floating visual cheat sheet covering Visibility Inversion (`Tab` vs. Unindented notes), `↵` vs. `↵↵` column splitting, authoring & live stage shortcuts, and 1-click insertion of `@` blocks and slide recipes.
- **1-Click AI Agent Skills Installer**: Install all 4 bundled `limelight-*` skills (`limelight-deck-authoring`, `limelight-code-and-diagrams`, `limelight-live-stage-and-mcp`, `limelight-theme-designer`) into **Claude Code** (`~/.claude/skills`), **Google Antigravity** (`~/.gemini/antigravity/skills`), **OpenCode & OpenChamber** (`~/.config/opencode/skills`), **Cursor** (`~/.cursor/skills`), or any project folder in one click via `Help -> Install AI Agent Skills...` or `⌘K`.
- **Context-Aware Empty-Slide Ghost Hint**: When a slide has speaker notes but zero stage content, the Studio Stage Preview card displays an interactive ghost card with 1-click buttons to indent your note line onto the 16:9 stage (`⇥ Indent First Line to Stage`), add a `# Heading`, open `⌘K Templates`, or launch `? Quick Reference`.
- **Interactive "Try It!" Starter Deck & Conference Recipes**: Upgraded the default `⌘N` 12-slide starter deck with hands-on micro-actions on Slides 1-5, and added 3 conference-proven slide templates (`Scrolling Code Fold`, `Staged Code + Live Device`, and `Annotated Visual Callout`) to the `+` Toolbar Picker and `⌘K`.
- **Code Walkthrough Panning, Folding & Keynote parity**: Added `overflow: pan` 32pt viewport scrolling, `fold: "M-N"` `{ ••• }` code folding pills, `xcode-light` token-box highlights, QR rotation/radius/shadow controls, and standards-compliant SVG CSS normalization.

## [0.1.0] - 2026-10-26

### Added
- **Markdown-First Studio**: Continuous TextKit 2 Markdown editor with live two-way slide stage synchronization and single-slide focus mode (`⇧⌘E`).
- **3-Phase Code Walkthroughs**: Animated `@code` diff choreography with token anchoring and callouts.
- **Hand-Drawn Callouts & Diagrams**: Tapered ink-brush callouts (`^[...]`), interactive 3D isometric diagrams, and Mermaid flowcharts.
- **Live Window & Simulator Projection**: Embed live macOS application windows (`@live-window`) and iOS Simulators (`@live-simulator`) directly inside slides.
- **Presenter Display & Teleprompter**: Dual-display presenter view, windowed rehearsal mode (`⇧⌘W`), and voiceover narration.
- **QuickLook & Finder Thumbnails**: Native macOS `.limelight` QuickLook preview and Finder icon thumbnails.
