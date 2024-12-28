# Notes Application

This is a **Notes Application** built with React, allowing users to create, edit, delete, and preview markdown-formatted notes.

## Features
- **Add, Edit, Delete Notes**: Create new notes, modify their content or titles, and remove notes that are no longer needed.
- **Markdown Preview**: Instantly view the formatted version of your markdown content as you type.
- **Persistent Storage**: Automatically saves notes to the browser's `localStorage`, ensuring they remain available between sessions.
- **Dynamic Sorting**: Organizes notes by their last modified timestamp, keeping the most recent updates easily accessible.

## Technologies Used
- **React**: The JavaScript library used for building the user interface, providing component-based architecture.
- **React Markdown**: Converts markdown syntax into HTML for live previews.
- **CSS**: Used for custom styling, including layout, hover effects, and responsiveness.
- **Normalize.css**: Ensures consistent styling across different browsers.
- **LocalStorage API**: Stores notes data locally to maintain persistence across sessions.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Notes-Application.git
   ```
2. Install dependencies and start the app:
   ```bash
   npm install
   npm start
   ```

## Usage
1. **Add Notes**: Use the `Add` button to create new notes, which will appear at the top of the sidebar.
2. **Edit Notes**: Click on a note to edit its title and body in the editor section.
3. **Preview Markdown**: View the formatted markdown content in the live preview panel below the editor.
4. **Delete Notes**: Remove notes by clicking the `Delete` button next to them in the sidebar.

## Future Enhancements
- **Search Functionality**: Add a search bar to find notes by title or content.
- **Tagging and Categorization**: Introduce tags or folders for better organization.
- **Cloud Sync**: Enable synchronization across devices using cloud storage integration.

