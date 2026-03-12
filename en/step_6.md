<h2 class="c-project-heading--task">Add a link and quote</h2>

--- task ---
Add a helpful link and a short quote to give your page more content.
--- /task ---

Links use the `<a>` tag, and quotes can be marked up with `<blockquote>` and `<cite>`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 53
line_highlights: 55-64
---
        <p class="narrow hugefont spinme">🏆</p>
      </section>
      <section> <!-- Add a section for the link -->
        <p class="xcenter"><a href="https://rpf.io/emoji" target="_blank">More emojis!</a></p> <!-- Link to another emoji page -->
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
**Test:** Click **Run** and check that the link is centred and the quote appears below it in a larger style.
--- /task ---
