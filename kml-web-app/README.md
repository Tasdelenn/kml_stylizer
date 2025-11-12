# KML Merger & Stylizer (Client-Side)

KML Merger & Stylizer is a web application that allows users to upload multiple KML files, customize their styles (line color, line width, fill color, fill opacity), and merge them into a single downloadable KML file. All processing is done on the client-side, meaning your files are never uploaded to a server.

## Features

*   Upload multiple KML files via selection or drag-and-drop.
*   Customize style for each KML file individually:
    *   Line Color
    *   Line Width
    *   Fill Color
    *   Fill Opacity
*   Merge selected KML files into one.
*   Specify an optional output filename.
*   Dark/Light mode for user interface.
*   Responsive design.
*   **100% Client-Side:** All KML processing happens in your browser. Your data stays private.

## Project Structure

```
.
├── README.md
├── index.html       # Frontend HTML, CSS (Tailwind), and JavaScript
└── test_data/
    ├── ... (sample KML files)
```

## Tech Stack

*   **Frontend:** HTML, Tailwind CSS, Vanilla JavaScript

## Setup and Usage

1.  **Open `index.html`:**
    Simply open the `index.html` file in your web browser. No server or build steps are required.

### How to Use

1.  **Select KML Files:** Click the "Select KML Files" button or drag and drop your KML files onto the designated area.
2.  **Customize Styles:** For each uploaded file, you can adjust:
    *   Line Color
    *   Line Width
    *   Fill Color
    *   Fill Opacity (%)
3.  **Set Output Filename (Optional):** Enter a desired name for the merged file (without the `.kml` extension). If left blank, it defaults to `merged.kml`.
4.  **Merge Files:** Click the "Merge Files" button.
5.  **Download:** The merged KML file will be automatically downloaded by your browser.

## Notes

*   The application expects valid KML files. Parsing errors might occur with malformed files.
*   The styling options are applied to all placemarks within a given KML file.
*   The `test_data` directory contains sample KML files that can be used for testing.

## Future Enhancements (Potential)

*   More advanced styling options (e.g., icons, labels).
*   Individual placemark styling.
*   Preview of KML files on a map before merging.
