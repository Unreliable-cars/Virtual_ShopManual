
### Linux / macOS
```bash
chmod +x run.sh
./run.sh
```

### Windows
```
run.bat
```

Or run manually:
```bash
cd src
python -m fileorganizer.main
```

## ✅ Features
- Folder tree (nested) on left, file list with columns on right.
- Context menus for files/folders with Delete confirmation dialogs.
- Case-insensitive, symbol-aware search with filters: tag:, folder:, type:.
- Preview support: TXT (scrollable), Images, PDFs, Office docs, external open for multimedia.
- LibreOffice integration for preview/edit/new files.
- Export selected files to ZIP with metadata.
- Add/import button + drag and drop (if tkdnd installed).
- Keyboard shortcuts (Delete, Enter, Ctrl+F).

## ⚠️ Notes
- Database is overwritten/migrated on startup for schema compatibility.
- Requires SQLite FTS5 support (built into Python’s sqlite3).
- LibreOffice optional but needed for Office previews/edits.
