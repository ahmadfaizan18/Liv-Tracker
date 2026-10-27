# Liv-Tracker
Live position tracking web application. This displays other users who are connected.

## Features
-Real time position tracking with Socket.IO.
-Interactive map provided by Leaflet.js and OpenStreetMap.
-Position tracking via browser with Geolocation API.
-Users can enter their name to be identified.
-Markers will automatically be removed when they disconnect.

## Technologies Used
-Backend: Node.js, Express.js
-Realtime: Socket.IO
-Frontend: HTML, CSS, JavaScript
-Map: Leaflet.js, OpenStreetMap
-Templating: EJS

## Requirements
-Node.js and npm installed.
-Modern browser with geolocation capabilities.
-Location permission enabled.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ahmadfaizan18/Liv-Tracker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Liv-Tracker
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the application:
   ```bash
   node app.js
   ```
5. Open `http://localhost:3000` in your browser and allow location access.

## Notes
-You will need to allow location in your browser. It will also require a secure context, which localhost usually is.
-This application uses OpenStreetMap and Leaflet.js and Socket.IO client from external sources.
-The current server will push live updates to all clients.

## License
The license for this project is declared as ISC in package.json. Please check the license terms and conditions for redistribution of this project.