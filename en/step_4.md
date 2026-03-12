<h2 class="c-project-heading--task">Show the background</h2>

--- task ---
Add the background image and transparent main panel from the next checked-in project state.
--- /task ---

This step uses two code snippets because the imported snapshot changes both `index.html` and `style.css`, and you need both edits to see the result.

**Code snippet 1: Update the page structure.**

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 35
line_highlights: 35,37,45
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
--- /code ---

</div>

**Code snippet 2: Add the background and transparent style.**

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 44
line_highlights: 47,95-97
---
/* add a background image to body */

body {
  background-image: url('emojis.png'); /* Show the emoji image behind the page */
  /*background-repeat: repeat;*/ /* Make the image repeat */
  /*background-size: cover; */ /* Make the image cover the whole container */
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

/* Header and footer element styles */

header,
footer {
  text-align: center;
  width: 100%; /* Fill the full width of the window */
  margin: 0; /* Remove the default margin */
  min-height: 3rem;
  padding-top: 1rem;
  padding-bottom: 1rem;
}

/* Section styles */

section {
  padding: 1rem 2rem;
  margin: 1rem auto;
}

/* Border styles */

.border-bottom {
  border-bottom: 20px solid var(--detail); /* Add a solid */
}

.border-top {
  border-top: 10px solid var(--detail2); /* Add a solid line above the footer */
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

--- task ---
**Test:** Click **Run** and check that the emoji background shows around the page edges and the main panel looks slightly transparent.
--- /task ---
