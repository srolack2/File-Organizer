# File Organizer

## Overview
The File Organizer is a Python automation script designed to organize files in a directory into subfolders based on their file types. This project is a simple yet effective example of Python's ability to handle file operations and is perfect for showcasing automation skills.

## Features
- Automatically creates folders for various file categories (e.g., Images, Documents, Videos, etc.).
- Moves files into appropriate folders based on their extensions.
- Skips directories to avoid unwanted changes.
- Handles missing folders gracefully by creating them automatically.

## Categories and Extensions
The following categories and file extensions are supported:

| Category    | Extensions                                   |
|-------------|---------------------------------------------|
| Images      | `.jpg`, `.jpeg`, `.png`, `.gif`, `.bmp`     |
| Documents   | `.pdf`, `.docx`, `.txt`, `.xlsx`, `.pptx`   |
| Videos      | `.mp4`, `.mkv`, `.mov`, `.avi`             |
| Music       | `.mp3`, `.wav`, `.aac`                     |
| Archives    | `.zip`, `.rar`, `.7z`, `.tar`              |
| Scripts     | `.py`, `.js`, `.html`, `.css`              |
| Others      | Any file not fitting into the above groups |

## Requirements
- Python 3.7+

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/file-organizer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd file-organizer
   ```
3. Install any dependencies (if applicable):
   ```bash
   pip install -r requirements.txt
   ```
   *Note: This script has no additional dependencies beyond Python's standard library.*

## Usage
1. Run the script:
   ```bash
   python organizer.py
   ```
2. Enter the directory path you want to organize when prompted.
3. The script will create subfolders for each file category and move files accordingly.

## Example
### Before Running the Script:
```
example_directory/
├── image1.jpg
├── document1.pdf
├── video1.mp4
├── music1.mp3
├── archive1.zip
```

### After Running the Script:
```
example_directory/
├── Images/
│   └── image1.jpg
├── Documents/
│   └── document1.pdf
├── Videos/
│   └── video1.mp4
├── Music/
│   └── music1.mp3
├── Archives/
    └── archive1.zip
```

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- This project was inspired by the need to organize files efficiently.

## Contact
For any questions or suggestions, feel free to contact:
- **Name**: Sylvester Rolack II
- **Email**: srolack2@gmail.com
- **GitHub**: [srolack2](https://github.com/srolack2)

