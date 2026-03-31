<h2 class="c-project-heading--task">Update the emoji link</h2>

### Step 1
Replace the temporary emoji link with the final link layout from the complete project.

This step matches the complete project: the link moves into a paragraph, and the URL changes to the short `rpf.io` address.

Go back to `index.html` and replace the old link section with this final version. Only the link section changes here; the quote underneath stays the same.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 53
line_highlights: 54-55
---
      </section>
      <section> <!-- Use a plain section for the final link layout -->
        <p class="xcenter"><a href="https://rpf.io/emoji" target="_blank">More emojis!</a></p> <!-- Move xcenter to the paragraph and use the final link -->
      </section>

      <!-- A block quote with a citation -->

      <section class="wrap">
        <blockquote>
--- /code ---

</div>

<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-top-5-emoji-list-step-8" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

### Step 2
**Test:** Click **Run** and check that the centred link still opens in a new tab and now uses the final page layout.
