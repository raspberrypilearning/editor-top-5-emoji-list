<h2 class="c-project-heading--task">Animate the header</h2>

### Step 1
Add the different header animations from the next checked-in project state.

Each emoji uses a different class so the top of the page feels more energetic.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 30
line_highlights: 32-36
---
  <header class="secondary border-bottom">
    <h1>Top 5 Emojis!</h1>
    <span class="bigfont rollmeleft">🤣</span> <!-- Roll the first emoji in from the left -->
    <span class="bigfont spinme">😇</span> <!-- Spin the second emoji -->
    <span class="bigfont scaleme">😭</span> <!-- Make the third emoji grow and shrink -->
    <span class="bigfont bounceme">🤩</span> <!-- Make the fourth emoji bounce -->
    <span class="bigfont rollmeright">😘</span> <!-- Roll the fifth emoji in from the right -->
  </header>
--- /code ---

</div>

<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-top-5-emoji-list-step-6" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

### Step 2
**Test:** Click **Run** and check that the header emojis use different animations when the page loads.
