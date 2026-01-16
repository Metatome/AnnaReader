# AnnaReader User Manual

## 1. Installation & Setup

### Windows
1. Download `AnnaReader-Windows-x64.zip` from the Releases page.
2. Extract the file to any directory.
3. Double-click `AnnaReader.Desktop.exe` to run.

### macOS
1. Download `AnnaReader-macOS-x64.dmg`.
2. Open the DMG file and drag AnnaReader to your Applications folder.
3. Launch from Launchpad.

### Linux
1. Download `AnnaReader-Linux-x64.tar.gz`.
2. Extract and run `./AnnaReader.Desktop`.
3. Ensure necessary dependencies (like GTK3) are installed.

---

## 2. Library Management

### Importing Books
- **Import File**: Click the "Import File" button on the main interface to select one or more e-book files.
- **Import Folder**: Click "Import Folder" to select a directory. The system will scan and import all supported books.
- **Drag & Drop**: Simply drag files directly into the application window.

### Bookshelves
- **New Shelf**: Click the "+" icon in the sidebar and enter a name.
- **Move Books**: Right-click a book cover, select "Move to...", and choose the target shelf.
- **Delete Books**: Right-click a book and select "Delete". You can choose to remove it from the shelf or delete the local file entirely.

### Search
- Type a book title or author name in the top search bar to filter your local library instantly.

---

## 3. Reading

### Reader Interface
- **Turn Pages**: Click the left/right sides of the page or use the arrow keys.
- **Table of Contents**: Click the TOC icon in the top-left corner to jump to specific chapters.
- **Fullscreen**: Press `F11` to toggle fullscreen mode.

### Customization
Click the "Settings" icon (gear) in the top-right corner of the reader to adjust:
- **Font Size**: Slider to increase/decrease text size.
- **Background**: Choose between Eye-care (parchment), Night mode, or White.
- **Font Style**: Toggle between Serif and Sans-serif.

---

## 4. Anna's Archive Integration

### Searching
1. Click "Online Library" or "Anna's Archive" in the sidebar.
2. Enter keywords (Title, Author, ISBN) in the search box.
3. View results directly from Anna's Archive.

### Downloading
1. Click on a book cover in the search results to view details.
2. Click the "Download" button.
3. The book will be downloaded via the "Slow Download" channel and added to your default shelf.
4. **Note**: Download speed depends on your internet connection and Anna's Archive server load.

### Network Settings
If you cannot access Anna's Archive directly, configure a proxy in "Settings" -> "Network":
- Check "Use Proxy".
- Enter your proxy address and port (e.g., `127.0.0.1:7890`).

---

## 5. Cloud Sync (WebDAV)

AnnaReader supports syncing your reading progress and shelves via WebDAV.

1. Go to "Settings" -> "Sync".
2. Check "Enable Sync".
3. Enter your WebDAV server details:
   - **URL**: WebDAV Address (e.g., `https://dav.yourservice.com/`)
   - **Username**: Your WebDAV username
   - **Password**: Your WebDAV password
4. Click "Test Connection". Once successful, your data will sync automatically.

---

## 6. FAQ

**Q: Why can't I find certain books?**
A: While Anna's Archive is massive, it doesn't contain every book ever written. Also, check your network connection.

**Q: What formats are supported?**
A: Currently supports PDF, EPUB, MOBI, AZW3, TXT, MD. MOBI and AZW3 are automatically converted to EPUB for the best reading experience.

**Q: Is this software free?**
A: Yes, AnnaReader is forever free and open source.
