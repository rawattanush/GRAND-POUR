# The Grand Pour

A browser-based coffee shop simulation game focused on real-time interaction, dynamic UI, and state-driven gameplay.

Live Demo: https://grand-pour.vercel.app/

Repository: https://github.com/rawattanush/GRAND-POUR

---

## Overview

The Grand Pour is a simulation game where the player manages a coffee shop. The player prepares drinks, handles customer orders, manages inventory, and progresses through a day-based system.

The project was built using a rapid prototyping approach, prioritizing functionality and interaction over initial structure. It was later refactored into separate files for better maintainability.

---

## Features

* Interactive coffee brewing system
* Multi-step recipes (espresso, latte, cappuccino, etc.)
* Customer system with patience and behavior differences
* Inventory and resource management
* Equipment and upgrade system
* Reputation and progression mechanics
* Real-time UI updates using DOM manipulation
* Sound and ambient effects using Tone.js
* Save and load functionality using localStorage

---

## Tech Stack

* HTML
* CSS
* JavaScript (Vanilla)
* Tone.js (audio)
* Font Awesome (icons)
* Vercel (deployment)

---

## Project Structure

```
GRAND-POUR/
│── index.html
│── styles.css
│── script.js
```

The project was initially implemented in a single HTML file and later separated into individual files for better organization.

---

## Architecture (High Level)

The application is built around a central game object that manages:

* State (money, inventory, customers, progression)
* Game logic (brewing, crafting, upgrades)
* UI updates (DOM rendering and animations)

The UI is updated dynamically through event-driven interactions and direct DOM manipulation.

---

## Key Concepts

* State management in vanilla JavaScript
* Event-driven programming
* DOM manipulation at scale
* Game loop and timers
* Local storage for persistence
* Incremental system design

---

## Limitations

The project was developed using an experimental approach, so:

* Code structure is not fully modular
* Logic and UI are partially coupled
* Some sections are difficult to maintain or extend

---

## Future Improvements

* Refactor into modular architecture (separate logic, UI, data)
* Improve maintainability and readability
* Add more gameplay depth (new recipes, customer types)
* Optimize performance
* Possibly migrate to a framework or game engine

---
