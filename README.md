Asteroid Assemblers

(Started from https://github.com/melonjs/boilerplate )
-------------------------------------------------------------------------------

## To run distribution

To build, be sure you have [node](http://nodejs.org) installed. Clone the project:

    git clone https://github.com/ludumcloud/asteroid-assembler-poc.git

Then in the cloned directory, simply run:

    npm install

Running the game:

	npm start

And you will have the game running on http://localhost:8000

## Building Release Versions

To build:

    npm run build

This will create a `build` directory containing the files that can be uploaded to a server, or packaged into a mobile app.

Note that you may have to edit the file `Gruntfile.js` if you need to better dictate the order your files load in. Note how by default the game.js and resources.js are specified in a specific order.
