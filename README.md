# Awesome Obsidian [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A massive, curated guide to the [Obsidian](https://obsidian.md/) ecosystem—covering essential plugins, themes, CSS snippets, publishing engines, CLI workflows, companion apps, converters, starter vaults, and developer tools.

**Legend:** `⭐` Essential / Foundational | `🖥️` Desktop Only | `🌐` Official Tool

---

## Table of Contents

* [Official Ecosystem Tools](#official-ecosystem-tools)
* [Community Plugins](#community-plugins)
  * [Essentials & Power Tools](#essentials--power-tools)
  * [Note Creation, Properties & Templating](#note-creation-properties--templating)
  * [Task & Project Management](#task--project-management)
  * [Calendar & Daily Notes](#calendar--daily-notes)
  * [Knowledge Management & PKM](#knowledge-management--pkm)
  * [Visual Thinking, Canvas & Diagrams](#visual-thinking-canvas--diagrams)
  * [Editor & Writing Enhancements](#editor--writing-enhancements)
  * [UI, Layout & Navigation](#ui-layout--navigation)
  * [Data, Databases & Spreadsheets](#data-databases--spreadsheets)
  * [AI, LLMs & Automation](#ai-llms--automation)
  * [Read-It-Later, Citations & Sync](#read-it-later-citations--sync)
  * [Academic, Math & Science](#academic-math--science)
  * [Media, PDF & Attachments](#media-pdf--attachments)
  * [Developer & Code Tools](#developer--code-tools)
  * [Backup, Security & Maintenance](#backup-security--maintenance)
* [Themes](#themes)
* [CSS Snippets & Collections](#css-snippets--collections)
* [Publishing & Digital Gardens](#publishing--digital-gardens)
* [External Companion Apps, Launchers & Mobile](#external-companion-apps-launchers--mobile)
* [Importers & Converters](#importers--converters)
* [Starter Vaults & Template Kits](#starter-vaults--template-kits)
* [Plugin & Theme Development](#plugin--theme-development)
* [Community & Learning Resources](#community--learning-resources)

---

## Official Ecosystem Tools

First-party tools maintained by the Obsidian team that extend the core application.

* **[Obsidian Web Clipper](https://obsidian.md/clipper)** `🌐` `⭐` — Free, open-source browser extension (Chrome, Firefox, Safari, Edge) to highlight web pages, extract Schema.org/meta variables, and save clean offline Markdown using custom templates.
* **[Obsidian CLI](https://obsidian.md/cli)** `🌐` `🖥️` `⭐` — Official command-line interface and TUI (introduced in v1.12) to search vaults, append to daily notes, manage properties/tags, inspect backlinks, and automate workflows safely through Obsidian's internal API.
* **[Obsidian Sync & Headless Sync](https://obsidian.md/sync)** `🌐` — End-to-end encrypted multi-device synchronization with version history, shared vaults, and a headless CLI client for servers and automated publishing pipelines.
* **[Obsidian Publish](https://obsidian.md/publish)** `🌐` — First-party hosting service for turning notes into a fast, graph-enabled public wiki or digital garden.
* **[Obsidian Bases](https://help.obsidian.md/Bases)** `🌐` `⭐` — Core database functionality turning folders and YAML properties into native table and card views without external plugins.
* **[Obsidian Canvas](https://obsidian.md/canvas)** `🌐` `⭐` — Native infinite spatial canvas for laying out notes, media, web pages, and cards visually using the open [JSON Canvas](https://jsoncanvas.org/) format.
* **[Obsidian Importer](https://github.com/obsidianmd/obsidian-importer)** `🌐` — Official plugin for migrating notes from Notion, Evernote, OneNote, Apple Notes, Bear, Roam Research, Google Keep, and HTML/Markdown archives.

---

## Community Plugins

> **Note:** Browse and install these inside Obsidian via **Settings → Community plugins → Browse**.

### Essentials & Power Tools

* **[Dataview](https://github.com/blacksmithgu/obsidian-dataview)** `⭐` — Treat your vault as a database using SQL-like queries (`DQL`) or JavaScript (`DataviewJS`) to generate dynamic tables, lists, and task views.
* **[Templater](https://github.com/SilentVoid13/Templater)** `⭐` — Advanced templating engine supporting JavaScript execution, system commands, cursor placement, and dynamic file manipulation.
* **[QuickAdd](https://github.com/chhoumann/quickadd)** `⭐` — Rapidly capture notes, append text to specific headings, and chain multi-step macros bound to hotkeys.
* **[Omnisearch](https://github.com/scambier/obsidian-omnisearch)** `⭐` — Fast, relevance-weighted search engine for large vaults with built-in OCR for images and PDFs.
* **[Style Settings](https://github.com/mgmeyers/obsidian-style-settings)** `⭐` — Exposes user-friendly UI toggles, sliders, and color pickers for themes and CSS snippets.
* **[Commander](https://github.com/phibr0/obsidian-commander)** — Add custom commands and macros to the ribbon, file menu, tab bar, page header, or status bar.
* **[Linter](https://github.com/platers/obsidian-linter)** — Automatically formats Markdown notes and YAML frontmatter according to customizable style rules.
* **[Meta Bind](https://github.com/mProjectsCode/obsidian-meta-bind-plugin)** — Embed interactive inputs (toggles, sliders, dropdowns, buttons) directly into notes bound to frontmatter properties.

### Note Creation, Properties & Templating

* **[Note Refactor](https://github.com/lynchjames/note-refactor-obsidian)** — Extract highlighted text into new notes or split long notes automatically by headings.
* **[Folder Notes](https://github.com/LostPaul/obsidian-folder-notes)** — Associate an index note with a folder so clicking the folder opens its overview note.
* **[Auto Note Mover](https://github.com/farux/obsidian-auto-note-mover)** — Automatically routes notes into target folders based on tags or title regex rules.
* **[Metadata Menu](https://github.com/mdelobelle/metadatamenu)** — Define `fileClass` schemas with preset field types, dropdown values, and bulk frontmatter editing.
* **[Modal Form](https://github.com/danielo515/obsidian-modal-form)** — Build clean popup forms to collect structured metadata before generating a note.
* **[Waypoint](https://github.com/IdreesInc/Waypoint)** — Automatically generates and updates dynamic Maps of Content (MOCs) inside folder notes.
* **[Zoottelkeeper](https://github.com/akosbalasko/zoottelkeeper-obsidian-plugin)** — Maintains automated index files across your folder hierarchy.
* **[Buttons](https://github.com/shabegom/buttons)** — Create clickable inline buttons to trigger templates, open links, or run commands.

### Task & Project Management

* **[Tasks](https://github.com/obsidian-tasks-group/obsidian-tasks)** `⭐` — Vault-wide task management supporting due/scheduled dates, recurring tasks, priorities, dependencies, and query blocks.
* **[Kanban](https://github.com/mgmeyers/obsidian-kanban)** `⭐` — Create Markdown-backed Kanban boards with drag-and-drop cards, due dates, and archive lanes.
* **[Projects](https://github.com/marcusolsson/obsidian-projects)** — Manage plain-text project workflows across table, board, calendar, and gallery layouts.
* **[Day Planner](https://github.com/ivan-lednev/obsidian-day-planner)** — Time-block your day with an interactive visual timeline synced to your daily notes.
* **[Checklist](https://github.com/delashum/obsidian-checklist-plugin)** — Aggregates unchecked tasks from across your vault into a persistent sidebar panel.
* **[CardBoard](https://github.com/roovo/obsidian-card-board)** — Kanban-style task board powered by tags and due dates across multiple notes.
* **[Reminder](https://github.com/uphy/obsidian-reminder)** — Adds date/time reminders to Markdown tasks with native desktop notifications.
* **[Toggl Track](https://github.com/mcndt/obsidian-toggl-track)** — Start, stop, and report Toggl time entries directly from Obsidian.
* **[Supercharged Links](https://github.com/mdelobelle/obsidian-supercharged-links)** — Style internal links dynamically with icons and colors based on the target note's YAML properties or tags.
* **[TaskNotes](https://github.com/callumalpass/tasknotes)** — Note-based task management where every task is its own Markdown note, with Bases-powered list, Kanban, and calendar views plus Pomodoro and time tracking.

### Calendar & Daily Notes

* **[Calendar](https://github.com/liamcain/obsidian-calendar-plugin)** `⭐` — Minimalist sidebar calendar widget for jumping between Daily and Weekly notes.
* **[Periodic Notes](https://github.com/liamcain/obsidian-periodic-notes)** `⭐` — Extends core Daily Notes with Weekly, Monthly, Quarterly, and Yearly review notes.
* **[Journals](https://github.com/srg-kostyrko/obsidian-journal)** — Multi-journal manager supporting custom schedules, calendar views, and chronological timelines.
* **[Natural Language Dates](https://github.com/argenos/nldates-obsidian)** — Parse human-readable dates (`@today`, `@next monday`, `@in 2 weeks`) into linked dates.
* **[Heatmap Calendar](https://github.com/Richardsl/heatmap-calendar-obsidian)** — Render GitHub-style contribution heatmaps for habits, workouts, or daily word counts.
* **[Tracker](https://github.com/pyrochlore/obsidian-tracker)** — Collect numeric metrics or habit occurrences from notes and plot line charts, bar graphs, and heatmaps.
* **[Chronology](https://github.com/Canna71/obsidian-chronology)** — Browse your vault's created and modified notes along an interactive timeline.

### Knowledge Management & PKM

* **[Spaced Repetition](https://github.com/st3v3nmw/obsidian-spaced-repetition)** `⭐` — Review flashcards and entire notes inside Obsidian using SM-2 spaced repetition scheduling.
* **[Various Complements](https://github.com/tadashi-aikawa/obsidian-various-complements-plugin)** — IDE-style autocomplete for vault words, note titles, aliases, and frontmatter keys.
* **[Strange New Worlds](https://github.com/TfTHacker/obsidian42-strange-new-worlds)** — Displays inline reference counters beside links and blocks showing where else they appear.
* **[Breadcrumbs](https://github.com/SkepticMystic/breadcrumbs)** — Build structured parent/sibling/child hierarchies in flat or non-hierarchical vaults.
* **[Tag Wrangler](https://github.com/pjeby/tag-wrangler)** — Rename, merge, delete, and search tags across your entire vault in bulk.
* **[Obsidian_to_Anki](https://github.com/Pseudonium/Obsidian_to_Anki)** — Sync Markdown-formatted flashcards and cloze deletions directly to Anki decks.
* **[Juggl](https://github.com/HEmile/juggl)** — Interactive, expandable local graph workspace designed for visual sensemaking.
* **[Graph Analysis](https://github.com/SkepticMystic/graph-analysis)** — Discover hidden note connections using similarity algorithms (Co-Citations, Jaccard, Adamic-Adar).
* **[Smart Random Note](https://github.com/erichalldev/obsidian-smart-random-note)** — Surface random notes filtered by search queries or tags to rediscover forgotten ideas.

### Visual Thinking, Canvas & Diagrams

* **[Excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin)** `⭐` — Full hand-drawn whiteboarding and sketching inside Obsidian with bidirectional note embedding and OCR.
* **[Advanced Canvas](https://github.com/Developer-Mike/obsidian-advanced-canvas)** — Supercharges core Canvas with presentation mode, nested portals, custom shapes, and edge styling.
* **[Canvas MindMap](https://github.com/TfTHacker/obsidian-canvas-mindmap)** — Adds keyboard-driven mind-mapping shortcuts (`Tab` for child, `Enter` for sibling) to Obsidian Canvas.
* **[Enhancing Mindmap](https://github.com/MarkMindCkm/obsidian-enhancing-mindmap)** — Edit and view Markdown outlines interactively as visual mind maps.
* **[Diagrams.net](https://github.com/jens-koster/obsidian-diagrams-net)** — Create and edit Draw.io flowcharts and architecture diagrams natively in your vault.
* **[Mermaid Tools](https://github.com/dartungar/obsidian-mermaid)** — Adds a visual helper toolbar for inserting and editing Mermaid.js syntax.
* **[PlantUML](https://github.com/joethei/obsidian-plantuml)** — Render UML sequence, class, and component diagrams directly from code blocks.
* **[Easy TikZ](https://community.obsidian.md/plugins/easy-tikz)** — Render LaTeX TikZ diagrams, mathematical plots, and vector graphics directly in your notes.

### Editor & Writing Enhancements

* **[Outliner](https://github.com/vslinko/obsidian-outliner)** `⭐` — Work with bulleted lists like Workflowy/Logseq (hoisting/zooming, folding, keyboard item reordering).
* **[Editing Toolbar](https://github.com/PKM-er/obsidian-editing-toolbar)** — Customizable Notion/Word-style formatting toolbar at the top of the editor.
* **[Zoom](https://github.com/vslinko/obsidian-zoom)** — Focus on a single heading or bullet branch by temporarily hiding the rest of the document.
* **[Typewriter Scroll](https://github.com/deathau/cm-typewriter-scroll-obsidian)** — Keeps your active typing line vertically centered on the screen.
* **[Longform](https://github.com/kevboh/longform)** — Manage multi-chapter books, screenplays, and theses with scene reordering and manuscript compilation.
* **[cMenu](https://github.com/chetachiezikeuzor/cMenu-Plugin)** — Compact floating formatting palette for quick text styling.
* **[Slash Commander](https://github.com/phibr0/obsidian-slash-commander)** — Trigger any Obsidian command via a customizable `/` slash menu.
* **[Auto Link Title](https://github.com/zolrath/obsidian-auto-link-title)** — Automatically fetches the webpage title when pasting raw URLs.
* **[Paste URL into selection](https://github.com/denolehov/obsidian-url-into-selection)** — Pasting a URL over highlighted text wraps it automatically as `[selection](url)`.
* **[Novel Word Count](https://github.com/isaaclyman/novel-word-count-obsidian)** — Displays word, character, and page counts next to files and folders in the File Explorer.
* **[Better Word Count](https://github.com/lukeleppan/better-word-count)** — Accurate live word/character counts for selections while ignoring frontmatter and comments.
* **[LanguageTool Integration](https://github.com/Clemens-E/obsidian-languagetool-plugin)** — Grammar, spellcheck, and style suggestions inside the editor.
* **[Creases](https://github.com/liamcain/obsidian-creases)** — Granular folding commands and fold markers for headings and lists.
* **[StoryLine](https://github.com/PixeroJan/obsidian-storyline)** — Book-planning workspace with corkboard, timeline, plotlines, and character tracking for long-form fiction. *Caveat: character relationships don't sync bidirectionally, so the cast list has to be maintained by hand.*

### UI, Layout & Navigation

* **[Iconize](https://github.com/FlorianWoelki/obsidian-iconize)** `⭐` — Add icons (Lucide, FontAwesome, Remix, custom SVGs) to folders, files, and tabs.
* **[Hover Editor](https://github.com/nothingislost/obsidian-hover-editor)** `⭐` — Converts the page preview popover into a full, editable, pinnable, and resizable floating window.
* **[Banners](https://github.com/noatpad/obsidian-banners)** — Add Notion-style cover banner images and page icons to notes.
* **[Minimal Theme Settings](https://github.com/kepano/obsidian-minimal-settings)** — Companion plugin for the Minimal theme to toggle color schemes, fonts, and card grids.
* **[File Tree Alternative](https://github.com/ozntel/file-tree-alternative)** — Splits the File Explorer into a two-pane folder + file list layout (similar to Ulysses or Bear).
* **[Quiet Outline](https://github.com/guopenghui/obsidian-quiet-outline)** — Searchable, auto-expanding Table of Contents sidebar that tracks your scroll position.
* **[Bartender](https://github.com/phibr0/obsidian-bartender)** — Drag-and-drop reordering for status bar and ribbon icons.
* **[Hider](https://github.com/kepano/obsidian-hider)** — Toggle visibility of UI chrome such as scrollbars, tooltips, ribbon, and status bar.
* **[Workspaces Plus](https://github.com/nothingislost/obsidian-workspaces-plus)** — Quickly switch between saved window and pane layouts from the status bar.
* **[Home Tab](https://github.com/olrenso/obsidian-home-tab)** — Replaces blank new tabs with a browser-style search bar and recent/pinned files.
* **[MAKE.md](https://github.com/Make-md/makemd)** — Reimagines Obsidian with Notion-like spaces, flow blocks, and visual navigation.
*  **[Note Toolbar](https://github.com/chrisgurney/obsidian-note-toolbar)** — Attach customizable toolbars to individual notes, folders, or the whole vault, with buttons that run commands, open links, or insert text. Works on mobile.

### Data, Databases & Spreadsheets

* **[Advanced Tables](https://github.com/tgrosinger/advanced-tables-obsidian)** `⭐` — Excel-like keyboard navigation (`Tab`/`Enter`), auto-padding, sorting, and spreadsheet formulas in Markdown tables.
* **[DB Folder](https://github.com/RafaelGB/obsidian-db-folder)** — Notion-style relational databases built on top of folders, tags, or Dataview queries.
* **[Charts](https://github.com/phibr0/obsidian-charts)** — Render interactive Chart.js visualizations (Line, Bar, Pie, Radar) from Markdown tables or DataviewJS.
* **[Agate](https://github.com/Casyfill/Agate)** — Create interactive, data-driven visualizations in Obsidian using Vega and Vega-Lite, with dynamic data, native Bases views, and extensive flexibility in chart types and visual design.
* **[Table Extended](https://github.com/alx-plugins/table-extended)** — Adds cell merging (`colspan`/`rowspan`) and multi-line cells to Markdown tables.
* **[Edit CSV](https://github.com/jon-heard/obsidian-csv-table)** — Open and edit `.csv` files directly in a spreadsheet grid inside Obsidian.

### AI, LLMs & Automation

* **[Smart Connections](https://github.com/brianpetro/obsidian-smart-connections)** `⭐` — Local and cloud AI embeddings that surface semantically related notes in real time alongside a vault-aware chat assistant.
* **[Copilot](https://github.com/logancyang/obsidian-copilot)** `⭐` — Multi-provider AI assistant (OpenAI, Anthropic, Gemini, Ollama) for note chatting, vault QA, and custom prompts.
* **[Text Generator](https://github.com/nhaouari/obsidian-text-generator-plugin)** — Generate summaries, outlines, and completions directly in the editor using customizable prompt templates.
* **[Whisper](https://github.com/nikdanilov/whisper-obsidian-plugin)** — Record voice notes and transcribe them straight into Markdown using Whisper speech-to-text.
* **[Local REST API](https://github.com/coddingtonbear/obsidian-local-rest-api)** `🖥️` — Exposes a local HTTPS API allowing external scripts, n8n, Raycast, and AI agents to read/write notes safely.
* **[Shell Commands](https://github.com/Taitava/obsidian-shellcommands)** `🖥️` — Run OS terminal commands and custom scripts from Obsidian hotkeys or file events.

### Read-It-Later, Citations & Sync

* **[Zotero Integration](https://github.com/mgmeyers/obsidian-zotero-integration)** `⭐` — Import bibliographic metadata, citations, and color-coded PDF annotations directly from Zotero.
* **[Readwise Official](https://github.com/readwiseio/obsidian-readwise)** `⭐` — Automatically syncs highlights from Kindle, Readwise Reader, Instapaper, Pocket, and Apple Books.
* **[Remotely Save](https://github.com/remotely-save/remotely-save)** — Open-source multi-cloud sync supporting S3, WebDAV, Dropbox, OneDrive, and Google Drive.
* **[Self-hosted LiveSync](https://github.com/vrtmrz/obsidian-livesync)** — Real-time, end-to-end encrypted synchronization powered by self-hosted CouchDB.
* **[Obsidian Git](https://github.com/Vinzent03/obsidian-git)** `⭐` — Automated Git commits, pulls, and pushes to back up and version-control your vault on GitHub/GitLab.
* **[Slurp](https://github.com/inhumantsar/slurp)** — Paste any URL to download the article as clean, formatted Markdown directly into your note.

### Academic, Math & Science

* **[Latex Suite](https://github.com/artisticat1/obsidian-latex-suite)** `⭐` — Accelerates LaTeX math input with snippet expansion, matrix shortcuts, and auto-closing delimiters.
* **[Pandoc Plugin](https://github.com/OliverBalfour/obsidian-pandoc)** `🖥️` — Export notes to `.docx`, `.pdf`, `.epub`, `.html`, and LaTeX slides via Pandoc.
* **[Enhancing Export](https://github.com/mokeyish/obsidian-enhancing-export)** `🖥️` — GUI wrapper around Pandoc supporting dozens of academic and publishing export formats.
* **[Citations](https://github.com/hans/obsidian-citation-plugin)** — Search BibTeX / CSL-JSON libraries and generate standardized literature notes.
* **[TikZJax](https://github.com/artisticat1/obsidian-tikzjax)** — Compile and render LaTeX TikZ graphics and commutative diagrams natively.
* **[Admonition](https://github.com/javalent/admonitions)** — Create custom callout blocks (Theorem, Proof, Lemma, Example) with tailored icons and colors. *Core callouts (`> [!note]`) now cover most styling needs — reach for this only when you need custom callout types.*

### Media, PDF & Attachments

* **[PDF++](https://github.com/RyotaUshio/obsidian-pdf-plus)** `⭐` — Next-gen PDF workflow: copy text with automatic deep backlinks, multi-color highlights, and embed PDF regions without altering the source file.
* **[Paste Image Rename](https://github.com/reorx/obsidian-paste-image-rename)** `⭐` — Automatically renames clipboard screenshots using the current note's title or custom date patterns.
* **[Image Toolkit](https://github.com/sissilab/obsidian-image-toolkit)** — Click any embedded image to zoom, rotate, invert colors for dark mode, or inspect full-screen.
* **[Annotator](https://github.com/elias-sundqvist/obsidian-annotator)** — Side-by-side annotation viewer for PDF and EPUB files stored in your vault.
* **[Local Images Plus](https://github.com/Sergei-Korneev/obsidian-local-images-plus)** — Downloads external web images referenced in notes into local folders to prevent link rot.
* **[Clear Unused Images](https://github.com/ozntel/oz-clear-unused-images-obsidian)** — Scans your vault for orphaned images and attachments no longer linked anywhere.
* **[Media Extended](https://github.com/PKM-er/media-extended)** — Embed YouTube, Vimeo, and local videos with clickable timestamp links and playback speed controls.

### Developer & Code Tools

* **[Execute Code](https://github.com/twibiral/obsidian-execute-code)** `🖥️` — Execute Python, JS, Bash, C++, Rust, R, and Go code blocks directly inside notes and display inline output.
* **[Shiki Highlighter](https://github.com/mProjectsCode/obsidian-shiki-plugin)** — Replaces default Prism syntax highlighting with VS Code's Shiki engine and themes.
* **[Code Block Enhancer](https://github.com/nyable/obsidian-code-block-enhancer)** — Adds one-click copy buttons, line numbers, language badges, and code folding.
* **[Codeblock Customizer](https://github.com/mugiwara85/CodeblockCustomizer)** — Styles code blocks with themes, custom syntax colors, line highlighting, headers with file names and language icons, folding, and line numbers. Also adds tabbed code block groups, terminal prompts, comment annotations, inline code highlighting, and a "copy as image" button.
* **[CustomJS](https://github.com/saml-dev/obsidian-custom-js)** — Reuse modular JavaScript classes across DataviewJS and Templater scripts.
* **[Custom Frames](https://github.com/Ellpeck/ObsidianCustomFrames)** `🖥️` — Embed external web apps (Google Calendar, Todoist, Notion, local dev dashboards) as native panes.

### Backup, Security & Maintenance

* **[Plugin Update Tracker](https://github.com/swar8080/obsidian-plugin-update-tracker)** — Notifies you of community plugin updates and displays release notes before upgrading.
* **[Lazy Plugin Loader](https://github.com/alangrainger/obsidian-lazy-plugins)** — Delays loading heavy plugins on startup to keep app launch times under a second.
* **[BRAT](https://github.com/TfTHacker/obsidian42-brat)** — Install and auto-update pre-release beta plugins and themes directly from GitHub repositories.
* **[Meld Encrypt](https://github.com/meld-cp/obsidian-encrypt)** — Password-protect individual notes or inline text blocks using AES encryption.
* **[Find Unlinked Files](https://github.com/Vinzent03/find-unlinked-files)** — Identifies orphaned notes and broken internal links across your vault.
* **[Trash Explorer](https://github.com/proog/obsidian-trash-explorer)** — Browse, preview, and restore deleted files from Obsidian's `.trash` folder.

---

## Themes

Install via **Settings → Appearance → Themes → Manage**. Many pair with **Style Settings** for deep customization.

* **[Minimal](https://github.com/kepano/obsidian-minimal)** `⭐` — Created by Obsidian CEO kepano; distraction-free typography, multi-column cards, and rich color palettes.
* **[AnuPpuccin](https://github.com/AnubisNekhet/AnuPpuccin)** `⭐` — Highly customizable theme built around Catppuccin palettes with custom callouts, checkboxes, and card layouts.
* **[Things](https://github.com/colineckert/obsidian-things)** — Clean, crisp interface inspired by the Cultured Code Things 3 task manager.
* **[Border](https://github.com/Akifyss/obsidian-border)** — Modern, card-based aesthetic with distinctive pane borders and extensive Style Settings toggles.
* **[Blue Topaz](https://github.com/whyt-byte/Blue-Topaz_Obsidian-css)** — Feature-rich theme with dozens of built-in background, heading, and callout styles.
* **[Catppuccin](https://github.com/catppuccin/obsidian)** — Official port of the soothing pastel Catppuccin palettes (*Latte*, *Frappé*, *Macchiato*, *Mocha*).
* **[ITS Theme](https://github.com/SlRvb/Obsidian--ITS-Theme)** — Packed with specialized styling for TTRPGs, Wikipedia-style infoboxes, image grids, and alternate checkboxes.
* **[Primary](https://github.com/ceciliamay/primary)** — Warm, tactile theme inspired by Bauhaus and vintage stationery with semantic accent colors.
* **[Sanctum](https://github.com/jdanielmourao/obsidian-sanctum)** — Calm, monochrome reading and long-form writing environment built around IBM Plex.
* **[Shimmering Focus](https://github.com/chrisgrieser/shimmering-focus)** — Minimalist, keyboard-centric theme that fades inactive UI chrome while you write.
* **[Obsidian Nord](https://github.com/insanum/obsidian_nord)** / **[Obsidian Gruvbox](https://github.com/insanum/obsidian_gruvbox)** — Faithful ports of the classic Arctic Nord and warm retro Gruvbox palettes.
* **[Tokyo Night](https://github.com/tcmmichaelb139/obsidian-tokyo-night)** / **[Dracula Official](https://github.com/dracula/obsidian)** — Developer-favorite dark themes with crisp syntax contrast.

---

## CSS Snippets & Collections

Drop `.css` files into `.obsidian/snippets/` and enable them in **Settings → Appearance → CSS snippets**.

* **[Modular CSS Layout (MCL)](https://github.com/efemkay/obsidian-modular-css-layout)** `⭐` — Add multi-column callouts, floating galleries, and wide-page layouts to *any* theme using simple tags or callout metadata.
* **[Obsidian-CSS-Snippets (rushi-cheulwar)](https://github.com/rushi-cheulwar/Obsidian-CSS-Snippets)** — Huge community-curated vault of snippets for custom checkboxes, rainbow headings, brutalist tags, and Bases row numbering.
* **[ITS Theme Snippets](https://github.com/SlRvb/Obsidian--ITS-Theme/tree/main/Snippets)** — Standalone snippets for Wikipedia infoboxes, Kanban styling, and image adjustments usable outside ITS Theme.
* **[Minimal Theme CSS Snippets (replete)](https://github.com/replete/obsidian-minimal-theme-css-snippets)** — Enhancements for Minimal cards, dashboards, and properties.
* **[PDF Export Styling Snippet](https://github.com/teotimepacreau/obsidian-snippet-export-to-pdf)** — Clean print typography and page-break rules when exporting notes to PDF.

---

## Publishing & Digital Gardens

Turn your local Markdown vault into a public website, blog, or interactive digital garden.

* **[Quartz](https://github.com/jackyzha0/quartz)** `⭐` — Fast, static-site generator built specifically for Obsidian vaults featuring backlinks, graph view, full-text search, popovers, and LaTeX.
* **[Digital Garden (oleeskild)](https://github.com/oleeskild/obsidian-digital-garden)** `⭐` — Publish notes straight from Obsidian to Vercel or Netlify using a dedicated companion plugin with zero command-line setup.
* **[Flowershow](https://github.com/datopian/flowershow)** — Turn Obsidian vaults into clean websites with support for callouts, Mermaid diagrams, and wikilinks.
* **[Enveloppe](https://github.com/Enveloppe/obsidian-enveloppe)** — Community plugin that pushes selected notes and attachments directly to a GitHub repository for Hugo, Jekyll, Eleventy, or Astro sites.
* **[Perlite](https://github.com/secure-77/Perlite)** — Lightweight, self-hosted PHP/Docker web viewer optimized for browsing an Obsidian vault privately or publicly.
* **[Astro Starlight + Obsidian](https://starlight.astro.build/)** — Popular documentation framework frequently paired with Obsidian vaults via `astro-loader-obsidian`.

---

## External Companion Apps, Launchers & Mobile

Tools outside Obsidian that integrate with your vault via URIs, local files, or the Obsidian CLI.

* **[Raycast Obsidian Extension](https://www.raycast.com/marcjulian/obsidian)** `🖥️` `⭐` — Search notes, append to daily notes, capture quick thoughts, and open bookmarks on macOS from Raycast.
* **[Alfred Obsidian Utilities](https://github.com/chrisgrieser/shimmering-obsidian)** `🖥️` — Comprehensive Alfred workflow for vault search, screenshot capture, and workspace switching.
* **[Actions for Obsidian](https://actions.work/actions-for-obsidian)** — Deep Apple Shortcuts integration for iOS, iPadOS, and macOS (append/prepend, search, get properties).
* **[Drafts](https://getdrafts.com/)** — Lightning-fast text capture app on iOS/macOS with native actions to send notes straight into Obsidian vaults.
* **[Quick Capture / Fleeting Notes](https://github.com/fleetingnotes/fleeting-notes-flutter)** — Lightweight mobile scratchpad syncing quick ideas directly into Obsidian.
* **[SQLite Graph Memory](https://github.com/tonydzi/sqlite-graph-memory)** `🖥️` — Local MCP server and CLI that indexes a Markdown vault into SQLite and follows wikilinks to find related notes for Claude Code, Cursor, or Codex.
* **[Syncthing](https://syncthing.net/)** — Free, open-source peer-to-peer file synchronization across Windows, macOS, Linux, and Android.
* **[Working Copy](https://workingcopyapp.com/)** (iOS) / **[Termux](https://termux.dev/)** (Android) — Run Git-based vault synchronization on mobile devices.

---

## Importers & Converters

Migrate existing archives into clean Obsidian-compatible Markdown.

* **[Yarle (Yet Another Rope Ladder from Evernote)](https://github.com/akosbalasko/yarle)** `⭐` — The gold-standard converter for `.enex` exports, preserving tags, creation dates, attachments, and internal links.
* **[Notion-to-Obsidian](https://github.com/connertennery/Notion-to-Obsidian-Converter)** — Strips Notion UUID hashes from filenames and links while fixing CSV databases.
* **[keep-it-markdown (KIM)](https://github.com/djsudduth/keep-it-markdown)** — Converts Google Keep exports and notes into frontmatter-tagged Markdown.
* **[DayOne JSON to MD](https://github.com/QuantumMobile/DayOne-JSON-to-MD)** — Migrates Day One journal entries, locations, weather metadata, and photos.
* **[Goodsidian](https://github.com/selfire1/goodsidian)** — Syncs your Goodreads shelves, ratings, and reviews into structured book notes.
* **[Readwise / Zotero / Hypothesis Scripts](https://github.com/out-of-cheese-error/gooseberry)** — CLI tools (`gooseberry`, etc.) to pull web annotations into Markdown.

---

## Starter Vaults & Template Kits

Explore ready-made architectures to learn PKM workflows by example.

* **[Obsidian Community Vaults Gallery](https://vaults.obsidian-community.com/)** — Browsable gallery of published community vaults with screenshots and source links — the fastest way to see how other people structure a real vault before committing to your own.
* **[Kepano's Obsidian Vault](https://stephango.com/vault)** `⭐` — Minimalist, folder-light reference vault by Obsidian CEO Steph Ango demonstrating properties, Bases, and evergreen notes.
* **[Linking Your Thinking (LYT) Kit](https://www.linkingyourthinking.com/lyt-kit)** — Nick Milo's hands-on starter vault teaching Maps of Content (MOCs) and fluid note organization.
* **[PARA Starter Kit](https://github.com/cotemaxime/obsidian-para-starter-kit)** — Pre-built vault structured around Tiago Forte's *Projects, Areas, Resources, Archives* framework.
* **[Obsidian Template Hub](https://github.com/groepl/Obsidian-Templates)** — Community repository of templates for daily logs, book notes, meeting minutes, and Zettelkasten cards.
* **[SlRvb's MediaDB & Journaling Setups](https://github.com/SlRvb/Obsidian--ITS-Theme)** — Worked examples for tracking movies, games, books, and daily journals.

---

## Plugin & Theme Development

Resources for building your own Obsidian plugins, themes, and scripts.

* **[Official Obsidian Developer Docs](https://docs.obsidian.md/)** `🌐` `⭐` — Official TypeScript API reference, CSS variables guide, and plugin submission guidelines.
* **[Obsidian Sample Plugin](https://github.com/obsidianmd/obsidian-sample-plugin)** `🌐` — Official TypeScript + esbuild starter template for creating a new community plugin.
* **[Obsidian Sample Theme](https://github.com/obsidianmd/obsidian-sample-theme)** `🌐` — Boilerplate repository for developing and publishing a community theme.
* **[Hot Reload (pjeby)](https://github.com/pjeby/hot-reload)** `⭐` — Automatically reloads your plugin inside Obsidian whenever `main.js` or `styles.css` changes during development.
* **[Obsidian CLI Dev Commands](https://obsidian.md/help/cli)** `🌐` — Use `obsidian dev:console`, `obsidian dev:dom`, and `obsidian plugin:reload` directly from your terminal or AI coding agent.
* **[Obsidian Typings](https://github.com/Fevol/obsidian-typings)** — Community-maintained TypeScript definitions for undocumented internal Obsidian APIs.

---

## Community & Learning Resources

* **[Obsidian Help & Official Docs](https://help.obsidian.md/)** `🌐` — Comprehensive official manual covering Markdown syntax, Properties, Bases, Canvas, and Sync.
* **[Obsidian Forum](https://forum.obsidian.md/)** `🌐` — Official discussion board for bug reports, feature requests, custom CSS help, and showcase workflows.
* **[Official Obsidian Discord](https://obsidian.md/community)** `🌐` — Active real-time community with dedicated channels for `#plugin-dev`, `#appearance`, `#academia`, and `#dataview`.
* **[r/ObsidianMD](https://www.reddit.com/r/ObsidianMD/)** — Active Reddit community sharing vault setups, plugin discoveries, and troubleshooting tips.
* **[Obsidian Stats](https://www.obsidianstats.com/)** — Searchable analytics directory tracking new plugins, download trends, themes, and release updates.
* [**YouTube notes to Obsidian**](https://videonotes.dev/youtube-notes-to-obsidian) — Illustrated guide to capturing timestamped YouTube notes with Video Notes, copying Markdown, and pasting it into an Obsidian vault.
