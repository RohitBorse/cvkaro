# CVkaro — Free ATS resume builder & checker

**CV banao. Shortlist ho jao.**

🔗 **Live website:** https://cvkaro.co.in

CVkaro helps job seekers in India build a resume that applicant tracking
systems (ATS) can read, check it against any job description, and download
it as a clean PDF — free, with no sign-up.

## Features

- **16 original resume templates** — from traditional (Scholar, Classic) to
  modern (Banner, Timeline) and creative (Slate, Monogram), with 10 accent
  colours and a spacing control to fit one page.
- **Resume builder** with live A4 preview, page-break warnings, section
  reordering, optional photo, and ready-made bullet points for software,
  data, marketing, sales and students.
- **Upload and import** an existing resume (PDF, Word or text). The file is
  read in the browser and sorted into sections automatically. Scanned
  image PDFs are detected and flagged, since ATS software can't read them.
- **ATS checker** that scores a resume out of 100 against a job description:
  keyword match (with synonyms such as JS / JavaScript and extra weight for
  required skills), job-title match, sections, measurable impact, action
  verbs and length, with a keyword-stuffing penalty.
- **One-click PDF export** with a custom engine that keeps the design while
  placing every line of text cleanly, so the PDF itself passes ATS parsing.
- **Cover letter builder** that matches the resume's design.
- **Multiple resumes**, saved privately in the browser's local storage.
- Responsive design with light and dark mode.

## Tech

- Plain HTML, CSS and JavaScript in a single page — no framework, no build step
- PDF reading: pdf.js · Word reading: mammoth.js
- PDF creation: jsPDF + html2canvas with a custom text layer
- Hosted on Cloudflare workers

## Privacy

Resumes never leave the user's device. There is no account system and no
server-side storage of personal data.

## Copyright

© 2026 CVkaro. All rights reserved. See [LICENSE](LICENSE).
