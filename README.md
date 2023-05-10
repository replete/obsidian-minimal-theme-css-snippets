# Obsidian CSS snippets for Minimal Theme

![Screenshot](screenshots/screenshot.png)

My working folder of CSS snippets for Obsidian configured with the [Minimal Theme](https://github.com/kepano/obsidian-minimal). The purpose is to both visually harmonize the style of various plugins with the theme (and its colour schemes) while also extending Obsidian UI possibilities, incorporating a preference for increased UI density. Updated regularly. Screenshots below.


## How to use

1. Clone/[fork](https://github.com/replete/obsidian-minimal-theme-css-snippets/fork)/[unzip](https://github.com/replete/obsidian-minimal-theme-css-snippets/archive/refs/heads/main.zip) into `<your vault location>/.obsidian/snippets` or use 'Snippet Downloader' plugin
2. (recommended) Install the [MySnippets plugin](https://github.com/chetachiezikeuzor/MySnippets-Plugin) via 'Community plugins' to more easily manage snippets
![MySnippets plugin screenshot](screenshots/mysnippets.png)
3. Use what you like, dupe + hack what you don't
4. Update periodically, as this repo is unversioned and actively developed


<a href="https://www.buymeacoffee.com/replete"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=replete&button_colour=BD5FFF&font_colour=ffffff&font_family=Poppins&outline_colour=000000&coffee_colour=FFDD00" /></a>


## My environment

- `MacOS 13.3.1`, ~~Mobile~~ (not tested/fixed yet)
- `Obsidian v1.2.8 (installer 1.2.7)`, if installer < 1.1.8 reinstall from official installer to update electron for updated CSS features like `:has()` - homebrew update didn't work for this version)
- `Minimal Theme v6.3.3`
```js
Enabled plugins: ['obsidian-advanced-uri', 'obsidian-attachment-name-formatting', 'auto-class', 'calendar', 'chatgpt-md', 'obsidian-checklist-plugin', 'cmdr', 'obsidian-contextual-typography', 'obsidian-custom-attachment-location', 'custom-sort', 'obsidian-custom-frames', 'dataview', 'obsidian-day-planner', 'dbfolder', 'draw-harada-method', 'folder-note-plugin', 'obsidian-hide-sidebars-when-narrow', 'hotkeysplus-obsidian', 'obsidian-hover-editor', 'obsidian-icon-folder', 'obsidian-excalidraw-plugin', 'cm-editor-syntax-highlight-obsidian', 'obsidian-minimal-settings', 'obsidian-meta-bind-plugin', 'open-in-new-tab', 'open-vscode', 'periodic-notes', 'quickadd', 'obsidian-quiet-outline', 'obsidian-smart-typography', 'obsidian-style-settings', 'obsidian-task-progress-bar', 'obsidian-tasks-plugin', 'templater-obsidian', 'obsidian-toggle-list', 'make-md', 'mysnippets-plugin', 'nldates-obsidian', 'no-dupe-leaves', 'file-explorer-note-count', 'obsidian-columns', 'ob-table-enhancer']
// [...new Set(app.plugins.enabledPlugins)]
```

## Editor Snippets
- **Custom Tag Styles**
    ![Custom tag styles screenshot](screenshots/custom-tags.png)
- **Editor fixes** - gutter component alignments, general editor fixes, less visible indentation guide
- **Frontmatter tweaks** - styling, fixes for `editor syntax highlighter plugin`
- **Table tweaks** - WIP
- **Top Fade** - Remove harsh edge of content when using one of the positional Tab Header snippets
![Top fade screenshot](screenshots/top-fade.png)
- **Typography fixes** - alignment fixes for editor, headings, quotes etc (WIP)
## UI snippets:
- **Collapsible Right Headers** - Hide panel headers until hover in the right sidebar   
    ![Collapsible right headers screenshot](screenshots/collapsible-header.gif)
- **Compact File Explorer with chevrons on right** - also makes attachment folders less visible    
    ![Compact File Explorer screenshot](screenshots/compact-file-explorer.png)
- **Compact Tab Header** - Compact icons in toolbar, also fixes `Commander` plugin icon colours    
    ![Compact Tab Header screenshot](screenshots/compact-tab-header.png)
- **Compact Tabs** - Compact firefox-style pill tabs, better for smaller screens     
    ![Compact Tabs screenshot](screenshots/compact-tabs.png)
- **Compact Tabs (classic)** - Compact classic tabs, better for smaller screens    
    ![Compact Tabs classic screenshot](screenshots/compact-tabs-classic.png)
- **Custom Separators** - user-configurable CSS for separators, works well with `File Explorer Custom Sorting` plugin    
    ![Custom Separator screenshot](screenshots/custom-separators.png)
- **Custom Separators (gradient)** - user-configurable CSS for separators, works well with `File Explorer Custom Sorting` plugin    
    ![Custom Separators (gradient) screenshot](screenshots/custom-separators-gradient.png)
- **Floating Tab Header** - Save space with this float right leaf tab header (show navigation, breadcrumb on hover/focus)    
    ![Floating Tab Header screenshot](screenshots/floating-tab-header.gif)
- **Floating Tab Header (mini)** - Save even more space with this float right leaf tab header (show navigation, breadcrumb on hover/focus)    
    ![Floating Tab Header (mini) screenshot](screenshots/floating-tab-header-mini.gif)
- **Hide Ribbon**
- **Hide Vault Title in Sidebar**
- **Resize Handles - prefer more muted theme colours**
- **Restrict Last Right Sidebar  Panel (e.g. for calendar plugin)** - Sets max-height on last right sidebar panel, saving you from constantly resizing the panel when resizing windows    
![Restrict last right sidebar panel screenshot](screenshots/restrict-last-right-sidebar-panel.png) 
- **Status bar tweaks** - more visible text on dark theme 
- **Tab Header on bottom** - Move the tab title bar to the bottom, vertical statusbar when right sidedock closed
    ![Tab Header on Bottom screenshot](screenshots/tab-header-bottom.png)
- **Translucent Tab Header** - Classic style tab header showing blurred document content underneath
    ![Translucent Tab Header screenshot](screenshots/tab-header-translucent.png)
### User Snippets:
- **Daily Note styles** - supporting styles for my daily note template, scoped to notes with `cssclass: dailynote` in frontmatter
- **Themed accents** - Custom accent colours for each minimal theme subtheme 
    ![Themed Accents screenshot](screenshots/accents.gif)

### Plugin snippets
- **Calendar** - Compact, weekend, day styles, colours    
    ![Calendar screenshot](screenshots/calendar.png)
- **CardBoard** - Compact styles, waiting on feature update so WIP
    ![CardBoard screenshot](screenshots/cardboard.png)
 
- **Checklist (Ultra compact)** - Compact view (for tag mode users)    
    ![Checklist (ultra compact) screenshot](screenshots/checklist.png)
- **Custom Frames** - Compact panel
- **Custom Frames (Duotone)** - blend custom frames content in with theme until hover    
    ![Custom Frames - Duotone screenshot](screenshots/custom-frames-duotone.png)
- **Database Folder (Compact)** - compact view    
    ![Database Folder screenshot](screenshots/dbfolder.png)
- **Day Planner** - I'm using [my own fork](https://github.com/replete/obsidian-day-planner) of this abandoned plugin for more features but the styles here are not dependent on fork changes, yes its still buggy    
    ![Day Planner screenshot](screenshots/dayplanner.png)
- **Make.MD Contexts** - Compact Make.md Contexts, tidier layout   
    ![Make.MD Contexts screenshot](screenshots/makemdcontexts.png)
- **Make.MD Contexts: Auto-hide properties** - Hide file properties until hover    
    ![Make.MD Contexts autohide screenshot](screenshots/makemdcontextsautohide.gif)

- **Make.MD Contexts: Duotone Banner** - Makes all banner images duotone to match minimal theme    
    ![Make.MD Contexts Duotone banners screenshot](screenshots/makemdcontextsbannerduotone.png)
- **Make.MD Contexts: Gradient Banner**  Fade images to background with a gradient    
    ![Make.MD Contexts Gradient banners screenshot](screenshots/makemdcontextsbannergradient.png)
- **MySnippets** - make menu wider and fix button style/order    
    ![MySnippets tweaks screenshot](screenshots/mysnippets_tweaks.png)
- **Outline** - chevron on right, compact    
    ![Outline tweaks screenshot](screenshots/outline.png)
- **Quiet Outline** - Remove rainbow colours to theme colors, re-arrange layout
    ![Quiet Outline plugin tweaks screenshot](screenshots/quietoutline.png)
- **Task progressbars** - alignments and colours
    ![Task Progressbars plugin tweaks screenshot](screenshots/taskprogressbars.png)
    
## Abandoned snippets (no longer developed)
- **Heatmap Calendar** - colours and text styles for habit type use-case [(imgur screenshot)](https://i.imgur.com/ndvRLIC.png)
- **Full Calendar** - pretty hacky due to limits of styling hooks
- **Obsidian Buttons** - alignments

## Deprecated snippets (deleted from repo)
- ~~[Make.MD Banner](https://i.imgur.com/bn5bfMS.gif) - Mostly banner cssclass overrides, gradient, blur, tall, short etc - I refactored/improved this into separate snippets above~~
- ~~Make.MD Compact Spaces - use less space, like Compact File Explorer snippet (deprecated)~~
## Versions / updates

This repo is updated frequently as I work on my own vault. I aim to keep my environment up to date. When a new Obsidian version breaks things (which hasn't happened yet), I'll tag a release for whatever the last good Obsidian or Minimal Theme version was before it broke, and subsequent commits will be fixes for the current version.

<a href="https://www.buymeacoffee.com/replete"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=replete&button_colour=BD5FFF&font_colour=ffffff&font_family=Poppins&outline_colour=000000&coffee_colour=FFDD00" /></a>

## TODO
- [ ] Fix the weird list item alignments that vary depending on file length
- [ ] Test/fix for Mobile Obsidian (likely near future)
- [x] Fix colour inconsistencies across light/dark themes
- [x] Test/fix for Windows (no fixes needed at time)
- [x] Test/fix for Linux (no fixes needed at time)

