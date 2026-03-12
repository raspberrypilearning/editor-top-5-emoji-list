<h2 class="c-project-heading--task">Add a background</h2>

--- task ---
Show an emoji background and make the main panel slightly transparent so the image can show through.
--- /task ---

This step uses two code snippets because the style must be created in `style.css` and then applied in `index.html` before you can see the effect.

**Code snippet 1: Update the page styles.**

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

.transparent { /* Create a class for a see-through panel */
  opacity: 0.95; /* Let a little of the background show through */
}
--- /code ---

</div>

**Code snippet 2: Apply the transparent class to the main area.**

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 35
line_highlights: 35
---
    <main class="transparent"> <!-- Apply the transparent style to the main content -->
      <section class="wrap">
        <ol class="wide">
--- /code ---

</div>

--- task ---
**Test:** Click **Run** and check that the emoji image appears around the page edges and the main panel looks slightly see-through.
--- /task ---
