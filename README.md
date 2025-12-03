# Playing Cards Display

## Overview
This project displays a set of playing cards using **HTML** and **CSS**. Each card shows its **rank** (A, 2–5) and **suit** (♠, ♣, ♥, ♦) in a structured layout with left, middle, and right sections.

## Features
- Five sample cards:
  - Ace of Spades
  - 2 of Clubs
  - 3 of Hearts
  - 4 of Clubs
  - 5 of Diamonds
- **Left section:** Rank and suit
- **Middle section:** Main symbols in card layout
- **Right section:** Flipped symbols for symmetry
- **Color differentiation:** Red suits (♥, ♦) and black suits (♠, ♣)

## How to Use
1. Clone or download this repository.
2. Open `index.html` in a web browser.
3. The cards will appear in a horizontal layout.

## HTML Structure
```html
<main id="playing-cards">
  <div class="card">
    <div class="left">
      <div>A</div>
      <div>♠</div>
    </div>
    <div class="middle">
      <div>♠</div>
    </div>
    <div class="right">
      <div class="flip">♠</div>
      <div class="flip">A</div>
    </div>
  </div>
  <!-- Additional cards follow the same structure -->
</main>
