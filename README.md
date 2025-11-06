# webapp-snippets
Minimal HTML/CSS/JS snippets for quick repro and debugging of web app issues

## Files

### folder-upload-test.html
Tests the native folder upload dialog to inspect what information the browser returns. Displays comprehensive details about selected files including names, paths, sizes, types, last modified dates, and folder structure. **Note:** No actual upload logic is implemented by design - this is purely for inspecting the FileList API response.

**How to run:**

1. **Direct file opening (simplest):**
   - Double-click the HTML file in File Explorer

2. **Python HTTP Server:**
   ```powershell
   python -m http.server 8000
   ```
   Then open: http://localhost:8000/folder-upload-test.html

3. **VS Code Extensions:**
   - **Live Server** (ritwickdey.liveserver): Most popular, right-click file → "Open with Live Server". Simple and reliable.
   - **Live Preview** (ms-vscode.live-server): Microsoft's official extension, embedded browser in VS Code. Better for debugging with DevTools integration.

