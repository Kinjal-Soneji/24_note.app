# Notes App

A simple and intuitive web application for creating, editing, and managing notes with local storage functionality.

## Features

- Create new notes with custom text
- Edit existing notes
- Delete unwanted notes
- Persistent storage using browser's localStorage
- Responsive design for various screen sizes
- Real-time error handling and validation
- Clean and modern user interface

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Local Storage API

## Usage

1. **Adding a Note**
   - Type your note in the input field
   - Click the "Add Note" button or press Enter
   - The note will be added to the list and saved automatically

2. **Editing a Note**
   - Click the "Edit" button next to the note you want to modify
   - The note text will appear in the input field
   - Make your changes
   - Click "Edit Note" to save the changes

3. **Deleting a Note**
   - Click the "Delete" button next to the note you want to remove
   - The note will be permanently deleted from the list and storage

## Project Structure

```
notes-app/
│
├── index.html          # Main HTML file
├── style.css          # Stylesheet file
├── main.js            # JavaScript logic
└── README.md          # Project documentation
```

## Styling

The application features a modern design with:
- Purple background theme
- Yellow accent colors
- Responsive layout
- Smooth animations and transitions
- User-friendly button styles
- Clear visual hierarchy

## Local Storage

The app uses the browser's localStorage to persist notes between sessions. Notes are automatically saved when:
- Creating a new note
- Editing an existing note
- Deleting a note
