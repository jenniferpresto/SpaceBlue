SpaceBlue
=========

####General notes
This app is an example of reading information sent via BLE in a node app, and sending that information to Processing via Spacebrew. The app reads information sent from two RedBear BLE Shields -- the app is currently set up for two specific, individual shields -- and uses the data in a Processing sound app. More information about Spacebrew can be found [here](http://docs.spacebrew.cc/). The spacebrew_and_BLE.js node app uses the [NOBLE library](https://github.com/sandeepmistry/noble).

####Files included here

* Arduino/: Contains the file to upload to the RedBear BLE Shield for Arduino.
* sb_bluetooth_processing/: Contains the files to run the Processing sketch. sb_bluetooth_processing.pde is the main file.
* package.json: The JSON package for running the node.js app. You may type "npm start" at the command line to run the node app.
* spacebrew.js: Node.js spacebrew library.
* spacebrew_and_BLE.js: Node.js app integrating BLE.


####To run the app
Navigate to SpaceBlue folder on the command line and type "npm start". Start the Processing app by opening sb_bluetooth_processing.pde and clicking "Run". These are currently configured to use the public [Spacebrew sandbox](http://spacebrew.github.io/spacebrew/admin/admin.html?server=sandbox.spacebrew.cc). Connect the appropriate subscribers and publishers there.