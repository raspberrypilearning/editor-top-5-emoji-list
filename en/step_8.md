<h2 class="c-project-heading--task">Update the emoji link</h2>

--- task ---
Replace the temporary emoji link with the final link layout from the complete project.
--- /task ---

The complete page wraps the link in a paragraph and uses the short `rpf.io` address.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 54
line_highlights: 55-56
---
      </section>
      <section> <!-- Use a plain section for the final link layout -->
        <p class="xcenter"><a href="https://rpf.io/emoji" target="_blank">More emojis!</a></p> <!-- Link to the finished emoji page -->
      </section>
--- /code ---

</div>

<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-top-5-emoji-list-step-8" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

--- task ---
**Test:** Click **Run** and check that the centred link still opens in a new tab and now uses the final page layout.
--- /task ---
