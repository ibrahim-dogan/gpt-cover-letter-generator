# Cover Letter Generator

This is a simple web application that generates cover letters based on your CV and a job description. It utilizes the OpenAI GPT-3.5 Turbo model to generate the cover letter content. The generated cover letter can be previewed, downloaded as a PDF, and copied to the clipboard.

## Getting Started

To use the Cover Letter Generator, follow these steps:

1. Open the [Cover Letter Generator](index.html) in your web browser.
2. Paste your CV into the "Paste your CV here" textarea.
3. Paste the job description into the "Paste job description here" textarea.
4. Click the "Generate" button to generate the cover letter based on the provided inputs.
5. The generated cover letter will appear in the "Cover letter will appear here" textarea.
6. Click the "Copy" button to copy the cover letter to the clipboard.
7. Click the "Download PDF" button to download the cover letter as a PDF file.

## Additional Features

### Settings

The application provides a settings option to enter your OpenAI API key. This allows you to use your own API key for making requests to the OpenAI API. To access the settings, click the "Settings" button, and a modal will appear where you can enter your API key.

### Auto-Save

The application automatically saves your CV and job description locally in your browser's storage. So, when you revisit the site, your previous inputs will be populated in the respective textareas.

## Dependencies

The Cover Letter Generator utilizes the following dependencies:

- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework used for styling the user interface.
- [pdfmake](https://pdfmake.github.io/docs/): A JavaScript library used for generating PDF documents.

## Note

Please note that this application requires a valid OpenAI API key to function properly. If you don't have an API key, you can sign up for one at the [OpenAI website](https://openai.com/).