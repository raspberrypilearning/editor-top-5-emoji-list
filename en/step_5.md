<h2 class="c-project-heading--task">Add a link and quote</h2>

--- task ---
Add the extra text content from the next project snapshot: a link and a quote.
--- /task ---

This imported code state adds both pieces of content together, so they stay in one step.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 46
line_highlights: 48-55
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
--- /code ---

</div>

--- task ---
**Test:** Click **Run** and check that the link appears under the list and the quote appears below it.
--- /task ---
