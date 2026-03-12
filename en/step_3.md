<h2 class="c-project-heading--task">Add a spinning trophy</h2>

--- task ---
Turn your list into a side-by-side layout and add a spinning trophy emoji.
--- /task ---

This step matches the next checked-in code state, where the layout classes and the `spinme` class are introduced together.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 35
line_highlights: 36-44
---
    <main>
      <section class="wrap"> <!-- Let the list and trophy sit side by side -->
        <ol class="wide"> <!-- Make the list wider than the trophy area -->
          <li>🤣 – Rolling on the floor laughing.</li>
          <li>👍👍🏻👍🏼👍🏽👍🏾👍🏿 – Thumbs up.</li>
          <li>😭 – Loudly crying face.</li>
          <li>🙏🙏🏻🙏🏽🙏🏽🙏🏾🙏🏿 – Folded hands.</li>
          <li>😘 – Face blowing a kiss.</li>
        </ol>
        <p class="narrow hugefont spinme">🏆</p> <!-- Add a large trophy and make it spin -->
      </section>
--- /code ---

</div>

<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-top-5-emoji-list-step-3" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

--- task ---
**Test:** Click **Run** and check that the trophy appears beside the list and spins when the page loads.
--- /task ---
