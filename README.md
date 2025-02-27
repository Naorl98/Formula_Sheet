# Formula Sheet Creator

![Python](https://img.shields.io/badge/python-v3.8%2B-blue)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-yellow)
![License](https://img.shields.io/badge/license-MIT-green)
![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen)

## Overview

The **Formula Sheet Creator** application helps students create organized and compact formula sheets from class summaries. This GUI-based tool processes PDF files, removes unnecessary white spaces, and resizes content to fit efficiently within the generated sheet. It also allows users to specify custom output filenames and provides a progress tracker.

---
## Author
This project was created by **Naor Ladani**.

## License
© Naor Ladani, [2025]. All rights reserved.


## Features

- **PDF Processing:**
  - Removes unnecessary white spaces and empty columns.
  - Allows resizing content by percentage.
  - Handles errors gracefully for failed pages.

- **Custom Output:**
  - Default or user-defined file naming for generated PDFs.
  - Automatically saves outputs to a dedicated `FormulaSheet` directory on the desktop.

- **User-Friendly GUI:**
  - Built with Tkinter for an intuitive interface.
  - Progress bar and status messages for better user experience.

---

## Installation

### Prerequisites

- Python 3.8+
- Required libraries:
  - `cv2` (OpenCV)
  - `fitz` (PyMuPDF)
  - `numpy`
  - `FPDF`

Install dependencies using pip:
```bash
pip install opencv-python PyMuPDF numpy fpdf
```

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/formula-sheet-creator.git
   ```

2. Navigate to the project directory:
   ```bash
   cd formula-sheet-creator
   ```

3. Run the application:
   ```bash
   python formula_sheet_creator.py
   ```

---

## Usage

1. **Launch the App:**
   - Run the script to open the Formula Sheet Creator GUI.

2. **Upload a PDF:**
   - Click the `Upload` button to browse and select a PDF file.

3. **Set Resizing Percentage:**
   - Enter the desired scaling percentage (e.g., `80` for 80%).

4. **Specify Output Name (Optional):**
   - Provide a name for the output file or use the default naming format (`NEW-filename`).

5. **Process the File:**
   - Monitor progress through the progress bar and status messages.
   - Once complete, the processed file will be saved to the `FormulaSheet` directory on your desktop.

---

## GUI Components

- **Input Fields:**
  - Resize percentage
  - Output file name

- **Check Options:**
  - "Do not delete empty lines and columns" checkbox for customized processing.

- **Progress Indicators:**
  - A progress bar and status label for real-time feedback.

---

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or feedback, please open an issue or contact [Your Name](mailto:your-email@example.com).

---

### Show Your Support

If you find this project useful, give it a ⭐ on GitHub!
