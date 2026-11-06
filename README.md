# URWATUL WUTHQAA (URWA)

**The Firmest Handhold** — a public-facing website for URWA, an Islamic learning and community initiative.

## Website

- `index.html` is the responsive, single-page public website.
- Brand palette: warm beige `#F3EBDD`, elegant black `#171717`, classic gold `#C5A052`, and ivory `#FFFCF6`.
- Sections: Home, About, Programmes, Classes, Teachers, Gatherings, Enquiries, and Student Portal entry point.
- Mobile navigation, FAQ accordions, and the student-area dialog are implemented in the page.

## Preview locally

Open `index.html` in a browser, or run a local static server from this directory (for example, `python -m http.server 8000`) and visit `http://localhost:8000`.

## Before launch

This is currently a static front-end website. The enquiry form is not connected to an email or database, and student/teacher authentication and private dashboards are not active. Connect an approved form endpoint and configure Firebase Authentication/Firestore before collecting personal information or enabling portal access. Confirm official contact details, teacher biographies, class times, and enrolment rules before publishing those details.

## Deployment

The `website-build` branch is the working branch. Review and test it before merging into `main` or connecting it to a production hosting service such as Netlify.
