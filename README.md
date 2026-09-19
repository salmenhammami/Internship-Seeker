# Internship Seeker

A website for browsing internship offers, built with nothing but HTML, CSS and
Bootstrap.

This was my front-end fundamentals project. No framework, no build step, no back end —
the offers are written straight into the markup. It's here because it's where I
learned responsive layout and semantic markup properly.

## The pages

- **Home** — landing page with the partner companies and a mobile off-canvas menu
- **Offres** — the offer listings
- **Table** — the same offers laid out as a comparison table
- **Sign in** — the login form

Along the way I got the accessibility basics right: landmark elements, ARIA labels on
the navigation, alt text everywhere, and meta tags on each page.

**Built with** HTML5, CSS3 and Bootstrap 5.

## Running it

Nothing to install — open `Home.html` in a browser, or serve the folder:

```bash
git clone https://github.com/salmenhammami/Internship-Seeker.git
cd Internship-Seeker
python -m http.server 8000
```

## What I'd add

Move the offers out of the HTML into a JSON file, render them with JavaScript, and add
filtering by location and duration. Then put it on GitHub Pages.

---

**Salmen Hammami** · [GitHub](https://github.com/salmenhammami) · [LinkedIn](https://www.linkedin.com/in/salmenhammami/)
