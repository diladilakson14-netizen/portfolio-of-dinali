# Dinali Perera : Brand Strategist & Interactive Designer (Student Project)

A 3-page responsive portfolio for Sri Lankan photojournalist Thilina Kaluthotage, built from his public profiles. It is not his official site. Palette: off-white, teal, slate, orange, with a matching dark mode.

## Project structure
```
index.html (home + projects), about.html, contact.html
css/style.css          theme, layout, animation
js/main.js             menu, dark mode, JSON gallery, modal
js/validation.js       contact form validation
data/portfolio.json    portfolio items
images/                add real photos here
```

## Roles and Members
| Role | Member |
|---|---|---|
| Project Manager | U Dilakson | 
| HTML Lead | T M R Kasuntha | 
| CSS Layout Designer | D G A N Kumarasinghe | 
| CSS Styling Designer | R M C T Bandara | 
| JS Functionality Developer | W V Anuradha | 
| JS Validation Developer | | 
| Content Manager | W H M A K Senevirathne | 
| Testing & Documentation Lead | T A K Malshan | 

## How to run
The gallery loads a JSON file, so opening the HTML directly may fail. Use a local server:
1. Open a terminal in this folder.
2. Run `python -m http.server 8000`
3. Visit http://localhost:8000

Or push to GitHub and enable Pages (Settings > Pages).

## Features
Hamburger menu, dark mode button (saved in the browser), category filters, project modal, form validation, responsive Flexbox/Grid layout.

## Content notes
Project images are drawn placeholders.
