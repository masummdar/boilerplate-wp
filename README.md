# Boilerplate WP
This is my preffered setup for a new WordPress project with docker.

## Features
- gitignore to ignore unnecessary files on version control.
- editorconfig for editor setup, spacing, tabs etc.
- developmet setup via docker-compose.

## Getting Started
- clone this repo from `https://github.com/masummdar/boilerplate-wp.git`
- edit the .env file and add preffered details
- cd into the directory and run `docker-compose up -d`
- edit windows hosts file to set the virtual host entries. e.g. `127.0.0.1 mydomain.local`
- visit `mydomain.local` and setup WordPress.
