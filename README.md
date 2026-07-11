# Portfolio Website

A static, multi-page personal portfolio website built entirely with plain HTML. No CSS files, no JavaScript, and no inline styles are used anywhere in this project. Layout elements such as the horizontal navigation bar and header are achieved using native HTML tags like `<table>`, in the style of early web pages built before CSS was standard.

## About This Project

This site showcases my background, skills, certifications, projects, and work experience. It is intentionally built without any styling to demonstrate strong command of core HTML tags and semantic structure, including tables, lists, forms, and metadata elements.

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Landing page with a short introduction and site overview |
| About | `pages/about.html` | Background, skills, and certifications |
| Projects | `pages/projects.html` | Selected projects with descriptions and links |
| Experience | `pages/experience.html` | Work history, education, and leadership timeline |
| Contact | `pages/contact.html` | Contact details and a mailto-based contact form |

## Technology Used

- HTML5 only
- No CSS (no external stylesheets, no `<style>` tags, no inline styles)
- No JavaScript
- Tables used for layout in place of CSS flexbox or grid, since no styling is available

## How to View

Clone or download this repository, then open `index.html` directly in any web browser. No build step, server, or dependencies are required.

```bash
git clone https://github.com/Prazol452412/my-portfolio.git
cd my-portfolio
```

Then open `index.html` in a browser of your choice.

## Images

Two images are used across the site, located in the `images/` directory:

- `images/law.jpg` — displayed as the logo in the header on every page
- `images/profile.jpg` — displayed on the About page

Paths are relative, so `index.html` references `images/...` directly, while pages inside `pages/` reference `../images/...`.

## Contact

- Email: [projwol.114381@mitnepal.edu.np](mailto:projwol.114381@mitnepal.edu.np)
- LinkedIn: [linkedin.com/in/prazol-nepal-8a5187349](https://www.linkedin.com/in/prazol-nepal-8a5187349)
- GitHub: [github.com/Prazol452412](https://github.com/Prazol452412)

## License

This project is open for reference and learning purposes. Feel free to explore the structure, but please do not copy the personal content as your own.
