# Table Cleaner & CSV Exporter Chrome Extension

This Chrome Extension scrapes the first `<table>` element on the currently open tab, removes columns 9 and 10 (zero-indexed), and downloads the cleaned table as a CSV file. The file name includes a timestamp in IST (Indian Standard Time).

## Features

- Scrapes the currently open page
- Removes columns 9 (10th) and 10 (11th)
- Downloads the cleaned table as a CSV
- Includes a timestamp in IST in the filename

## Installation (Manual)

1. Download and extract the ZIP folder.
2. Go to `chrome://extensions` in Chrome.
3. Enable "Developer Mode" (top-right corner).
4. Click "Load unpacked" and select the extracted folder.

## Usage

1. Open the webpage with a table you want to export.
2. Click the extension icon.
3. Click **"Export Table as CSV"** – the filtered CSV file will download automatically.

## Icon

The extension uses a placeholder icon (16x16 PNG). You can replace `icon.png` with any other.

## Manifest Permissions

```json
"permissions": ["scripting", "activeTab"]
```

## License

This project is for personal and internal use. No tracking or data collection is involved.
