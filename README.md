# Project Oblivion Website

## Overview
This website is a fan-made informational site dedicated to *The Elder Scrolls IV: Oblivion*. It provides an overview of the game’s world, story, gameplay systems, and key features. The site is designed to be visually immersive, using a dark fantasy colour palette and a consistent layout across multiple pages.

The project focuses on responsive design, accessibility, and the use of Bootstrap alongside custom CSS to create a cohesive user experience across desktop and mobile devices.



## Website Structure

The website consists of four main pages:

### Home Page (`index.html`)
- Introduces *Oblivion* and the world of Cyrodiil
- Highlights key aspects of the game
- Provides navigation to all other sections



### Gameplay Page (`gameplay.html`)
- Explains core gameplay systems including:
  - Real-time combat system
  - Character progression and leveling
  - Magic and alchemy systems
- Includes interactive cards with modal popups for deeper information
- Features a “Playstyles” section showing different ways to play:
  - Warrior
  - Mage
  - Assassin



### Story Page (`story.html`)
- Covers the main storyline of *Oblivion*
- Uses an accordion layout to present key story events:
  - Prison Escape
  - Oblivion Crisis
  - Finding Martin Septim
  - Final Sacrifice
- Includes key story moments displayed as cards with modals:
  - Oblivion Gates
  - Battle of Kvatch
  - Final Sacrifice
- Also includes additional lore-related side quest references such as guilds and Daedric quests



### World & Features Page (`world&features.html`)
- Displays an overview of the world of Cyrodiil
- Includes an interactive world map section
- Highlights major world features such as:
  - Living cities
  - Oblivion gates
  - Factions and guilds
  - Exploration systems
  - Daedric influence
  - Dynamic world systems



## Design Approach

### Visual Style
- Dark fantasy theme inspired by *Oblivion*
- Colour palette:
  - Deep browns and mahogany backgrounds
  - Orange highlights for emphasis
  - Warm accent colours for interactive elements

### Layout
- Built using Bootstrap 5 grid system
- Responsive design for different screen sizes
- Card-based UI for content sections
- Modals used for expanded information

### Components Used
- Navbar (responsive with collapsible menu)
- Cards with hover effects
- Modal popups for detailed content
- Accordion for story progression
- Responsive image containers
- Styled tables (used in gameplay section)



## Technologies Used

- HTML5
- CSS3 (custom styling with variables)
- Bootstrap 5.3.3
- JavaScript (Bootstrap bundle for modals, navbar, accordion)



## Features

- Fully responsive layout
- Consistent navigation across all pages
- Interactive UI elements (modals, accordion)
- Styled tables and cards matching theme
- Hover animations and transitions
- Accessible structure with alt text and ARIA labels



## Responsive Design

The website is designed to work across:
- Desktop (primary design target)
- Tablet
- Mobile devices

Key responsive features:
- Collapsible navigation bar
- Flexible Bootstrap grid layout
- Scalable images using `img-fluid`
- Media queries for map and card adjustments



## File Structure
/project-oblivion
│
├── index.html
├── gameplay.html
├── story.html
├── world&features.html
├── style.css
│
├── /images
│ ├── hero1.jpg
│ ├── hero2.jpg
│ ├── hero3.jpg
│ ├── hero4.jpg
│ ├── combat.jpg
│ ├── magic.jpg
│ ├── progression.jpg
│ ├── map.jpg
│ ├── oblivion-gate.jpg
│ ├── kvatch.jpg
│ ├── final-battle.jpg
│
└── README.md



## Notes

- Bootstrap is used for layout consistency and responsiveness
- Custom CSS is used to enforce a consistent dark fantasy aesthetic
- Modals and interactive elements improve user engagement without requiring page reloads



## Author
Jake Lynch
Fan-made educational project based on *The Elder Scrolls IV: Oblivion*