## Design your mood board

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you will choose a topic for your mood board and choose a matching colour palette and fonts. You will check that your colour palette has good contrast so that it is accessible. 
</div>
<div>
Image, gif or video showing what they will achieve by the end of the step. ![](images/image.png){:width="300px"}
</div>
</div>

--- task ---

What is the topic of your mood board? 

+ Party: for a specific occasion or theme
+ Artwork: Book cover, poster, flyer, comic book
+ Logo or product design: 
+ Decorate a space: Classroom, makerspace, cafe
+ Fashion design: glasses frames, sari, bag
+ Inspired by nature: Terrarium, outside space
+ Inspired by animals: Fish tank, tropical rainforest 
+ Character design or world building

Remember, you don't need to create a complete web page, you are just going to make a page that is visually appealing and sets a mood.

--- /task ---

--- task ---

Change the `<h1>` title of your mood board to match your topic, for example 'Summer party'.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Graphic designers, interior designers, industrial designers, photographers, user interface designers and other creative artists**</span> use mood boards to visually illustrate the style they wish to pursue. Amateur and professional designers alike may use them as an aid for more subjective purposes such as how they want to decorate their bedroom, or the vibe they want to convey through their fashion.
</p>

--- task ---

Open the [mood board starter project](https://trinket.io/library/trinkets/bb2ee12497){:target="_blank"}. 

--- /task ---

--- task ---

**Choose:** Set the colour palette for your mood board. You will need 5 colours `primary`, `secondary`, `tertiary`, `detail` and `detail2`.

You could:

[[[hex-colour-palettes]]]

--- collapse ---

---
title: Create your own custom colour palette
---

The starter project uses the `default.css` file to assign colours to the variables. The existing colours use a greyscale scheme. 

![The default colour palette showing 5 shades of grey.](images/greyscale.png)

**Choose** Change the colour codes in `default.css` to the colours you would like to use in your mood board. Your mood board colours will update as you update them.

**Tip:** You can use [coolors.co](https://coolors.co){:target="_blank"} to generate and customise colour palettes then update your colour codes in `deault.css`.

--- code ---
---
language: html
filename: default.css
line_numbers: true
line_number_start: 4
line_highlights: 5-14
---

:root {
  --primary: #bccad0;
  --onprimary:#4f4e4e;
  --secondary: #495054;
  --onsecondary:#ffffff;
  --tertiary:#747474;
  --ontertiary: #ffffff;
  --page:#ffffff;
  --onpage:#000000;
  --detail: #9ba8ae;
  --detail2: #000000;
}

--- /code ---

--- /collapse ---

Or, you could choose an image and then select a colour palette to match:

--- collapse ---

---
title: Choose an image
---

The starter file has a library of useful images.

Click on the 'View and Add images' icon: 

![An icon shaped like a piece of paper with top right corner folded over and a mountain scene on the paper.](images/view-add-images.png)

Scroll through the image library and make a note of the file name of an image you would like to use in your mood board: 

![The image library with beetle.jpg file shown.](images/image-gallery.png)

Add your image to the `<main></main>` in `index.html` so that it appears on your mood board webpage:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 35
---

    <!-- The main content for the web page goes between the main tags -->
    <main>
      Lorem ipsum dolor sit amet. 
      <img src="beetle.jpg">
       
    </main>

--- /collapse ---

Right click on the image on your webpage and select `Copy image address`:

![The output area in trinket with large beetle image. The rightclick menu has an option selected to 'Copy image address'.](images/copy-image-address.png)

In a new browser window, go to [coolors.co](https://coolors.co){:target="_blank"} and select the `Tools` menu then `Image picker`:

![The coolors.co website with tolls selected from the top right corner. The 'Image picker' tool is highlighted in the drop down menu.](images/image-picker-menu.png)

Click on the `Browse image` button: 

![The browse image button.](images/browse-image-button.png)

Click on `URL` then paste the copied image address into the `Image URL` box. Click `OK`:

![The Select image box with URL selected and the image address for the beetle image copied in.](images/select-image-box.png)

Sample palettes are created from your image. You can use the `picked palette` slider to select which colour scheme you want to use:

![The picked palette slider is a third of the way across. The image is shown with hotspots showing where the colours have been selected from.](images/generated-image-palettes.png)

When you are happy with the palette, click on the dropdown arrow of the `Export palette` button and select `Open in the generator`:

![The Export palette menu with the top item 'open in the generator' selected.](images/generate-palette-menu.png)

The final palette will be shown. The coded letters and numbers are the hex codes for your chosen colours. Update the variable values in your `default.css` file to use these new colours:

![Squares of colour with the hex codes written on them.](images/final-image-palette.png)


--- code ---
---
language: html
filename: default.css
line_numbers: true
line_number_start: 4
line_highlights: 5-14
---

:root {
  --primary: #08586B;
  --onprimary:#4f4e4e;
  --secondary: #E0DB54;
  --onsecondary:#ffffff;
  --tertiary:#AF5C08;
  --ontertiary: #ffffff;
  --page:#ffffff;
  --onpage:#000000;
  --detail: #AB7C1C;
  --detail2: #38640D;
}

--- /code ---

--- /task ---

--- task ---

[choose an image]
[get colours from an image]

--- /task ---

--- task ---

**Tip:** To make your mood board useable to people with disabilities and appealing to a wide audience you need to make sure it is accessible: 

[accessibility]

--- collapse ---

---
title: 
---



--- /collapse ---

--- /task ---

--- task ---

**Test:** Check that your web page is using your new colour palette. 

--- /task ---

--- task ---

**Choose:** Select fonts that work well to set the style of your mood board. 

[Choosing CSS fonts]
[Fonts from your palette file]
[Add Google fonts]

--- /task ---

--- task ---

**Test:** Check that your web page is using your new fonts. 

--- /task ---


