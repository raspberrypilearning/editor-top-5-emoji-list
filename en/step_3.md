<h2 class="c-project-heading--task">Add a trophy</h2>

--- task ---
Place a large trophy emoji next to your list so the rankings stand out.
--- /task ---

The `wrap`, `wide`, and `narrow` classes help the list and trophy share the space on larger screens.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 35
line_highlights: 36-37,44
---
    <main>
      <section class="wrap"> <!-- Let the list and trophy sit in one row -->
        <ol class="wide"> <!-- Give the list more room than the trophy -->
          <li>🤣 – Rolling on the floor laughing.</li>
          <li>👍👍🏻👍🏼👍🏽👍🏾👍🏿 – Thumbs up.</li>
          <li>😭 – Loudly crying face.</li>
          <li>🙏🙏🏻🙏🏽🙏🏽🙏🏾🙏🏿 – Folded hands.</li>
          <li>😘 – Face blowing a kiss.</li>
        </ol>
        <p class="narrow hugefont">🏆</p> <!-- Add a large trophy emoji -->
      </section>
--- /code ---

</div>

--- task ---
**Test:** Click **Run** and check that the trophy appears beside the list when there is enough room.
--- /task ---
