## Add your content

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step, you will fill in your layout with content to create the mood that you want. 
</div>
<div>
![alt=""](images/step-four.PNG){:width="300px"}
</div>
</div>

\--- task ---

![alt=""](images/text-examples.png){:width="300px"}

Add any **text** that you want to appear on your mood board.

**Choose:** Your text could be any combination of:

- Short words or phrases that fit with your topic
- Nonsense placeholder text ('lorem ipsum') to give an idea of what the text would look like
- An inspirational quote

Don't spend too much time on the text details. A mood board just sets the mood for your project.

[[[add-placeholder-text]]]

[[[full-width-quote]]]

\--- /task ---

\--- task ---

![Examples of images and emoji in a strip.](images/image-emoji-strip.png)

**Choose:** Add images and/or emojis to make your webpage look interesting.

The starter project includes lots of images that you could use on your mood board.

[[[rpfeditor-image-library]]]

[[[huge-emoji]]]

There are lots of different emojis to choose from.

[[[choose-an-emoji]]]

**Tip:** It is fine to use the same image or emoji multiple times on your webpage to quickly fill your page.

\--- /task ---

\--- task ---

**Debug:**

## --- collapse ---

## title: My content has different heights and it looks odd

When you add content that has different heights, the boxes around them will be different heights.

![alt=""](images/different-heights.png)

You can change this by adding in the `tile` class:

## --- code ---

language: HTML
filename: index.html
line_numbers: false

---

<div class="tile">
--- /code ---

`tile` sets a specific height for each of the elements that have this class. To adjust the height, change it in the `style.css` file.

## --- code ---

language: CSS
filename: style.css
line_numbers: false

---

.tile {
height: 9.4rem;
}
\--- /code ---

Add the `tile` class to make every element with that class the same height.

![alt=""](images/same-height.png)

\--- /collapse ---

\--- /task ---

\--- task ---

**Test:** Have a look at your webpage. Make sure you are happy with the content on your page.

[[[image-not-displayed]]]

\--- /task ---
