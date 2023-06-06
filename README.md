# docgrouper

A command-line tool for quickly organizing groups of images into multiple PDFs

## Features

- Convert files to PDF using the system-installed imagemagick
- Preview images using the system viewer
- Fast-paced interactive sorting shell
- Ability to insert an image to a previous document (saves to whichever folder ("document") specified)
- Ability to quickly add images to the previous document
- Pick up where you left off by rerunning `docgrouper group` command

## Roadmap
1. `cleanup` function to remove directories after converting to PDF
2. GUI?


## Installing

First, install `imagemagick`: `sudo apt install imagemagick`

The download the `docgrouper` file, set as executable, and place it somewhere on PATH.


## Usage

`docgrouper`

Display help message and exit

`docgrouper group`

Run the interactive console for displaying photos and grouping them into documents

`docgrouper pdf`

Creates a PDF for each subfolder

`docgrouper run`

Group documents, then convert to PDF (for shorter sessions)

## Limitations
- Only works on Linux
- Uses the system image viewer and can be a bit slow to load images
- imagemagick may need to be reconfigured if pdf creation is not working
