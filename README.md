Note-Taker
Project Description
The Note-Taker application is a web-based tool designed for users to create, save, and manage their notes. Built with an Express.js back end, this application allows users to organize their thoughts and track tasks efficiently. The front end is intuitive and user-friendly, providing a seamless experience for note management.

Table of Contents
Features
Technologies Used
Installation
Usage
API Routes
Bonus Features
Deployment
License
Acknowledgements
Features
Create and save notes with titles and text.
View existing notes and edit them.
User-friendly interface with a clear layout.
Note data is stored in a JSON file, ensuring persistence across sessions.
Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: JSON file for data storage
Unique ID Generation: npm package for generating unique IDs
Installation
To set up the project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/mkeeney42/note-taker.git
cd note-taker
Install dependencies:

bash
Copy code
npm install
Start the server:

bash
Copy code
npm start
Open your browser and navigate to http://localhost:3000 to access the application.

Usage
Upon opening the application, you will see a landing page with a link to the notes page.
Clicking the link directs you to the notes page where you can view existing notes and enter new ones.
Fill in the note title and text, then click "Save Note" to store it.
Click on existing notes to view their contents and use the "New Note" button to create a new note.
API Routes
GET /notes: Returns the notes.html file.
GET /: Returns the index.html file.
GET /api/notes: Retrieves all saved notes as JSON.
POST /api/notes: Saves a new note to the db.json file and returns the note as a response.
DELETE /api/notes/
: Deletes a note by its unique ID.
Bonus Features
The application includes functionality to delete notes, allowing users to manage their notes effectively.
Deployment
The Note-Taker application is deployed on Render. You can access the live application at: [Your Deployed URL Here].

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Thanks to the educational resources and community support for helping to shape this project.
Special thanks to the creators of Express.js and other technologies utilized in this application.
Feel free to reach out if you have any questions or feedback about the Note-Taker application!
