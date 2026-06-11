# Moon-Museum-2
# Moon Museum
A multi-page web project built with HTML and CSS.

## Overview
This project is a themed character showcase inspired by Sailor Moon. It includes a home page, a gallery of character cards, and individual detail pages for each Sailor Guardian. The goal was to demonstrate multi-page site structure, responsive layout, shared styling, and organized file management.

The site uses a soft magical-girl aesthetic with glowing accents, blurred glass panels, and pastel color themes to match the Sailor Moon universe.

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

## Design Decisions

### Visual Theme
A soft pastel palette with glowing borders and blurred glass panels was chosen to match the magical aesthetic of Sailor Moon. The UI uses rounded corners, soft shadows, and hover animations to create a dreamy, polished feel.

### Responsive Layout
- The gallery uses a CSS Grid that automatically adjusts to screen size.
- Navigation includes a mobile hamburger menu (nav.css).
- Images scale smoothly on smaller screens.

### Reusable Components
- Shared navigation across all pages
- Shared typography and layout in style.css
- Gallery-specific grid and card styles in gallery.css
- Mobile nav overrides in nav.css

### Organized Assets
All character images were renamed to clean, web-friendly filenames and stored in the required images/ folder.

## Challenges
- Ensuring consistent styling across multiple pages
- Creating a responsive grid that adapts to different screen sizes
- Managing image filenames and paths so they load correctly
- Adding a mobile navigation system that works on every page

## What I Learned
- How to structure a multi-page website
- How to use CSS Grid and Flexbox for layout
- How to organize assets into folders for clean project structure
- How to create reusable components like nav bars and card layouts
- How to design with a consistent visual theme

## Future Improvements
- Add animations to player pages
- Add a dark mode toggle
- Add more characters or villains
- Add a search or filter system for the gallery
