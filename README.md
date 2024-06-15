# Node.js Note Taker App

## Deployed App In Render

<https://node-note-taker.onrender.com>

## GitHub Repo

<https://github.com/ndzamboni/node-note-taker.git>

<!-- insert screenshot -->
![Screenshot](/test.PNG)

This Node.js application allows users to create, save, view, and delete notes. It utilizes Express.js for handling server requests, fs (File System) module for interacting with the file system, and uuid package for generating unique IDs for notes.

This Node.js application allows users to create, save, view, and delete notes. It utilizes Express.js for handling server requests, fs (File System) module for interacting with the file system, and uuid package for generating unique IDs for notes.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Dependencies](#dependencies)
- [License](#license)

## Installation

To install and run the application locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd node-note-taker

2. **Install Dependencies:**

    ```bash
    npm install

3. **Start the server:**

    ```bash
    npm start

This will start the server at <http://localhost:3000/notes>.

## Usage

- Creating a Note:

Navigate to <http://localhost:3000/notes>.

Enter a title and content for the note.

Click the "Save" button to save the note.

- Viewing Notes:

All saved notes will be displayed on the left panel.

Click on a note to view its details.

Deleting a Note:

Click the trash icon next to a note to delete it.

## Endpoints

The application has the following API endpoints:

GET /api/notes:

Retrieves all notes stored in db.json.
POST /api/notes:

Creates a new note with a unique ID and saves it to db.json.
DELETE /api/notes/:id:

Deletes the note with the specified id from db.json.

## Dependencies

Express.js: Minimalist web framework for Node.js.

uuid: Package for generating unique IDs

## License

This project is licensed under the MIT License - see the LICENSE file for details.
