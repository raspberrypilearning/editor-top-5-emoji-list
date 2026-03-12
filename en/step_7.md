<h2 class="c-project-heading--task">Animate the header</h2>

--- task ---
Add bouncing emojis to the header to make the top of your page more eye-catching.
--- /task ---

The `.bounceme` class is already included in `animation.css`, so you can reuse it on each emoji in the header.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 34-38
---
  <header class="secondary border-bottom">
    <h1>Top 5 Emojis!</h1>
    <span class="bigfont bounceme">🤣</span> <!-- Add a bouncing emoji to the header -->
    <span class="bigfont bounceme">😇</span> <!-- Add another bouncing emoji -->
    <span class="bigfont bounceme">😭</span> <!-- Add another bouncing emoji -->
    <span class="bigfont bounceme">🤩</span> <!-- Add another bouncing emoji -->
    <span class="bigfont bounceme">😘</span> <!-- Add another bouncing emoji -->
  </header>
--- /code ---

</div>

--- task ---
**Test:** Click **Run** and check that all five header emojis bounce when the page loads.
--- /task ---
