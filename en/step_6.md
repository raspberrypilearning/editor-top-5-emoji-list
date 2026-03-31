<h2 class="c-project-heading--task">Make the header bounce</h2>

### Step 1
Replace the mixed header effects with bouncing emojis to match the complete project.

The complete version uses the same animation class on all five emojis.

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
    <span class="bigfont bounceme">🤣</span> <!-- Change the first emoji to bounce -->
    <span class="bigfont bounceme">😇</span> <!-- Change the second emoji to bounce -->
    <span class="bigfont bounceme">😭</span> <!-- Change the third emoji to bounce -->
    <span class="bigfont bounceme">🤩</span> <!-- Keep the fourth emoji bouncing -->
    <span class="bigfont bounceme">😘</span> <!-- Change the fifth emoji to bounce -->
  </header>
--- /code ---

</div>

<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-top-5-emoji-list-step-7" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

### Step 2
**Test:** Click **Run** and check that all five header emojis bounce when the page loads.
