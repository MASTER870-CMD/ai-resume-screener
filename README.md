# AI Resume Screener

A simple, client-side AI Resume Screener built with HTML, CSS, and JavaScript. This tool allows users to upload a resume (ideally in PDF format), extracts the text, and presents the extracted content for review.

# Project 📸 view
<img width="1160" height="606" alt="image" src="https://github.com/user-attachments/assets/4b4d11b2-70f4-4458-a4dd-4824f177ed02" />


## Features

*   **Resume Upload:** Allows users to upload resume files.
*   **PDF Extraction:** Extracts text from PDF files using PDF.js.
*   **Text Display:** Displays the extracted text in a user-friendly format.
*   **Client-Side Processing:** Operates entirely in the user's browser, ensuring data privacy.
*   **Responsive Design:** Utilizes Bootstrap for a responsive layout.
*   **Theming:** Styled with a professional white and green color scheme.

## Requirements

*   Modern web browser with JavaScript support.
*   PDF.js library for PDF parsing.
*   Bootstrap CSS for styling.

## Installation

No installation is required. Simply download or clone the repository and open the `index.html` file in your browser.

## Usage

1.  Open the `index.html` file in your web browser.
2.  Use the file input element to select a resume file (preferably in PDF format).
3.  The extracted text from the resume will be displayed in the designated area.

## File Structure

```
ai-resume-screener/
├── index.html       # Main HTML file containing the structure and UI.
└── README.md        # Documentation for the project.
```

## Testing

Currently, there are no automated tests. Manual testing can be performed by:

1.  Opening `index.html` in a browser.
2.  Uploading various resume files (PDFs).
3.  Verifying that the text extraction is accurate and the UI is responsive.

## Configuration

There is no configuration file.  The look and feel can be configured inside the `<style>` tag in `index.html`.  Specifically, the CSS variables in `:root` control the color scheme.

## Contributing

Contributions are welcome! To contribute:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes.
4.  Submit a pull request.

## License

This project has no license. All rights are reserved.

## Improvements

*   **AI-powered analysis:** Integrate with an AI model (either a local model, or external API) to perform automated resume screening based on keywords, skills, or experience.
*   **Keyword Highlighting:** Highlight important keywords or skills within the extracted text.
*   **Scoring/Ranking:** Implement a scoring system to rank resumes based on predefined criteria.
*   **More robust error handling:** Add more error handling to catch and display informative messages if file uploads fail, files are the wrong type, or text extraction fails.
*   **Automated Testing:** Implement unit and integration tests to ensure code quality and prevent regressions.
*   **UI enhancements:** Further improve the user interface and user experience.
*   **Support more file types:** Expand support to other common resume file formats (e.g., .docx, .txt).
*   **Download Extracted Text:** Allow users to download the extracted text as a file.
