# Simple CSV Editor

A lightweight, browser-based utility designed for local data management. This application provides a streamlined interface for editing CSV files directly from the local file system without requiring external server communication or data uploads.

## Core Capabilities

- **Local-First Architecture:** Operations are performed entirely within the client-side environment to ensure data privacy and security.
- **Zero-Dependency Deployment:** the application requires no installation, runtime environments (Node.js/Python), or external libraries.
- **Direct File System Synchronization:** Integration with the File System Access API allows for seamless reading and overwriting of files within a designated directory.
- **Persistent Sidebar Navigation:** Automatic indexing of CSV files within the selected workspace for rapid switching between datasets.
- **Standardized UI:** Interface elements are built using Google Material Icons for an intuitive, industry-standard user experience.

## Deployment and Initialization

1. **Directory Mapping:** Use the **Initialize Assets** overlay to map the local directory containing the target CSV files.
2. **Modification:** Select a file from the sidebar to populate the editor. Data is modified via the interactive table cells.
3. **Commitment:** Changes are written back to the source file via the **Save Changes** command.

## Compatibility and Technical Requirements

Full support for direct file overwriting is available in browsers implementing the [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_Access_API):
- **Google Chrome** (Version 86+)
- **Microsoft Edge** (Version 86+)
- **Opera** (Version 72+)

*Note: Browsers lacking API support (such as Firefox or Safari) will default to a standard download-and-replace workflow.*

## License

This project is licensed under the **Apache License, Version 2.0**. 

Full license details are available in the [LICENSE](LICENSE) file.

---
*Technical Utility for Local-First Asset Management.*
