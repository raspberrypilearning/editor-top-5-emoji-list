<h2 class="c-project-heading--task">Add a link and quote</h2>

### Step 1
Add the extra text content from the next project snapshot: a link and a quote.

This imported code state adds both pieces of content together, so they stay in one step.

Go back to `index.html` and add the new link section followed by the quote section.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 45
line_highlights: 47-53
---
    <p class="narrow hugefont spinme">🏆</p>
  </section>
  <section class="xcenter"> <!-- Add a centred section for the link -->
    <a href="https://unicode.org/emoji/charts/full-emoji-list.html" target="_blank">More emojis!</a> <!-- Link to another emoji page -->
  </section>
  <section class="wrap"> <!-- Add a section for the quote -->
    <blockquote>
      <p>"Oceans of emotion can be transmitted through an emoji sequence"</p> <!-- Show the quote text -->
      <cite>- Jenna Wortham.</cite> <!-- Credit the quote -->
    </blockquote>
  </section>
  </main>
--- /code ---

</div>

<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-top-5-emoji-list-step-5" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

### Step 2
**Test:** Click **Run** and check that the link appears under the list and the quote appears below it.
