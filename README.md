# Aptitude Assessment - CS

A single-page HTML assessment for English-language, phone-based customer support applicants.

## Preview

Open `index.html` in a modern browser. Applicants enter their name and email before starting. The assessment has 20 questions and a 30-minute time limit. Each question must be answered before continuing. The repeating sequence is multiple choice, crossword, typing, short call summary, and analytics activity. Crosswords include a bonus word jumble, and queue questions use interactive ordering. At the end, applicants can print or save their responses as a PDF through the browser's print dialog.

## Audio and focus behavior

Typing prompts use the browser's speech synthesis with an English voice when available. Each spoken prompt contains exactly 30 words. Voice quality and availability depend on the applicant's browser and device; this is synthesized speech, not a human recording. No video recording asset was provided, so the typing prompt is audio-only.

The page masks the assessment when its browser tab or window loses focus. This can deter casual switching, but browser pages cannot reliably block operating-system screenshots, detect every capture, or remove content from an image after capture. Copy and paste are blocked within the assessment view, but browser developer tools and page source remain accessible.

## Before live use

This is a front-end prototype. Applicant details and answers stay in browser memory and are not submitted to a secure service. The PDF is generated locally through the browser's print dialog. The current repository is public, so visitors can inspect the question text and audio scripts in `index.html`. Use a private repository and a secure server-side assessment service before sharing with real applicants; keep question material and scoring on the server.

## Theme colours

- Ink: `#365366`
- Cyan: `#00B5E2`
- Mint: `#3CDBC0`
