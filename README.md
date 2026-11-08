# Nour Zaatari Studio — Portfolio

Static one-page portfolio site (HTML / CSS / vanilla JS, no build step).
Served locally by Herd at http://nour-portfolio.test.

```
index.html          page markup (sections: hero, about, services, projects, philosophy, contact)
css/styles.css      styles — palette tokens at the top in :root
js/main.js          header scroll state, mobile menu, scroll reveals, contact form
assets/images/      logo.png (original), logo-mark.png (cropped), favicon.svg
```

## Brand

- Font: Montserrat (Google Fonts)
- Palette: warm ivory `#EAE5DC` · sand `#B6A58F` · stone `#79766E` · charcoal `#343532` · off-white `#F9F7F2`

## Placeholders to replace

Search for `PLACEHOLDER` in `index.html` and `css/styles.css`.

- **Hero image**: `.hero-media` background URL in `css/styles.css`
- **About image**: studio/portrait photo in the About section
- **Projects**: 6 Unsplash images plus made-up names and years
- **Copy**: About paragraphs, service descriptions, philosophy quote
- **Contact details**: email (also `data-email` on the form), phone, Instagram link

The contact form has no backend yet. It validates the fields, then opens the visitor's email app with the enquiry pre-filled. Swap the submit handler in `js/main.js` for a real endpoint (Formspree, a Laravel route, etc.) when one is ready.
