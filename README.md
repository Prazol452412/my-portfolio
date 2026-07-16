#Portfolio Website

A single-page personal portfolio website built with semantic HTML5 and
CSS. The page uses `<header>`, `<nav>`, `<main>`, `<section>`, and
`<article>` throughout, with all sections accessible via in-page anchor
links rather than separate HTML files.

## About This Project

This site showcases my background, skills, projects, work experience,
and contact details on a single scrollable page. It demonstrates
semantic HTML structure paired with a custom stylesheet, including a
card-based skills grid, a flex-based about section, and an accessible
contact form with properly paired labels and inputs.

## Page Sections

| Section | Anchor | Description |
|---|---|---|
| About | `#about` | Biography with profile photo, laid out with `.about-container` |
| Introduction | `#intro` | Short personal tagline |
| Highlights | `#highlights` | Quick bullet list of key facts |
| Skills | `#skills` | Skill categories displayed as cards in `.skill-grid` |
| Projects | `#projects` | Project write-ups as `<article>` elements with GitHub links |
| Experience | `#experience` | Work and education history as `<article>` elements |
| Contact | `#contact` | Contact form and social/email icon links |

## Technology Used

- HTML5 with semantic elements (`header`, `nav`, `main`, `section`, `article`, `footer`)
- Custom CSS (`style.css`) — no framework, no CSS libraries
- CSS Grid for the responsive skills layout (`.skill-grid`)
- Flexbox for the header, nav, and about-section layout
- No JavaScript

## Key CSS Features

- `.about-container` — flex layout pairing the bio text with the profile photo
- `.skill-grid` / `.skill-card` — responsive auto-fit grid of skill categories, each rendered as a `<dl>` with one `<dt>`/`<dd>` pair
- Header search form styled with rounded input and button, matching the site's blue color scheme
- Contact form inputs and textarea styled full-width with consistent padding and border radius

## How to View

Clone or download this repository, then open `index.html` directly in
any web browser. No build step, server, or dependencies are required.

```bash
git clone https://github.com/Prazol452412/my-portfolio.git
cd my-portfolio
```

Then open `index.html` in a browser of your choice.

## Images

Two images are used, located in the `images/` directory:

- `images/law.jpg` — displayed as the logo in the header
- `images/profile.jpg` — displayed in the About section

## Contact

- Email: [projwol.114381@mitnepal.edu.np](mailto:projwol.114381@mitnepal.edu.np)
- LinkedIn: [linkedin.com/in/prazol-nepal-8a5187349](https://www.linkedin.com/in/prazol-nepal-8a5187349)
- GitHub: [github.com/Prazol452412](https://github.com/Prazol452412)

## License

This project is open for reference and learning purposes. Feel free to
explore the structure, but please do not copy the personal content as
your own.
