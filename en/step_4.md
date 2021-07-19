## Give your template some style

Now that you have the shape of a template, add colour and style to it with CSS.

![A page with a title and a menu. The background is blue, with a green content box, a white heading, and a green dotted border around a menu with black text.]('images/step_4_preveiw.png')

![A page with a title and a menu. The background is gold, with a white content box, a purple heading, and a menu with a yellow background and black text.]('images/step_4_preveiw_2.png')

--- task ---

Use some CSS rules in your `style.css` file to add colour to your page, and maybe change the size and font of the text you're using. Remember that you can apply rules to all copies of a tag on your page, or you can use classes to target only specific elements.

**Choose:** You can find a list of colours to choose from [here](https://www.w3schools.com/colors/colors_names.asp){:target="_blank"}.

--- save ---

--- collapse ---
---
title: Assigning CSS rules to a HTML tag
---

You can assign a CSS rule to apply to all copies of a tag (like `p`) as shown below.

```html
    <p>
        Here is the text of a paragraph.
    </p>
```

```css
p{
    /* CSS rules go here */
}
``` 

**Tip:** Assigning a rule to the `body` tag will make it apply to everything on the page unless another, more specific, rule applies. This is how you set the default text styles for your site, or the background colour of your pages.

--- /collapse ---

--- collapse ---
---
title: Assigning CSS rules with classes
---

You can use a class on a HTML element to connect it with a set of CSS rules, like this:

```html
    <p class="my_class">
        Here is the text of a paragraph.
    </p>
```

```css
.my_class{
    /* CSS rules go here */
}
``` 

--- /collapse ---

--- collapse ---
---
title: Setting text colour with CSS
---

You can set the background colour of an element with the `color` property:

```css
.my_class{
    color: white;
}
```

--- /collapse ---
--- collapse ---
---
title: Setting background colour with CSS
---

You can set the background colour of an element with the `background-color` property:

```css
.my_class{
    background-color: green;
}
```

--- /collapse ---

--- collapse ---
---
title: Setting fonts with CSS
---

You can use the `font-family` property to make your text look different. The font families are:

  + <span style="font-family: cursive">cursive</span>
  + <span style="font-family: fantasy">fantasy</span>
  + <span style="font-family: monospace">monospace</span>
  + <span style="font-family: sans-serif">sans-serif</span>
  + <span style="font-family: serif">serif</span>

You can set font families like this:

```css
.my_class{
    font-family: cursive;
}
```

--- /collapse ---

--- collapse ---
---
title: Setting text size with CSS
---

You can use the `font-size` property to make your text look bigger, or smaller. The default size, which the user chooses and on which the others are based, is `medium`. The font sizes are:

  + <span style="font-size: xx-small">xx-small</span>
  + <span style="font-size: x-small">x-small</span>
  + <span style="font-size: small">small</span>
  + <span style="font-size: medium">medium</span>
  + <span style="font-size: large">large</span>
  + <span style="font-size: x-large">x-large</span>
  + <span style="font-size: xx-large">xx-large</span>
  + <span style="font-size: xxx-large">xxx-large</span>

You can set font sizes like this:

```css
.my_class{
    font-size: large;
}
```

--- /collapse ---

--- collapse ---
---
title: Aligning text with CSS
---

The `text-align` property can be used to control whether text is positioned to the `left`, `right`, or `center` of its parent element.

```css
.my_class{
    text-align: center;
}
```

--- /collapse ---

--- /task ---
