# # BuildCore

A desktop browser workspace with — web ai, tabs, notes, a code editor, and session management in one app.

---

## Tabbed Browser

- Open unlimited tabs, each fully isolated from one another (separate cookies, login sessions, and storage per tab)
- Navigate with a URL bar, back/forward buttons, reload, and hard reload
- Duplicate, close, or switch tabs from a right-click context menu
- Tab titles and favicons update live as pages load
- Tabs persist across restarts — reopen the app and continue where you left off
- Keyboard navigation: `Ctrl+T` new tab, `Ctrl+W` close, `Ctrl+1–9` jump to tab, `Ctrl+Tab` cycle tabs

---

## AI Provider Launcher

New tabs open a launch page with one-click access to the major AI tools:

**AI Assistants** — Claude, ChatGPT, Gemini, Grok, Perplexity, DeepSeek, Mistral, Copilot, Meta AI, Cohere

**Dev Tools** — Notion, GitHub, Linear, Figma, Vercel, Replit

Each provider opens in its own isolated tab so you can be logged into multiple services simultaneously.

---

## Custom Site Categories

- Create named categories (e.g. "Work", "Research") and add any URL to them
- Sites appear as cards on the new tab page alongside the built-in providers
- Add, rename, and delete categories and sites at any time

---

## Command Palette

Press `Ctrl+K` to open a fast command palette. Search open tabs by title or URL, navigate to any history entry, or type a URL to open it — all from the keyboard without touching the mouse.

---

## Browsing History

- Full history of every page visited, searchable by title or URL
- Click any entry to reopen it in a new tab
- Export history as JSON for external use
- Clear all history at once

---

## Notes

A persistent scratchpad always one click away. Write freely — notes auto-save every 5 seconds. `Ctrl+S` saves immediately. Notes survive restarts and are stored locally.

---

## Web Session Manager

- Save the current set of open tabs as a named session
- Restore any saved session to reopen all its tabs at once
- Rename and delete sessions
- Set a countdown timer per session (15 min, 30 min, 1 hr, 2 hr, or custom) — a visible pill shows time remaining and alerts when it expires
- Search saved sessions by name

---

## Code Editor (Project IDE)

A full in-app editor for front-end projects — no external editor needed.

**Projects**
- Create multiple projects, each with its own colour-coded label
- Full file tree with folders, collapsible nodes, and drag-and-drop reordering
- Rename, duplicate, cut/paste, and delete files and folders inline
- Import a project by dropping a `.zip` file — it unpacks automatically
- Export any file or the whole project as a `.zip` download

**Editor**
- Syntax-aware language detection for 30+ file types: HTML, CSS, JS, TS, JSX, TSX, JSON, Markdown, Python, Ruby, PHP, Go, Rust, Swift, Kotlin, Dart, Vue, GraphQL, SQL, YAML, TOML, SCSS, LESS, SASS, C, C++, Java, Shell, XML, SVG
- Line numbers, cursor position (line + column), character count, and file size in the status bar
- Find and replace with match count and next/prev navigation (`Ctrl+H`)
- Toggle line comments with `Ctrl+/`
- Auto-indentation with Tab key, 2-space indent
- Multiple open file tabs with unsaved-change indicators
- Resizable file explorer panel

**Live Preview**
- Split-pane preview for HTML files — see changes as you type (800 ms debounce)
- CSS and Markdown files also refresh the preview automatically
- Resizable preview pane; toggle preview on/off with a single button

---

## Sidebar

The collapsible left sidebar shows all open tabs for quick switching. Toggle with `Ctrl+B` or the sidebar button. Sidebar state is remembered between sessions.

---

## Settings

- **Default Home URL** — set what loads in new tabs when no provider is selected
- **Show/hide status bar** — toggle the bottom status strip
- **Show/hide sidebar** — collapse or expand the left panel
- **Clear tab session** — wipe cookies and storage for the active tab only
- **Export history** — save browsing history as JSON
- **Clear history** — delete all history
- **Open data folder** — reveal the app's storage directory in your file explorer

---

## Keyboard Shortcuts

| Action | Shortcut |
|---|---|
| New tab | `Ctrl+T` |
| Close tab | `Ctrl+W` |
| Command palette | `Ctrl+K` |
| Toggle sidebar | `Ctrl+B` |
| Focus URL bar | `Ctrl+L` |
| Reload | `Ctrl+R` |
| Hard reload | `Ctrl+Shift+R` |
| Switch to tab N | `Ctrl+1–9` |
| Next / prev tab | `Ctrl+Tab` |
| Navigate back | `Alt+←` |
| Navigate forward | `Alt+→` |
| Save file (IDE) | `Ctrl+S` |
| Find & replace (IDE) | `Ctrl+H` |
| Toggle comment (IDE) | `Ctrl+/` |
| Cancel / close overlay | `Escape` |
| Quit | `Ctrl+Q` |

need to upgrade/fix:
notes
IDE
add architecture or workflow charts 
