# Folder Tree Visualizer

A lightweight, browser-based utility to instantly visualize and export a recursive directory tree of any selected local folder.

## Features
*   **Recursive Scanning**: Deeply traverses selected directories to list all nested files and subfolders.
*   **Instant Visualization**: Generates a clean, text-based tree structure (e.g., using ASCII characters like `├──`).
*   **Privacy First**: Runs entirely in the browser. No data is uploaded to any server.
*   **Zero Setup**: A single-file HTML tool (`FolderTree.html`) that requires no installation or dependencies.

## Built With
*   **HTML5 / CSS3**: Responsive UI for clear directory viewing.
*   **Vanilla JavaScript**: Uses modern asynchronous iteration to handle large directory structures efficiently.

## How to Use
1.  **Open** `FolderTree.html` in a modern web browser (Chrome, Edge, or any browser supporting the File System Access API).
2.  **Click** the "Choose Folder" button to trigger the directory picker.
3.  **Grant Permission** for the browser to read the folder contents.
4.  **View** your entire folder structure rendered instantly on the screen.

## Requirements
*   A modern browser that supports `window.showDirectoryPicker()` (e.g., Chrome 86+, Edge 86+).

## License
This project is licensed under the [MIT License](LICENSE).
