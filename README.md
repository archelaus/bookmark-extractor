# Bookmark Extractor
## Description
This script allows you to extract bookmarks from a Chromium-based browser and save them as a prettified HTML file. The script supports automatic detection of the browser's bookmark file path and provides options to specify the path or use a compatibility mode to generate a compatible HTML file which can be imported in any browser.
## Compatibility
- This script is designed to work with Chromium-based browsers like Brave, Vivaldi, Chromium, and Google Chrome.
- Automatic bookmark file detection only works on Linux.
## Requirements
- Python 3.x
## Usage
```
extract-bookmarks [flags]
```
### Flags
- `-h`, `--help`: Show the help message with usage and flag information.
- `-a`, `--automatic`: Automatically detect the default bookmark file path.
- `-f <bookmark_file_path>`, `--file <bookmark_file_path>`: Specify the bookmark file path as an argument.
- `-c`, `--compatible`: Use this flag to enable compatibility mode.

**Note:**
If no flags are provided, the script will check for the bookmark file in the current directory.

### Examples

1. To extract bookmarks using automatic detection:
```
extract-bookmarks -a
```

2. To extract bookmarks by specifying the bookmark file path:
```
extract-bookmarks -f /path/to/bookmarks_file
```
### Generated Output
The extracted bookmarks will be saved as an HTML file with a filename in the format "bookmarks_DD_MM_YYYY.html" in the current directory.

---
For any questions or issues, feel free to open an issue.

> "Organizing is what you do before you do something, so that when you do it, it is not all mixed up." — A.A. Milne
