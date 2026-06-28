# SibeliusGUB

A lightweight, browser-based tool to convert MusicXML files into professional choral scores (SATB) in PDF format.

## Features
- **Drag & Drop**: Easily upload `.xml` or `.musicxml` files.
- **Rendering**: Uses OpenSheetMusicDisplay (OSMD) to render the score directly in the browser.
- **PDF Export**: Generates and downloads a multi-page PDF of the rendered score using jsPDF and html2canvas.
- **Privacy-First**: All processing happens client-side in the browser. No data is sent to a server.

## Setup
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the local development server.

## Tech Stack
- Vite
- OpenSheetMusicDisplay (OSMD)
- jsPDF
- html2canvas
