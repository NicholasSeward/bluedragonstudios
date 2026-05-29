# Blue Dragon Studios Website Plan

## Goal

Build a simple single-page website for a newly incorporated art nonprofit in Hot Springs, Arkansas. Keep it professional, artsy, sleek, and easy to revise.

## App Structure

Use one page: `index.html`.

Sections:

1. Home
2. About
3. Board
4. Donate
5. Contact

The navigation should scroll smoothly to each section instead of loading separate pages.

## Layout

### Header

- Black sticky header.
- Blue dragon SVG logo or placeholder mark on the left.
- Simple links on the right: About, Board, Donate, Contact.
- On mobile, collapse links into a small menu button.

### Home

- Black background with subtle blue glow.
- Large blue dragon SVG logo or placeholder.
- Main title: `Blue Dragon Studios`
- Tagline: `A nonprofit art studio in Hot Springs, Arkansas.`
- Buttons: `Donate` and `Contact Us`

### About

- One short mission statement.
- Mention that the organization is newly incorporated.
- Keep copy honest and early-stage.

Suggested copy:

`Blue Dragon Studios is a newly incorporated nonprofit dedicated to supporting art, creativity, and community in Hot Springs, Arkansas. We are building a space where local artists, families, and neighbors can connect through creative work.`

### Board

- Simple board member cards.
- For now, use name, title, and short placeholder bio.
- Example cards: President, Executive Director, Treasurer, Secretary, Board Member.

### Donate

- Short explanation of what donations will support.
- Button linking to donation platform when ready.
- If no donation platform exists yet, use a placeholder button.

Suggested copy:

`Donations will help us recoup the cost of incorporation and put us on our way to support creative projects, purchase supplies, and build our foundation in the community.`

### Contact

- Contact form or simple email link.
- Include service area: Hot Springs, AR.
- Direct donation/contact questions to the President or Executive Director.
- Add social links later.

## Style

- Background: black / near-black.
- Main accent: bright blue.
- Text: white and soft gray.
- Cards: dark charcoal with thin blue border.
- Buttons: blue with soft glow.
- SVG logo can use a subtle blue drop shadow or glow in the hero.
- Feel: clean, modern, slightly dramatic, not busy.

CSS colors:

```css
:root {
  --bg: #050505;
  --card: #111111;
  --blue: #007bff;
  --blue-bright: #00aeff;
  --text: #f5f7fa;
  --muted: #a7aab0;
}
```

Fonts:

- Headings: `Cinzel` or `Playfair Display`
- Body: `Inter` or `Montserrat`

## CSS Plan

Use `styles.css`.

Needed styles:

- Global reset.
- Sticky header.
- Full-height hero.
- Smooth section spacing.
- Reusable buttons.
- Simple board card grid.
- Donate callout box.
- Mobile responsive layout.

## JS Plan

Use `script.js`.

Needed JavaScript:

- Smooth scroll navigation.
- Mobile menu open/close.
- Fade-in sections as the user scrolls.
- Contact form placeholder alert until real form handling is added.

## File Plan

```text
index.html
styles.css
script.js
logo.svg
```

## First Build

Build only the single-page app with placeholder content. Do not add gallery, events, programs, blog, newsletter, or extra pages yet.
