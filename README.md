# Replete's Obsidian CSS snippets for Minimal Theme

![Screenshot](_screenshot.png)
<small>Screenshot out of date already..</small>

This is my working folder of CSS snippets for Obsidian using [@kepano](https://github.com/kepan)'s [Minimal Theme](https://github.com/kepano/obsidian-minimal). There are opinionated tweaks and fixes for various plugins and aspects of Obsidian's UI organized into separate CSS files.

### Features
- Editor:
    - [Custom Tag Styles](https://i.imgur.com/Zc9DLFa.png)
    - Editor fixes - gutter component alignments, general editor fixes, less visible indentation guide
    - Typography fixes - alignment fixes for editor, headings, quotes etc
    - Table tweaks (WIP)
- Note styles ('cssclass' frontmatter property note styles):
    - [Daily Note styles](https://i.imgur.com/R28YXn9.png) (WIP)
    - Dashboard styles (WIP) (empty atm)
- Plugin:
    - [Calendar Plugin tweaks](https://i.imgur.com/1Jrvkbl.png)
    - [CardBoard plugin tweaks](https://i.imgur.com/yp7Hxvb.png)
    - [Checklist plugin tweaks](https://i.imgur.com/51Lvbbh.png) - Compact view (for tag mode users)
    - [Database Folder plugin tweaks](https://i.imgur.com/G4TfL3w.png) - compact view
    - [Day Planner plugin tweaks](https://i.imgur.com/xFdbIwe.gif) - I'm using [my own fork](https://github.com/replete/obsidian-day-planner) of this abandoned plugin for more features but the styles here are not dependent on fork changes
    - Full Calendar plugin tweaks - (WIP) pretty hacky due to limits of styling hooks (I stopped using this plugin)
    - [Heatmap Calendar tweaks](https://i.imgur.com/ndvRLIC.png) - colours and text styles for habit type use-case
    - [Make.MD Tweaks](https://i.imgur.com/bn5bfMS.gif) - Quite a lot here mostly banner cssclass overrides
    - [MySnippets plugin](https://i.imgur.com/5E0LyO0.png) - make menu wider and fix button style/order
    - Obsidian Buttons plugin - alignments
    - [Quite Outline tweaks](https://i.imgur.com/XJHUfMk.png) - Remove rainbow colours to theme colors, re-arrange layout
    - [Task progressbars](https://i.imgur.com/eCGkkVD.png) - alignments and colours
- Obsidian UI tweaks:
    - [Collapsible Right Headers](https://i.imgur.com/xFdbIwe.gif)
    - [Compact File Explorer with chevrons on right](https://i.imgur.com/9Kizq2q.png)
    - [Custom Separators](https://i.imgur.com/9Kizq2q.png) - user-configurable CSS for separators, works well with `File Explorer Custom Sorting` plugin
    - Custom Separators (gradient version)
    - Custom Frames tweaks - remove padding
    - General fixes
    - Frontmatter tweaks (styling, fixes for `editor syntax highlighter plugin`)
    - Hide Ribbon - guess what this does
    - [Hide Vault Title in Left Sidebar](https://i.imgur.com/LU98mhD.png)
    - [Compact Outliner styles](https://i.imgur.com/RgTxA7s.png) with chevron on right
    - Resize Handles - more muted theme colours
    - Status bar tweaks - more visible text on dark theme 
    - [Tab Title Bar Bottom](https://i.imgur.com/nedVJ5g.png) - Move the tab title bar to the bottom, vertical statusbar when right sidedock closed
    - Tabs Tweaks - (WIP) More classic style tabs to improve visibility of navigation
    - Tab Title Bar tweaks - Fixes `Commander` plugin icons, condensed icons, tweaks

## My environment


- `MacOS 13.2.1`, ~~Mobile~~ 
- `Obsidian v1.1.15` (official Installer, homebrew unreliable)
- `Minimal Theme v6.3.2`
- Enabled plugins: `['templater-obsidian', 'dataview', 'calendar', 'settings-search', 'cmdr', 'periodic-notes', 'heatmap-calendar', 'obsidian-hide-sidebars-when-narrow', 'hotkeysplus-obsidian', 'obsidian-minimal-settings', 'obsidian-custom-frames', 'open-vscode', 'quickadd', 'mysnippets-plugin', 'obsidian-day-planner', 'dbfolder', 'no-dupe-leaves', 'cm-editor-syntax-highlight-obsidian', 'obsidian-toggle-list', 'custom-sort', 'obsidian-icon-folder', 'omnisearch', 'obsidian-task-progress-bar', 'table-editor-obsidian', 'auto-class', 'make-md', 'nldates-obsidian', 'obsidian-attachment-name-formatting', 'obsidian-tabs', 'obsidian-hotkeys-for-specific-files', 'obsidian-tasks-plugin', 'folder-note-plugin', 'obsidian-hover-editor', 'file-explorer-note-count', 'obsidian-quiet-outline', 'obsidian-fullscreen-plugin']`
```js
[...new Set(app.plugins.enabledPlugins)]
```

## How to use

1. Clone/[fork](https://github.com/replete/obsidian-minimal-theme-css-snippets/fork)/[unzip](https://github.com/replete/obsidian-minimal-theme-css-snippets/archive/refs/heads/main.zip) into `<your vault location>/.obsidian/snippets` 
2. Install the `MySnippets` community [plugin](https://github.com/chetachiezikeuzor/MySnippets-Plugin) and activate snippets individually
![MySnippets plugin screenshot](_mysnippets-screenshot.png)
3. Use what you like, dupe + hack what you don't

## TODO:
- [ ] Fix some colour inconsistencies across light/dark themes
- [ ] Test/fix for Mobile Obsidian (likely near future)
- [x] Test/fix for Windows (no fixes needed!)
- [ ] Test/fix for Linux

## Versions / updates

This repo is updated frequently as I work on my own vault. I aim to keep my environment up to date. When a new Obsidian version breaks things (which hasn't happened yet), I'll tag a release for whatever the last good Obsidian or Minimal Theme version was before it broke, and subsequent commits will be fixes for the current version.

<a href="https://www.buymeacoffee.com/replete"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=replete&button_colour=6a8695&font_colour=ffffff&font_family=Poppins&outline_colour=000000&coffee_colour=FFDD00"></a>