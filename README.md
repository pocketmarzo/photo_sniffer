# OSINT Photo Sniffer

A standalone command-line tool to extract hidden metadata (EXIF) from image files. It supports standard formats like JPEG and modern iPhone formats (HEIC).

## Features

- **HEIC Support**: Seamlessly opens iPhone photos using the pillow-heif library.
- **GPS Extraction**: Automatically identifies and decodes GPS coordinates.
- **Direct Map Link**: Generates a clickable Google Maps link for the exact location.
- **Binary Filtering**: Skips unreadable binary data for a clean terminal output.

## Installation

1. Clone this repository:

```bash
git clone [https://github.com/pocketmarzo/photo-sniffer.git](https://github.com/pocketmarzo/photo-sniffer.git)