# The Grand Pour

![Game Preview](./assets/banner.png)

A browser-based coffee shop simulation game demonstrating interactive UI design, real-time state management, and user-driven workflows.

Live Demo: https://grand-pour.vercel.app/
Repository: https://github.com/rawattanush/GRAND-POUR

---

## Overview

The Grand Pour is a simulation game where the user operates a virtual coffee shop. The gameplay involves preparing beverages, serving customers, managing inventory, and progressing through a day-based system.

The project was initially developed using a rapid prototyping approach and later refactored into separate files to improve structure and maintainability.

---

## Key Features

* Interactive brewing system with drag-and-drop mechanics
* Multi-step beverage preparation (espresso, latte, cappuccino, etc.)
* Dynamic customer system with varying patience and behavior
* Inventory and resource management
* Equipment unlocking and progression system
* Reputation-based progression
* Real-time UI updates using DOM manipulation
* Audio integration using Tone.js for ambient and interaction feedback
* Persistent game state using browser localStorage

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

```id="m4rk8p"
GRAND-POUR/
│── index.html
│── styles.css
│── script.js
│── assets/
│   └── banner.png
```

The project was originally implemented as a single-file application and later modularized into separate files for improved organization.

---

## Architecture Overview

The application follows a centralized, state-driven design:

* A core game object manages application state (money, inventory, customers, progression)
* Game logic handles brewing, crafting, and progression systems
* UI updates are performed through direct DOM manipulation and event-driven interactions

This approach enables real-time updates while maintaining consistency between state and interface.

---

## Persistence

Game progress is stored using browser localStorage and is automatically restored on reload.
No backend or external database is required.

---

## Core Concepts Demonstrated

* State management in vanilla JavaScript
* Event-driven programming
* Complex DOM manipulation and UI synchronization
* Asynchronous behavior and timers
* Client-side persistence

---

## Notes

The project was developed using a rapid prototyping approach and later refactored for better structure. Some components can be further modularized to improve scalability and maintainability.

---
