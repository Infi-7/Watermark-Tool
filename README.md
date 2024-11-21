# Watermark Tool

A user-friendly GUI tool for adding watermarks to images, built with Python and Tkinter. This tool allows you to import an image, add a customizable watermark, and save the watermarked image to your device.

---

## Features

- **Import Images:** Supports common image formats such as PNG and JPEG.
- **Add Custom Watermark:**
  - Enter your desired watermark text.
  - Choose the position of the watermark (Top Left, Top Right, Bottom Left, Bottom Right).
- **Preview Watermark:** View the watermarked image on a canvas before saving.
- **Save Watermarked Image:** Export the image with the applied watermark to your device.

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/Watermark-Tool.git
   cd Watermark-Tool
   ```

2. **Install Dependencies:**
   Ensure you have Python installed. Then install the required packages using pip:
   ```bash
   pip install pillow
   ```

3. **Run:**
    ```
    python watermark_tool.py
    ```
## How to Use:

  1. **Launch the application.**
  2. **Import an image:** Click the "Import File" button to select an image from your device.
  3. **Add a watermark:**
       - Enter the watermark text in the text box.
       - Choose the watermark position from the dropdown menu.
       - Click "Add Watermark" to apply the watermark.
  4. **Save the image:** Click the "Save Image" button and specify the save location and file name.

## Screenshots
  ![image](https://github.com/user-attachments/assets/ac61b8a9-881c-43cf-801b-61a1a69ab34b)
  ![image](https://github.com/user-attachments/assets/b6f3d180-fd24-4aed-a3c0-f8b736beaaaf)
  ![image](https://github.com/user-attachments/assets/f142e973-90af-4041-887c-167f0074d5bd)


## File Structure
  ```bash
  Watermarking-Tool/
  ├── fonts/               # Directory for custom fonts (e.g., "Inktype.ttf")
  ├── watermark_tool.py    # Main Python script
  └── README.md            # Documentation file
  ```

## Requirements
  - Python 3.7 or later
  - Pillow (Python Imaging Library)

## Limitations
  - Ensure the fonts/ directory contains the font file Inktype.ttf. Replace it with an available font if missing.
  - Watermark text and positioning are fixed to predefined areas.
