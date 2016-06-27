## Flatbuffer visual editor and testing framework.  

node.js app to enable visual editing of flatbuffer schemas locally as well as on a server. The basic features:

* Complete visual editing of multi-layered flatbuffer schemas with pull down lists for supported data types, support for nested types, etc..
* Ability to export a schema file from a visual definition.
* Ability to import a schema file and have a visualization of that schema you can use to edit.
* Ability to copy and paste schema definitions in and out of the tool as a substitute for using files.

## Usage Instructions
1. Install Node 5+
2. clone the flatbuffers-visual git: `git clone https://github.com/LamdaFu/flatbuffers-visual`
3. `cd flatbuffers-visual`
2. Run `npm install webpack webpack-dev-server --save-dev`
3. Run `npm start` to start the hot reload server.
4. Go to `localhost:3000` to view the app.
