# Memory Buffer

**Write first. Organize later. Or never.**

## What is this?

Memory Buffer is a notes app for people who think in bursts.

It removes the friction between "having a thought" and "writing it down."

- Open the app → blank note. Cursor blinking. No folders. No decisions.
- Type. That's it.
- Want to keep it? Save to a folder. Or to Misc. Or leave it ephemeral and let it disappear.

**Most apps ask: "What is this worth?"**
**Memory Buffer asks: "What are you thinking?"**

## The Problem This Solves

Existing notes apps force you to make decisions before you write:

- "Where should this go?"
- "What should I call it?"
- "Is this worth keeping?"

Each decision is **noise**. It interrupts the thought before it's fully formed.

Memory Buffer removes the noise. You write first. The app gets out of the way.

## Key Features

### Instant Blank Note
Open the app → cursor blinking in a blank note. No dashboard. No "New Note" button. Just space to think.

### Folders (Optional)
Create topics as folders. Nest them. Click to select where new notes save. Or ignore folders entirely.

### Misc Folder
Don't want to organize? Save to Misc. Auto-named with date. No guilt. No "Unfiled" punishment.

### Append Bar (Chat-Style)
Quickly add to any note without opening it. Type in the bottom bar → Enter → timestamped line appears at the bottom of the note.

Like messaging yourself. Perfect for capture during the day.

### Ephemeral Mode
Toggle ephemeral mode for thoughts that don't need to last. Close the app → they're gone. No prompts. No "are you sure?"

### Direct Editing
Click any note → full editor. Edit freely. Auto-saves (debounced). No "save" button required.

### Keyboard First
Every action has a shortcut. Your hands never leave the keyboard.

## Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+N` | New blank note |
| `Ctrl+E` | Toggle ephemeral mode |
| `Ctrl+M` | Save current note to Misc |
| `Ctrl+S` | Save current note |
| `Ctrl+Shift+F` | New folder |
| `Ctrl+K` | Focus folder search |
| `Ctrl+↓` | Focus append bar |
| `Ctrl+Enter` | Append thought |
| `F2` | Rename selected note/folder |
| `Del` | Delete selected note/folder |

## How It's Different

| | Most Apps | Memory Buffer |
|-|-----------|---------------|
| Default action | Browse | Write |
| Organization | Required | Optional |
| Adding content | Edit mode only | Edit + Append |
| Temporary notes | Unsaved (accident) | Ephemeral (choice) |
| Unfiled notes | Punishment | Feature (Misc) |
| Mental model | Filing cabinet | Conversation |

## Psychological Design

Memory Buffer is designed to reduce cognitive load:

- **No decision fatigue** — Write first, organize later
- **Low cost of impermanence** — Ephemeral mode makes discarding safe
- **Separation of capture and curation** — Create in one mode, edit in another
- **No clutter anxiety** — Misc absorbs unfiled notes without judgment
- **Externalization without commitment** — Append bar gets thoughts out of your head instantly

## Tech Stack

- Single HTML file
- Vanilla JavaScript
- LocalStorage for persistence
- Plain text/markdown notes
- No dependencies
- Works offline


## Getting Started

1. Download the HTML file
2. Open in any modern browser
3. Start typing

All notes are saved locally to your browser's storage. Export to JSON for backup.

## File Structure

Notes are stored as plain text files in a nested folder structure.

DISCLAIMER: made with AI.
