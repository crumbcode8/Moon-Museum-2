# Moon-Museum-2
# Moon Museum
A multi-page web project built with HTML and CSS.

## Overview
The Moon Museum is a modern, interactive character gallery built with animated flip‑cards, dark‑mode styling, and expanded bios for each Guardian. I wanted it to feel clean, magical, and fun to explore, like a digital trading‑card collection with a sleek UI twist.

This project let me play with layout, animation, and theming while building something nostalgic and pretty. Every card flips to reveal stats, every page has its own vibe, and the whole site lives in a purple‑tinted dark mode that feels right at home in the Moon Kingdom. It’s simple, cute, and a great practice project for HTML, CSS, and building consistent design across multiple pages.

## Pages Included
- index.html — Home page with hero section and featured character previews
- gallery.html — Grid layout of all character cards with hover animations
- player-usagi.html — Detail page for Sailor Moon
- player-ami.html — Detail page for Sailor Mercury
- player-rei.html — Detail page for Sailor Mars
- player-makoto.html — Detail page for Sailor Jupiter
- player-minako.html — Detail page for Sailor Venus

Each player page includes:
- Character image
- Stats section
- Highlights/description
- Back-to-gallery navigation

## File Structure
project/
│
├── index.html
├── gallery.html
├── player-usagi.html
├── player-ami.html
├── player-rei.html
├── player-makoto.html
├── player-minako.html
│
├── css/
│   ├── style.css
│   ├── gallery.css
│   └── nav.css
│
└── images/
    ├── usagi-front.jpeg
    ├── usagi-back.jpeg
    ├── ami-front.jpeg
    ├── ami-back.jpeg
    ├── rei-front.jpeg
    ├── rei-back.jpeg
    ├── makoto-front.jpeg
    ├── makoto-back.jpeg
    ├── minako-front.jpg
    ├── minako-back.jpeg
    └── moon-kingdom.jpeg

-- Design Decisions
Visual Theme
I went full magical‑girl dark mode for this redesign — deep purples, soft gold highlights, and just enough glow to feel enchanted without overwhelming anything. The flip‑cards, glass panels, and sparkly accents make the whole site feel like a digital shrine to the Sailor Guardians.

--Responsive Layout
The gallery grid snaps into place like it has its own transformation sequence.

The hero image scales beautifully without losing that Moon Kingdom drama.

Cards and text resize smoothly so everything still looks cute on mobile.

--Reusable Components
One shared nav bar to rule them all

A unified dark‑mode theme living in style.css

Gallery‑specific grid magic in gallery.css

A sleek, glassy nav vibe handled in nav.css

--Organized Assets
All character images live in a tidy images/ folder with filenames that won’t make future‑me cry.

-- Challenges
Making the flip animations feel smooth and not like a cursed trading card

Getting gold text to stay readable on every back‑card image

Keeping the dark‑mode palette consistent across multiple pages

Balancing the hero section with the gallery so nothing felt too heavy

 --What I Learned
How to keep a whole multi‑page site visually consistent

How to mix Grid, Flexbox, and 3D transforms without breaking everything

How to organize assets and styles so the project stays clean

How to design with contrast, readability, and vibes in mind

--Future Improvements
Add sparkles or subtle animations because… why not

Add a light/dark mode toggle

Add more characters (outer senshi, villains, everyone gets a card)

Add search or filters so the gallery feels more like a real collection
