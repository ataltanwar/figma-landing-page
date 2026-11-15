# WSCube Tech Digital Marketing Landing Page

A static, responsive landing page for a digital marketing course. The page is designed to promote the course, highlight its benefits, collect demo-session registrations, and provide course and career information.

## Features

- Sticky navigation header with:
  - WSCube Tech logo
  - WhatsApp enquiry link
  - Click-to-call link
- Hero section with course overview and primary calls to action
- Demo-session registration form
- Course statistics, including students trained, highest CTC, and recruiting partners
- Course highlights and learning benefits
- Digital marketing career options
- Certification information
- Curriculum overview
- Student testimonials
- Frequently asked questions section
- Companies hiring digital marketing professionals
- Footer with copyright information
- Hover effects and visual styling built with CSS

## Technologies Used

- HTML5
- CSS3
- Google Fonts - Inter
- Font Awesome
- PNG, SVG, and JPG image assets

## Project Structure

```text
.
├── index.html
├── Readme.md
├── CSS/
│   └── style.css
└── Images/
    ├── Cb-icon/
    ├── Illustration/
    ├── Learn-icon/
    ├── Profile/
    └── Website Images/
```

## Getting Started

This project does not require a build tool, package manager, or backend server.

### Option 1: Open directly

Double-click `index.html` to open the page in a browser.

### Option 2: Run a local server

From the project directory, start any local static server. For example, with Python:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

## Usage

- Use the navigation buttons to open the WhatsApp enquiry link or initiate a phone call.
- Complete the registration form to test the client-side form validation.
- Review the course highlights, curriculum, career options, certification details, and testimonials by scrolling through the page.
- Resize the browser window to inspect the layout at different screen sizes.

## Notes

- The registration form currently has no backend submission endpoint.
- Several calls to action are visual buttons and do not yet navigate to a booking or curriculum page.
- Some course descriptions and FAQ text are placeholder content and can be replaced with final copy.
- Google Fonts and Font Awesome are loaded from external CDNs, so an internet connection is recommended for the complete visual experience.

## Customization

- Update page content and links in `index.html`.
- Modify colors, spacing, typography, layout, and hover effects in `CSS/style.css`.
- Replace or add visual assets in the `Images/` directory.