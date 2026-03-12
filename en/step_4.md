<h2 class="c-project-heading--task">Spin the trophy</h2>

--- task ---
Use the existing animation class to make the trophy spin when the page loads.
--- /task ---

The starter project already includes a `.spinme` class in `animation.css`, so you only need to apply it.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 35
line_highlights: 44
---
    <main>
      <section class="wrap">
        <ol class="wide">
          <li>🤣 – Rolling on the floor laughing.</li>
          <li>👍👍🏻👍🏼👍🏽👍🏾👍🏿 – Thumbs up.</li>
          <li>😭 – Loudly crying face.</li>
          <li>🙏🙏🏻🙏🏽🙏🏽🙏🏾🙏🏿 – Folded hands.</li>
          <li>😘 – Face blowing a kiss.</li>
        </ol>
        <p class="narrow hugefont spinme">🏆</p> <!-- Apply the spin animation to the trophy -->
      </section>
--- /code ---

</div>

--- task ---
**Test:** Click **Run** and check that the trophy rotates when the page starts.
--- /task ---
