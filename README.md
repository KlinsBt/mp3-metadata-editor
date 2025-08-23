# MP3 Metadata Editor (Web-Based)

A simple **web-based MP3 metadata editor** that runs entirely in your browser.  
Upload an MP3 file, edit its metadata (title, artist, album, year, genre, track number), change or add cover artwork, and download the updated file — no installation required!

## Features

- Upload any `.mp3` file directly in the browser
- View and edit common ID3 metadata tags:
  - Title
  - Artist
  - Album
  - Year
  - Genre
  - Track number
- Add, replace, or remove album artwork
- Save & download the MP3 with **updated metadata embedded**
- No server required — all processing happens client-side

## Built With

- [jsmediatags](https://github.com/aadsm/jsmediatags) – for reading ID3 tags
- [browser-id3-writer](https://github.com/egoroof/browser-id3-writer) – for writing ID3 tags
- HTML5, CSS3, JavaScript

## How to Use

1. Open the app in your browser (`index.html`).
2. Click **"Choose MP3 File"** and select an MP3.
3. Edit the metadata fields as you like.
4. (Optional) Upload or remove album artwork.
5. Click **"Save & Download"** to download a new MP3 with updated tags.

Note: The app works completely offline. Your MP3 never leaves your computer.
