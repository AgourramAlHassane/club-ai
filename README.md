# Club AI

A responsive, four-page website presenting a fictional university AI club and its discovery day. Created as an individual HTML5 and CSS3 mini-project for Filière IL at Université Ibn Zohr.

## Pages

- **Accueil** (`index.html`): introduction to Club AI and its poster.
- **Ateliers** (`ateliers.html`): three workshop cards—Assistant pédagogique, Qualité du code, and Prototypage d’application.
- **Programme** (`programme.html`): the day’s schedule and fictional contact details.
- **Contact** (`contact.html`): a demonstration form for choosing a workshop and leaving a message.

## Features

- Shared navigation and stylesheet across all four pages.
- Responsive layouts using CSS Grid, Flexbox, and media queries.
- Custom SVG robot logo and favicon.
- Workshop cards and a schedule table.
- Form fields with native HTML5 validation for required name and email.

## Technologies

- HTML5
- CSS3
- Montserrat through Google Fonts, with Arial and sans-serif fallbacks
- GitHub for source hosting
- Vercel for deployment

No JavaScript, framework, or backend is used.

## Project structure

```text
club-ai/
├── index.html
├── ateliers.html
├── programme.html
├── contact.html
├── style.css
├── README.md
├── images/
│   ├── favicon_club_AI.svg
│   ├── Club AI_ Neon Campus Innovation.png
│   ├── atelier-1.png
│   ├── atelier-2.png
│   └── atelier-3.png
```

## Open locally

1. Download the repository using **Code → Download ZIP**, or clone it.
2. Extract the ZIP if needed.
3. Open `index.html` in your browser.

Keep the HTML files, stylesheet, and `images/` folder together. An internet connection is needed to load Google Fonts; a fallback font is used otherwise.

## Deployment

The website is deployed with Vercel from the connected GitHub repository.

For a fresh deployment, import the repository into Vercel, select **Other** as the application preset, and use the repository root as the root directory. No build command or environment variables are required.

Commits to the connected production branch trigger a new deployment.

## Form demonstration

The contact form is an educational simulation. Use fictional data only. No backend or email delivery service is included.

Test required-field and email-format validation, workshop selection, radio buttons, checkboxes, and the reset button. The exact behavior after clicking **Envoyer** depends on the form method in `contact.html`; a GET form can place entered values in the URL.

## Author

**AGOURRAM Al Hassane — Filière IL**

Educational project. Event dates, rooms, and contact details are fictional.
