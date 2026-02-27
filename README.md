
### OSINT Photo Sniffer

A command-line tool written in Python to extract hidden metadata (EXIF) from image files. It supports standard formats like JPEG and modern iPhone formats (HEIC).

**Features**
- HEIC Support: Seamlessly opens iPhone photos using `pillow-heif`.
- GPS Extraction: Automatically finds GPS coordinates in the file.
- Direct Map Link: Generates a clickable Google Maps link for the exact location.
- Binary Filtering: Skips unreadable binary data for a clean terminal output.

**How to Install**

Clone this repository:
   ```bash
   git clone [https://github.com/pocketmarzo/photo_sniffer.git](https://github.com/pocketmarzo/photo_sniffer.git)

**How to Use**

Run the script through your terminal:
   ```bash
   python sniffer.py your_image_name.jpg

