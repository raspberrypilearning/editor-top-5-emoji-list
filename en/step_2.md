<h2 class="c-project-heading--task">Create the list</h2>

--- task ---
Add a page title and an ordered list of your top five emojis.
--- /task ---

Ordered lists are useful for rankings because the browser numbers each item for you.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 31
line_highlights: 32,35-44
---
  <header class="secondary border-bottom">
    <h1>Top 5 Emojis!</h1> <!-- Add a heading for your page -->
  </header>
  <main>
    <section> <!-- Add a section to hold the ranking -->
      <ol> <!-- Use an ordered list for the top five -->
        <li>🤣 – Rolling on the floor laughing.</li> <!-- Add the first emoji -->
        <li>👍👍🏻👍🏼👍🏽👍🏾👍🏿 – Thumbs up.</li>
        <li>😭 – Loudly crying face.</li>
        <li>🙏🙏🏻🙏🏽🙏🏽🙏🏾🙏🏿 – Folded hands.</li>
        <li>😘 – Face blowing a kiss.</li>
      </ol>
    </section>
  </main>
--- /code ---

</div>

<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-top-5-emoji-list-step-2" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

--- task ---
**Test:** Click **Run** and check that your page shows a numbered list underneath the heading.
--- /task ---
