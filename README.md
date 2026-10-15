# Customer Support Assessment

A single-page HTML prototype for an English-language, phone-based customer support assessment.

## Preview

Open `index.html` in a modern browser. Applicants enter their name and email before starting. The assessment contains 12 questions and a 25-minute time limit. Applicants must provide a response before moving to the next question. It includes support scenarios inspired by the supplied screenshots, the retained typing transcription at question 6, numerical and verbal reasoning, prioritisation, word jumble, mini crossword, and step ordering. At the end, applicants can print or save their responses as a PDF using the browser's print dialog.

## Before live use

This is a front-end prototype. Applicant details and answers remain in browser memory and are not submitted or saved. The PDF is created locally through the browser's print dialog. Question text selection and copying are disabled in the assessment view, but a browser-only page cannot prevent screenshots, developer tools, or access to the HTML source. The transcription script and puzzle answers are included in the HTML source. Before live recruitment use, connect a secure submission service, move protected scoring and question material off the public page, and use a separately hosted audio asset with an accessible alternative. Keep the repository private while developing the assessment.

## Theme colours

- Ink: `#365366`
- Cyan: `#00B5E2`
- Mint: `#3CDBC0`

