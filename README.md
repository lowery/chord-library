# chord-library

Guitar Chord Library is a web-based library of the most commonly used guitar chords. Search chord
variations by name to view diagrams for fret positions and fingering. Search results also contain
sample audio recorded on electric guitar.

## Prerequisites

The web application requires node.js and mongodb. Install node.js on Debian via the following:

    curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
    sudo apt-get install -y nodejs

And mongodb:

     sudo apt-get install mongodb

## Getting Started

Clone the project and run npm install from project root to fetch the dependencies defined
in package.json:

    git clone https://github.com/lowery/chord-library.git
    cd chord-library

    npm install

Start the web server via node by running the following from the project root directory.

    node server.js

Once started the web application will be available at http://localhost:4711/
