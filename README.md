## What is this?
This repository contains the source code to build the HTML for the public API documentation site (https://docs.gog-games.com) with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Dependencies
 - Requires you have Docker installed. Learn how here: https://docs.docker.com/get-docker
 - Pull the image: `docker pull squidfunk/mkdocs-material`

## Building
- Navigate into build folder: `cd build`
- Build HTML with: `sudo docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build`
- HTML is built into the `site` folder

## Previewing
You can edit and view changes with: `sudo docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material`. **Note: must be in source directory** `mkdocs`!  Then navigate to [localhost:8000](http://localhost:8000)
