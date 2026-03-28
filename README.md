# Simple CSV Editor

A lightweight, browser-based CSV editor designed for local workflows. This tool allows you to manage datasets directly from your file system without ever uploading data to a server.

## Features

- **Privacy First:** Runs entirely in your browser. Data never leaves your machine.
- **Zero Installation:** No Node.js, Python, or databases required. Just open the HTML file.
- **Folder Sync:** Uses the modern File System Access API to edit and save files directly to your `./data/assets` folder.
- **Material UI:** A clean, sidebar-driven interface using Google Material Icons.
- **Vanilla Tech:** Built with pure HTML, CSS, and JavaScript for maximum speed and compatibility.

## Getting Started

1. **Clone or Download** this repository to your local machine.
2. Ensure your data is organized (e.g., in a `/data/assets` folder).
3. Open `index.html` in a modern web browser (Chrome or Edge recommended).
4. Click **Open Directory** and select your assets folder.
5. Click any CSV in the sidebar to start editing!

## Usage

- **Editing:** Click any cell to change its value.
- **Adding Data:** Use the **+ Add Row** button to append new entries.
- **Saving:** Click **Save Changes** to overwrite the local file. The browser will ask for permission the first time you save.

## Requirements

To use the **Direct Save** feature, you need a browser that supports the [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_Access_API):
- Google Chrome (Desktop)
- Microsoft Edge (Desktop)
- Opera (Desktop)

*Note: Firefox and Safari users can still open files but will be prompted to "Download" the edited version rather than saving in-place.*

## License

Licensed under the **Apache License, Version 2.0**. 

See the [LICENSE](LICENSE) file for more details.

---
*Created with focus on simplicity and local-first data management.*
