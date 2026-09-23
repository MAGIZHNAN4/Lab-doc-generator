# Lab Record Generator

A browser-based Lab Record Generator for creating lab records with a document-style preview and exporting them to Word or PNG images.

## Features

- Enter register number, exercise number, date, topic, and aim.
- Add between 1 and 20 questions.
- Enter each question and its program/code.
- Attach one or more output screenshots for each question.
- Resize output screenshots for the document.
- Preview the complete lab record before exporting.
- Edit fields directly from the preview.
- Download the lab record as a `.docx` Word document.
- Export the document pages as PNG images in a ZIP file.
- Includes borders around the document, header table, and exported Word pages.

## How to Use

1. Open `index.html` in a modern web browser.
2. Fill in the lab record details.
3. Add questions using **+ Add question**.
4. Enter the question, program, and output screenshot for each question.
5. Review the document preview.
6. Use **Download Word (.docx)** to save the Word document.
7. Use **Download Pictures (.png, one per page)** to export page images.

## Files

- `index.html` — Main Lab Record Generator application.
- `README.md` — Project documentation.

## Browser Requirements

Use a modern browser such as Google Chrome, Microsoft Edge, or Firefox.

The application loads JSZip and html2canvas from CDN resources, so an internet connection may be required for the export features when running the page directly.

## Output Format

The generated Word document contains:

- Bordered header table
- Register number
- Exercise number
- Date
- Topic
- AIM
- QUESTION
- PROGRAM
- OUTPUT
- RESULT
- Page borders on every page

## License

This project is provided for personal and educational use.
