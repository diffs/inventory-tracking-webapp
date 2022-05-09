# Inventory Tracking Web Application

Frontend + Backend of an inventory/item tracking system.

# Main Page (Frontend)
![image](https://user-images.githubusercontent.com/50718889/167464062-2b2302ae-6634-4a51-829b-b2f2410bd35c.png)


# Features
- Backend:
  - Persistent storage using SQLite
  - JSON-based API with input validation
  - 3 Endpoints and multiple HTTP methods for CRUD support
  - CSV export system with utilizing the json2csv package
- Frontend:
  - Full item listing
  - Edit and Delete options for each Item - with user confirmation
  - Specify reason for deleting an item
  - View deleted items, un-delete items
  - Add New Items
  - Special Feature: Export Data & Download CSV
  - Modern design with Bootstrap
  - Use of Sweetalert2 for user input
  - Fully AJAX based
  - Dark theme inspired by GitHub

# Installation Instructions

### 0) Ensure Node.JS and NPM (node package manager) are installed on the system
### 1) Download/clone this repository & extract if needed
### 2) Go to the "backend" folder, open a command line, and type:
`npm install`

This will install the necessary dependencies.

### 3) Launch the node.js backend API application
Type `node app.js` in the command line.

The SQLite database file is automatically created in the same folder.

By default, the application starts listening on localhost:3000. If the host changes, the `API_HOST` constant in `frontend/js/script.js` should be updated. 

### 4) Go to the frontend folder, and open the index.html file with a browser
Alternatively, copy the frontend folder to a web server such as IIS, Apache, or Nginx, and open the index.html through the web server.
Either way should work :)

(note: the API server does not host the frontend/HTML)

### 5) Use the app from the browser
