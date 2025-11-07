# Resume Website - INFO1005 Assessment 3

Live hosting target: GitHub Pages  
Student: Michael E. (Western Sydney University)  
Created: 2025-11-07

This repository contains a multi-page resume website built with Bootstrap 5, meeting the assessment requirements:
- Pages: Home (index.html), About, Experience, Contact
- Responsive layout using Bootstrap grid and utilities
- Clear typography hierarchy (Google Fonts)
- PDF resume download (assets/pdf/Michael_E_Resume.pdf)
- Accessibility basics (labels, landmarks, focus styles)
- Custom CSS (variables, media queries, comments, naming conventions)

## File tree
resume_site/
- index.html
- about.html
- experience.html
- contact.html
- assets/css/styles.css
- assets/img/portrait_placeholder.png
- assets/img/wireframe_home.png
- assets/pdf/Michael_E_Resume.pdf

## Deploy to GitHub Pages
1) Create a public GitHub repository.  
2) Upload all files (keep folder structure).  
3) Settings -> Pages -> Source: Deploy from a branch, Branch: main (root).  
4) Wait for deployment; your site appears at https://<username>.github.io/<repo>

## What you still need to do
- Replace assets/pdf/Michael_E_Resume.pdf with your real PDF (same name) OR update the link.
- Replace assets/img/portrait_placeholder.png with your photo (optimise ~200-400 KB, 1200px wide).
- Update contact details and LinkedIn in contact.html.
- Configure a form backend (Netlify Forms, EmailJS, Formspree) or use the mailto fallback.
- Validate HTML/CSS and test in Chrome and Firefox on desktop + mobile.

## Usability testing plan (3 users)
Tasks: (1) Find and open the PDF resume (2) Find a relevant skill (3) Send a message via contact page.  
Success: each under 30 sec, no confusion.  
Record sheet columns: Participant, Device, T1 sec/notes, T2 sec/notes, T3 sec/notes, Issues, Priority.

## Conceptual understanding (paste into submission)
Purpose and audience. This website presents my skills and experience as a civil engineering student seeking a trainee engineering role. The intended audience is hiring managers who value clarity, reliability, and practical capability. The site therefore emphasises fast scanning, consistent navigation, and a professional tone.

Layout and hierarchy. I use Bootstrap’s grid to create a clean, responsive structure that adapts from mobile to desktop without horizontal scrolling. Visual hierarchy is established through a strong page title, clear section headings, short paragraphs, and consistent spacing. Headings use Merriweather for contrast with the Inter body font, improving readability and scannability. Interactive elements use descriptive labels and a visible focus outline for accessibility.

Branding and typography. A restrained palette with a deep red accent and high-contrast text supports a professional identity. Typography is set for comfortable reading and consistent line length. Cards and panels create neat groupings of related information, helping users to locate key content quickly (for example, resume download, skills summary, and project highlights).

Responsiveness and components. Bootstrap utilities handle spacing, alignment, and responsiveness while custom CSS variables provide site identity without breaking framework conventions. The navigation collapses into a toggle on small screens, the hero image resizes responsibly, and content stacks into single-column layouts on mobile to preserve readability.

Accessibility and content accuracy. Semantic HTML landmarks (nav, header, main, footer), labels for form fields, and appropriate alt text strengthen accessibility. Links have clear naming (“Download Resume”) to support both screen-reader and SEO. All content is concise and specific to my goals, avoiding generic, long paragraphs.

Testing and iteration. I validated the HTML/CSS with W3C tools and conducted quick usability testing with three users on different devices. Feedback led to adjustments: clearer button text, increased spacing between section groups, and improved contact details visibility. I then re-tested to confirm the changes solved the observed issues.
