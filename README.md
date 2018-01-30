Simple Static Site
==================

This repo contains a basic `Dockerfile` that can build and serve basic static HTML site.

Usage
-----

Build the container image:

    $ docker build -t static-site .

Start the container, exposing port 80 locally on port 3000

    $ docker run -it --rm -p 3000:80 -t static-site

You can now visit (http://0.0.0.0:3000)[http://0.0.0.0:3000]
