## Layout your mood board

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you will design the overall layout of your mood board and add content sections with placeholder content. 
</div>
<div>
Image, gif or video showing what they will achieve by the end of the step. ![](images/image.png){:width="300px"}
</div>
</div>

--- task ---

Your mood board will have several sections of content using a combination of text, images or emoji. 

Think about the sections you want to add. You could sketch your layout on paper if you prefer. 

--- /task ---

--- task ---

Add at least three sections to your mood board. You can add more if you like. 

[Add a full width section with title and text]

--- collapse ---

---
title: Add a full width section with title and text
---

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<section>
    <h2>Section title</h2>
    <p>Section text.</p>
</section>

--- /code ---

--- /collapse ---

[Add side by side image and text]

--- collapse ---

---
title: Add side by side image and text
---

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<section class="wrap">
    <img src="placeholder.png" alt="Description of the image.">
    <div>
        <p>Add text here.</p>
    </div>
</section>

--- /code ---

You can swap the order of the `<img>` and `<div>` elements if you want the text to come first.

--- /collapse ---


[Add a wrapping section with regular width elements]


--- collapse ---

---
title: Add a wrapping section with regular width elements
---

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<section class="wrap">
    <div class="secondary">
        <p>Add text here.</p>
    </div>
    <img src="placeholder.png" alt="Description of the image.">
    <div class="tertiary">
        <p>Add text here.</p>
    </div>
</section>

--- /code ---

Add or remove `<div>` and `<img>` elements as needed. They will wrap if there is not enough space. 

Use the `primary`, `secondary` and `tertiary` styles to control the background and font colour for paragraphs of text.

--- /collapse ---

[Add wide text and a narrow image]

--- collapse ---

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<section class="wrap">
    <div class="wide">
        <p>Wide paragraph of text</p>
    </div>
    <img class="narrow" src="placeholder.png" alt="Description of the image.">
</section>

--- /code ---

--- /collapse ---

[Add a full width section with a quote]

--- collapse ---

---
title: Add a full width quote
---

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<section>
    <blockquote>
        <p>"Oceans of emotion can be transmitted through an emoji sequence"</p>
        <cite>- Jenna Wortham.</cite>
    </blockquote>
</section>

--- /code ---

--- /collapse ---

[]

--- collapse ---

---
title: 
---



--- /collapse ---

--- /task ---

--- task ---

**Test:** Check that you are happy with the layout of the page. Don't worry about the actual content or images yet. You will add those in the next step.

--- /task ---

