# ACIDS - Website

Website for **ACIDS**, a collective working across music, technology, and artistic R&D.

This project is based on the **Swissfolio** Astro + Tailwind CSS template and has been modified to fit the needs and identity of the ACIDS collective.

---

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

It is a derivative work of the Swissfolio template:
https://github.com/michael-andreuzza/swissfolio

In accordance with the GPL-3.0 license:
- The source code of this website is publicly available
- Modifications and redistributions remain under the same license

See the `LICENSE` file for details.

---

## Tech Stack

- Astro
- Tailwind CSS v4
- AOS (Animate On Scroll)

Tailwind CSS is used via a single global stylesheet:

```css
@import "tailwindcss";
@plugin "@tailwindcss/typography";
@plugin "@tailwindcss/forms";
```

Custom styles are defined using the `@theme` directive in `src/styles/global.css`.

---

## Project Structure

```text
/
├── public/
├── src/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   └── styles/
└── package.json
```

---

## Development

All commands are run from the root of the project.

| Command | Description |
| ------ | ----------- |
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server |
| `npm run build` | Build production site |
| `npm run preview` | Preview production build |

---

## Notes

This repository is public in order to comply with the GPL-3.0 license requirements.

Content, branding, and visuals are specific to ACIDS.
