## Add style

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you can add style to your mood board including font sizes and styles, centering, borders, gradients, transparency or rounded corners. You don't need to add everything! Just add the features that you need to create the effect you want. 
</div>
<div>
Image, gif or video showing what they will achieve by the end of the step. ![](images/image.png){:width="300px"}
</div>
</div>

--- task ---

Use the `primary`, `secondary` and `tertiary` classes to control the colours of each `<section>` or `<div>`.

**Tip:** You don't have to have text in every box, you can just create a solid block of colour. 

--- collapse ---

---
title: Primary, secondary and tertiary styles
---

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<section class="wrap">
    <div class="primary">
        <p>Colour one</p>
    </div>
    <div class="secondary">
        <p>Colour two</p>
    </div>
    <div class="tertiary">
        <p>Colour three</p>
    </div>
</section>

--- /code ---

--- /collapse ---

--- /task ---

--- task ---

You can change the size, position and font weight and style of text on your mood board:

--- collapse ---

---
title: Large text
---

You can use header tags `<h1>` and `<h2>` to create large text headings. 

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<div><h1>BEETLE</h1></div>

--- /code ---

--- /collapse ---

--- collapse ---

---
title: Start a new line
---

Sometimes you want text to start on a new line. You can use the `<br>` tag to do this. 

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<div class="tertiary">
    <h2>BEETLE<br>BEETLE<br>BEETLE</h2>
</div>

--- /code ---

Each 'BEETLE' will appear on a new line even if there is room on the previous line. 

--- /collapse ---

--- collapse ---

---
title: Centering text
---

Some items will automatically be centered because of the style for their element. 

You can use the `xcenter` and `ycenter` classes to center other elements horizontally and vertically. 

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<section class="xcenter ycenter">
    <h2>A title ...</h2>
    <p>... and a description.</p>
</section>

--- /code ---

--- /collapse ---

--- collapse ---

---
title: Bold and italic text
---

Use the `<strong>` and `<em>` tags to emphasise text. `<strong>` is used for important text which should be bold. `<em>` is used for emphasised text that should have an italic (slanted) font.

--- code ---
---
language: html
filename: index.html
line_numbers: false
---
<p>This is <strong>important</strong>.</p>
<p>This is <em>emphasised</em>.</p>
--- /code ---

--- /collapse ---

--- /task ---

--- task ---

You can add rounded corners, borders, gradients or transparency to style your `<section>` or `<div>` elements. 

--- collapse ---

---
title: Add rounded corners
---



--- /collapse ---


--- collapse ---

---
title: Add a border
---



--- /collapse ---

--- collapse ---

---
title: Add a gradient
---



--- /collapse ---

--- collapse ---

---
title: Add transparency
---



--- /collapse ---

--- /task ---

--- task ---



--- /task ---