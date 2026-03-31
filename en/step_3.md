<h2 class="c-project-heading--task">Show the background</h2>

### Step 1
Add the background image and transparent main panel from the next checked-in project state.

This step uses two code snippets because the imported snapshot changes both `index.html` and `style.css`, and you need both edits to see the result.

**Code snippet 1: Go back to `index.html` and update the page structure.**

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 34
line_highlights: 34,36,45
---
  <main class="transparent"> <!-- Make the main panel use the transparent style -->
    <section class="wrap">
      <div class="wide"> <!-- Wrap the list in a wide container -->
        <ol>
          <li>🤣 – Rolling on the floor laughing.</li>
          <li>👍👍🏻👍🏼👍🏽👍🏾👍🏿 – Thumbs up.</li>
          <li>😭 – Loudly crying face.</li>
          <li>🙏🙏🏻🙏🏽🙏🏽🙏🏾🙏🏿 – Folded hands.</li>
          <li>😘 – Face blowing a kiss.</li>
        </ol>
      </div>
      <p class="narrow hugefont spinme">🏆</p>
    </section>
  </main>
--- /code ---

</div>

**Code snippet 2: Then open `style.css` and add the background and transparent style.**

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 44
line_highlights: 47,66-67
---
/* add a background image to body */

body {
  background-image: url('emojis.png'); /* Show the emoji image behind the page */
  /*background-repeat: repeat;*/ /* Make the image repeat */
  /*background-size: cover;*/ /* Make the image cover the whole container */
}

/* The main content of the page between the header and footer */
main {
  background: var(--primary); /* Colour the background */
  color: var(--onprimary); /* Colour the text */
  margin: 0 auto; /* Center if the browser is really wide */
  min-width: 25rem; /* Don't let the content get too narrow */
  max-width: 70rem; /* Don't let the content get too wide */
  padding: 0;
  padding-top: 0.5rem; /* Padding at the top */
  margin-bottom: 1em; /* Gap before the footer */
}

/* Add a transparent effect */

.transparent {
  opacity: 0.95; /* Let the background show through a little */
}
--- /code ---

</div>

<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-top-5-emoji-list-step-4" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

### Step 2
**Test:** Click **Run** and check that the emoji background shows around the page edges and the main panel looks slightly transparent.
