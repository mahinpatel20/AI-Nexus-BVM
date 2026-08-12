# AI Nexus BVM

Official website for **AI Nexus BVM** — a student-run Artificial Intelligence & Machine Learning club.

🔗 **Live site:** _add your GitHub Pages link here once deployed_
📧 **Contact:** ainexusbvm@gmail.com

---

## About

AI Nexus BVM is a student community built around six focus tracks — Machine Learning, Computer Vision, NLP & LLMs, Generative AI, Robotics & IoT, and Data Science. The site introduces the club, its activities, and how to get in touch or join.

## Tech Stack

This is a single-page static website — no build step, no dependencies, no backend.

- **HTML5 / CSS3** — layout, theming, responsive design
- **Vanilla JavaScript** — scroll animations, mobile nav, contact form
- **Google Fonts** — Space Grotesk, JetBrains Mono, Inter

## File Structure

```
├── index.html      # Entire site (markup, styles, and script in one file)
└── README.md
```

## Running Locally

No installation needed. Either:

1. Double-click `index.html` to open it directly in a browser, **or**
2. Serve it locally:
   ```bash
   python3 -m http.server 8000
   ```
   then visit `http://localhost:8000`

## Deploying on GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Branch**, select `main` and `/root`, then **Save**.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a few minutes.

## Customizing

Everything lives in `index.html`:

- **Team section** — replace the placeholder initials/roles with real member names, roles, and photos.
- **Domains** — edit the six track cards to match what your club actually runs.
- **Activities** — update the cadence and descriptions of workshops, sprints, and talks.
- **Contact form** — currently opens the visitor's email client via `mailto:`. To collect submissions directly, connect it to a service like [Formspree](https://formspree.io) or [Google Forms](https://forms.google.com).
- **Colors/fonts** — all defined as CSS variables (`:root`) near the top of the `<style>` block.

## Contributing

Club members are welcome to open issues or pull requests for content updates, new sections, or fixes.

## License

Free to use and adapt for AI Nexus BVM's own purposes.
