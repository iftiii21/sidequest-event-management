# Sidequest — Event Management Website

A responsive event discovery and registration website for the K Explore Web Designing assignment.

## Design concept
Sidequest is styled as an independent city-culture guide / editorial event noticeboard rather than a standard event-booking template. It uses oversized editorial typography, issue numbers, field-note labels, warm paper tones, cobalt blue, orange and lime accents.

## Required features
- Responsive homepage and navigation
- Upcoming and featured event cards
- Event name, date, venue, image and description
- Individual event detail modal
- Search by title, category, venue or description
- Category filters: Technology, Music, Arts and Lifestyle
- Registration form for name, email, phone and selected event
- JavaScript validation and confirmation message
- Responsive desktop, tablet and mobile layouts

## Bonus features
- Dark/light theme preference saved in Local Storage
- Countdown timer for featured event
- Animated scrolling ticker
- Registration data saved in Local Storage
- Newsletter signup saved in Local Storage
- Keyboard support for event cards and Escape-to-close dialogs

## Files
- `index.html` — page structure
- `styles.css` — layout, visual design and responsive styles
- `script.js` — event data, filtering, validation, Local Storage and interactions

## Run locally
Extract the ZIP, open the `sidequest` folder in VS Code, then open `index.html` with Live Server. You can also open the HTML file directly in a browser.

## Customize events
Edit the `events` array at the top of `script.js`. Change the featured event date in `countdown()` if you change the featured event date in the page.

## Local Storage
- Registrations: `sidequestRegistrations`
- Newsletter signups: `sidequestSubscribers`
- Theme preference: `sidequestTheme`

This is a front-end demonstration. Registration records remain in the visitor's browser and are not sent to a central database. A production service would need a backend, database and secure email workflow.

## Deployment
**GitHub Pages:** Push these files to a public GitHub repository. In Settings → Pages, select Deploy from a branch, choose `main` and `/ (root)`, then save.

**Netlify:** Choose Add new site → Deploy manually and drag the extracted project folder into the deploy area.

**Vercel:** Import the GitHub repository, choose Other as the framework preset, leave the build command empty and deploy.

Images and fonts load from Unsplash and Google Fonts, so those assets require an internet connection.

**Assignment:** K Explore — Design and Develop a Responsive Event Management Website.
