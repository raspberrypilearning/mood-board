## Add style

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you can add style to your mood board including font sizes and styles, centering, borders, gradients, transparency or rounded corners. You don't need to add everything! Just add the features that you need to create the effect you want. 
</div>
<div>
![](images/image.png){:width="300px"}
</div>
</div>

--- task ---

Use the `primary`, `secondary` and `tertiary` classes to control the colours of each `<section>` or `<div>`.

**Tip:** You don't have to have text in every box, you can just create a solid block of colour. 

[[[web-primary-secondary]]]

--- /task ---

--- task ---

You can change the size, position and font weight and style of text on your mood board:

[[[web-large-text-tiles]]]

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

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<div class="rounded">
    <p>Add text here</p>
</div>

--- /code ---

**Tip:** You can adjust the `border-radius` of the `rounded` class in 'style.css'.

--- /collapse ---


--- collapse ---

---
title: Add a border
---

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<div class="bordered-box">
    <p>Add text here</p>
</div>

--- /code ---

**Tip:** You can adjust the `border` values for the `bordered-box` class in 'style.css'

--- /collapse ---

--- collapse ---

---
title: Add a gradient
---

The `gradient1` and `gradient2` styles provide different gradient effects. 

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<div class="gradient1">
    <p>Add text here</p>
</div>

--- /code ---

**Tip:** To change the colours and direction of the gradient, adjust the `background-image` values for the `gradient1` and `gradient2` class in 'style.css'.

--- /collapse ---

--- /collapse ---

--- collapse ---

---
title: Add transparency
---

Use the `transparent` class to make an element partially transparent so you can see the content behind it.

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<div class="transparent">
    <p>Add text here</p>
</div>

--- /code ---

**Tip:** Adjust the `opacity` value for the `transparent` class in 'style.css'. 0 is completely transparent and 1 is not at all transparent. 

--- /collapse ---

--- /task ---

--- task ---

**Test:** Check that you are happy with the way your mood board looks. Don't feel that you have to use lots of different effects, sometimes less is more! 

--- /task ---