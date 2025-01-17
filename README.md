
## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd Tracker
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    node app.js
    ```

2. Open your browser and navigate to [http://localhost:5000](http://_vscodecontentref_/5).

## Project Details

### [app.js](http://_vscodecontentref_/6)

This is the main server file. It sets up an Express server, integrates Socket.io for real-time communication, and serves the static files and views.

### [style.css](http://_vscodecontentref_/7)

This file contains the CSS styles for the application.

### [script.js](http://_vscodecontentref_/8)

This file contains the client-side JavaScript code. It uses the Geolocation API to get the user's location and sends it to the server via Socket.io. It also uses Leaflet to display the map and markers.

### [index.ejs](http://_vscodecontentref_/9)

This is the main HTML file rendered by the server. It includes the necessary styles and scripts.

### [package.json](http://_vscodecontentref_/10)

This file contains the project metadata and dependencies.

## Dependencies

- [Express](https://expressjs.com/)
- [EJS](https://ejs.co/)
- [Socket.io](https://socket.io/)
- [Leaflet](https://leafletjs.com/)

