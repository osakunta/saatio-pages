Static Pages for Satalinna Foundation
=====================================

These pages are generated using Hugo. The pages are hosted at Github Pages in this repository's `docs/` directory.


Setting up dev environment
--------------------------
Install [Hugo](https://gohugo.io/getting-started/installing). Before building/running the server, node dependencies must be installed to assets with the following commands:

    cd assets/ && npm install

Development server can be run with:

    hugo server -D


Deploying
---------
To deploy a new version of the site, run

    hugo

and commit the changes to Github.
