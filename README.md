# Troublesome Dimensions

## Project Description  
*Troublesome Dimensions* is an interactive **card-battle web app** built with HTML, CSS, and vanilla JavaScript.  
Players collect fantasy-themed cards, then enter a battle arena where they can fight against a randomly chosen AI opponent.  

The site includes:  
- A dynamic combat system with HP bars, accuracy, and turn-based attacks.  
- A store where players can spend coins (saved in `localStorage`) to unlock new cards.  
- A rotating **“Breaking News”** feed that adds lore and atmosphere.  
- A responsive design that works across desktop, tablet, and mobile.  

---

## Project Vision  

I wanted to create something **interactive and playful**, rather than a typical shop or portfolio site.  
Since I’ve always enjoyed **Dungeons & Dragons** and fantasy games, I designed *Troublesome Dimensions* as a browser-based **battle arena**, where cards represent different heroes and creatures, each with unique stats and abilities.  

The goal was to combine a fun fantasy theme with real coding challenges: multi-view navigation, battle logic, local storage, and UI animations.  
Adding background lore and rotating “multiverse news” makes it feel more alive than just a demo of buttons and menus.  

---

## Features
- Portal Battle Button — animated, hover-expanding call-to-action.  
- Card Selection — choose from cards you own to fight the AI.  
- Battle Arena — random background images, HP bars, attack choices, win/lose logic.  
- Store — buy packs of new cards using in-game coins.  
- LocalStorage — saves coins and owned packs between visits.  
- Breaking News Ticker — rotates through six multiverse-themed headlines.  
- Responsive Design — stable layout across PC, tablet, and mobile.  

---

## Screenshots

### Home Page
(docs/screenshots/home.png)

### Card Choice
(docs/screenshots/card-choice.png)

### Battle Arena
(docs/screenshots/battle.png)

### Store / Pack Page
(docs/screenshots/store.png)


---

## Future Ideas  
- Add multiplayer battles so players can duel each other in real time.  
- Introduce a card trading / winning system — earn new cards by defeating opponents.  
- Expand the deck with more heroes, monsters, and abilities.  
- Create richer battle animations (attack effects, sounds, hit feedback).  
- Flesh out the story/lore of the multiverse to immerse players even further.  

---

## What I Learned  
- How to build a multi-view SPA using only HTML, CSS, and vanilla JS.  
- Handling game state and persisting it with `localStorage`.  
- Using CSS Grid and clamp() for responsive design.  
- Implementing object-fit and aspect ratios to control images cleanly.  
- Debugging image/file path issues (case sensitivity, spaces, cache).  
- Designing for both functionality and fantasy theme/lore.  

---

## Challenges & Struggles  

I found working with HTML and CSS straightforward, as I’m comfortable with structuring layouts and styling pages.  
However, when it came to JavaScript, I sometimes struggled with the logic behind certain features.  

A specific example was the HP bar system in battles. I attempted several different approaches, but couldn’t quite get the logic right for updating the bar dynamically during combat. After multiple failed attempts and research, I decided to ask **ChatGPT** for insight into what I was doing wrong. This helped me not only fix the HP bar but also understand *why* my earlier approaches weren’t working.  

This experience showed me that while I can usually figure things out with persistence, I also know when to reach out for help or use external resources. It reinforced that problem-solving often involves iteration, debugging, and learning from mistakes.

---

## Known Issues  
- Filenames & case sensitivity: Some arena backgrounds may fail to load if filenames don’t match exactly across systems. Gameplay is unaffected.  
- Card image cropping: Different artwork aspect ratios are cropped with `object-fit: cover`. This may trim edges slightly.  
- Login page is demo-only: No backend is connected.  
- LocalStorage reset: Clearing browser data resets coins and owned packs.  

---

## Attributions  

All external images are sourced from **Pixabay** (https://pixabay.com/), which offers free use even for commercial purposes.  
No attribution is legally required, but I am including credits for academic integrity.  

- Backgrounds / Arenas:  
  - Misty Forest — by [TODO: author username] — Pixabay  
  - Volcanic Landscape — by [TODO: author username] — Pixabay  
  - Mystic Mountains — by [TODO: author username] — Pixabay  
  - Castle — by [TODO: author username] — Pixabay  
  - Waterfalls — by [TODO: author username] — Pixabay  
  - City Wall — by [TODO: author username] — Pixabay  

- Textures:  
  - Parchment background — by [TODO: author username] — Pixabay  

- Card Artwork:  
  - Dark Elf — by [TODO: author username] — Pixabay  
  - Fire Dragon — by [TODO: author username] — Pixabay  
  - Lightning Drake — by [TODO: author username] — Pixabay  
  - Orc — by [TODO: author username] — Pixabay  
  - Troll — by [TODO: author username] — Pixabay  
  - Wood Elf — by [TODO: author username] — Pixabay  
  - Paladin — by [TODO: author username] — Pixabay  

**Help & Resources**  
- General research: Google, StackOverflow, college forums  
- ChatGPT: Assisted with HP bar logic, CSS refactoring, and fixing battle arena paths  

---

## How to Run  

- Option A: double-click `Troublesome Dimensions.html` to open locally.  
- Option B: run a static server for smoother asset handling:  
  ```bash
  npx serve .
  # or
  python -m http.server 8080

