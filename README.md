# Replete's Obsidian CSS snippets for Minimal Theme

![Screenshot](_screenshot.png)
<small>Screenshot out of date already..</small>

This is my working folder of CSS snippets for Obsidian using [@kepano](https://github.com/kepan)'s [Minimal Theme](https://github.com/kepano/obsidian-minimal). There are opinionated tweaks and fixes for various plugins and aspects of Obsidian's UI organized into separate CSS files.

### Features
- Editor:
    - [Custom Tag Styles](https://i.imgur.com/Zc9DLFa.png)
    - Editor fixes - gutter component alignments, general editor fixes, less visible indentation guide
    - Frontmatter tweaks (styling, fixes for `editor syntax highlighter plugin`)
    - Table tweaks (WIP)
    - [Top Fade](https://i.imgur.com/Q0AYg0m.png) - Visual tweak to remove harsh edge of content when using one of the positional Tab Header snippets
    - Typography fixes - alignment fixes for editor, headings, quotes etc (WIP)
- Note styles ('cssclass' frontmatter property note styles):
    - [Daily Note styles](https://i.imgur.com/R28YXn9.png) (WIP)
- Plugin:
    - [Calendar Plugin tweaks](https://i.imgur.com/1Jrvkbl.png)
    - [CardBoard plugin tweaks](https://i.imgur.com/yp7Hxvb.png) (WIP)
    - [Checklist plugin tweaks](https://i.imgur.com/51Lvbbh.png) - Compact view (for tag mode users)
    - Custom Frames tweaks - remove padding
    - [Database Folder plugin tweaks](https://i.imgur.com/G4TfL3w.png) - compact view
    - [Day Planner plugin tweaks](https://i.imgur.com/xFdbIwe.gif) - I'm using [my own fork](https://github.com/replete/obsidian-day-planner) of this abandoned plugin for more features but the styles here are not dependent on fork changes, yes its still buggy
    - Excalidraw plugin fixes - fix invisible UI in dark theme
    - Full Calendar plugin tweaks - pretty hacky due to limits of styling hooks (I stopped using this plugin)
    - [Heatmap Calendar tweaks](https://i.imgur.com/ndvRLIC.png) - colours and text styles for habit type use-case (I don't use this anymore)
    - [Make.MD Banner tweaks](https://i.imgur.com/bn5bfMS.gif) - Mostly banner cssclass overrides, gradient, blur, tall, short etc (WIP)
    - Make.MD Compact Spaces - use less space, like Compact File Explorer snippet
    - [MySnippets plugin](https://i.imgur.com/5E0LyO0.png) - make menu wider and fix button style/order
    - Obsidian Buttons plugin - alignments
    - [Outline tweaks](https://i.imgur.com/RgTxA7s.png) chevron on right, compact
    - [Quiet Outline tweaks](https://i.imgur.com/XJHUfMk.png) - Remove rainbow colours to theme colors, re-arrange layout
    - [Task progressbars](https://i.imgur.com/eCGkkVD.png) - alignments and colours
- Obsidian UI tweaks:
    - [Collapsible Right Headers](https://i.imgur.com/xFdbIwe.gif)
    - [Compact File Explorer with chevrons on right](https://i.imgur.com/9Kizq2q.png) - also makes attachment folders less visible
    - Compact Tab Header - Compact view, fixes `Commander` plugin icon colours
    - [Compact Tabs](https://i.imgur.com/Xx15IVB.png) - Compact cleaner tabs, better for smaller screens
    - [Compact Tabs (pill style)](https://i.imgur.com/SYaJkI9.png) - Firefox like pill tabs, looks a bit weird for me but you might like it
    - [Custom Separators](https://i.imgur.com/9Kizq2q.png) - user-configurable CSS for separators, works well with `File Explorer Custom Sorting` plugin
    - Custom Separators (gradient version)
    - [Floating Tab Header](https://i.imgur.com/mAJuEpl.gif) - Save space with this float right leaf tab header (show navigation, breadcrumb on hover/focus)
    - Hide Ribbon
    - [Hide Vault Title in Left Sidebar](https://i.imgur.com/LU98mhD.png)
    - Resize Handles - more muted theme colours
    - Status bar tweaks - more visible text on dark theme 
    - [Tab Header on bottom](https://i.imgur.com/nedVJ5g.png) - Move the tab title bar to the bottom, vertical statusbar when right sidedock closed

## My environment


- `MacOS 13.2.1`, ~~Mobile~~ 
- `Obsidian v1.1.16` (official Installer, homebrew unreliable)
- `Minimal Theme v6.3.2`
- Enabled plugins: `['templater-obsidian', 'dataview', 'calendar', 'settings-search', 'cmdr', 'periodic-notes', 'heatmap-calendar', 'obsidian-hide-sidebars-when-narrow', 'hotkeysplus-obsidian', 'obsidian-minimal-settings', 'obsidian-custom-frames', 'open-vscode', 'quickadd', 'mysnippets-plugin', 'obsidian-day-planner', 'dbfolder', 'no-dupe-leaves', 'custom-sort', 'obsidian-icon-folder', 'omnisearch', 'auto-class', 'make-md', 'nldates-obsidian', 'obsidian-attachment-name-formatting', 'obsidian-tabs', 'obsidian-hotkeys-for-specific-files', 'folder-note-plugin', 'obsidian-hover-editor', 'file-explorer-note-count', 'obsidian-quiet-outline', 'obsidian-fullscreen-plugin', 'obsidian-checklist-plugin', 'cm-editor-syntax-highlight-obsidian', 'obsidian-list-callouts', 'obsidian-toggle-list', 'obsidian-excalidraw-plugin', 'obsidian-task-progress-bar', 'obsidian-custom-attachment-location', 'obsidian-smart-typography', 'obsidian-tasks-plugin', 'custom-classes']`
```js
[...new Set(app.plugins.enabledPlugins)]
```

## How to use

1. Clone/[fork](https://github.com/replete/obsidian-minimal-theme-css-snippets/fork)/[unzip](https://github.com/replete/obsidian-minimal-theme-css-snippets/archive/refs/heads/main.zip) into `<your vault location>/.obsidian/snippets` 
2. Install the `MySnippets` community [plugin](https://github.com/chetachiezikeuzor/MySnippets-Plugin) and activate snippets individually
![MySnippets plugin screenshot](_mysnippets-screenshot.png)
3. Use what you like, dupe + hack what you don't

## TODO:
- [ ] Fix the weird list item alignments that vary depending on file length
- [ ] Test/fix for Mobile Obsidian (likely near future)
- [x] Fix some colour inconsistencies across light/dark themes
- [x] Test/fix for Windows (no fixes needed at time)
- [x] Test/fix for Linux (no fixes needed at time)

## Versions / updates

This repo is updated frequently as I work on my own vault. I aim to keep my environment up to date. When a new Obsidian version breaks things (which hasn't happened yet), I'll tag a release for whatever the last good Obsidian or Minimal Theme version was before it broke, and subsequent commits will be fixes for the current version.

<a href="https://www.buymeacoffee.com/replete"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=replete&button_colour=BD5FFF&font_colour=ffffff&font_family=Poppins&outline_colour=000000&coffee_colour=FFDD00" /></a>