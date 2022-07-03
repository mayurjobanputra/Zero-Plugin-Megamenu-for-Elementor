# A 100% FREE Megamenu for Elementor using ONLY Jquery and CSS and standard Elementor sections and blocks

<a target="blank" href="https://www.youtube.com/watch?v=sLyoaLSXPz4"><img src="100%25%20FREE.png"></a>

---------------------

| ![sample](chrome_ygWkjM7s1O.gif) |
|-|

**About this repo:**

Build a megamenu with Elementor natively using some Javascript and CSS. 

**How it works:**

Javascript intercepts the mouseover/hover events and sets the opacity of an elementor section to 1.0. 

**How to install it (overview):**

Build your Megamenu content directly below your main navigation menu as a native Elementor section. Give this section a custom class ID and then use the provided script.html (don't forget to change the class ids in this file) inside your footer in an HTML block so that the submenu shows (opacity becomes 1.0) when the mouse is over the main menu item. 

**Detailed Instructions:**

1. Directly below your main menu in your header, build your submenu in a new section and give this section a unique class name. Use whatever Elementor blocks you like inside (I use a few inner sections). I haven't tested this with multiple sections, so if you want to create a comlex layout, stick with inner sections inside a single section vs multiple sections stacked. 
2. Drop the provided script inside your footer in an html block. Get the script here: https://github.com/mayurjobanputra/Zero-Plugin-Megamenu-for-Elementor/blob/main/script.html
3. Edit the script to reflect your unique css classes using the guideline below
- wherever you see **.gethelpmenu** in the script file change to the custom class ID assigned to the section you built inside Elementor
- wherever you see **.menu-item-37** change to the class id of the menu item from your main menu

**Watch the Youtube video >>>>** https://www.youtube.com/watch?v=sLyoaLSXPz4

<a target="blank" href="https://www.youtube.com/watch?v=sLyoaLSXPz4"><img src="100%25%20FREE.png" height="200"></a>

**Requirements:**

1. Elementor (free or pro) installed and activated. If you use Elementor free, you will need to install a plugin that lets you build headers via Elementor. I'm using pro in this example.
2. A navigation menu widget (native Elementor widget) added into your header and displaying your main menu
3. A method to add html to your footer (I use a native footer section that display site-wide via Elementor Theme builder)
4. Basic understanding of CSS and how to DevTools (chrome) to find the unique class id of the main nav menu

If you need more help, email me hello @ mayur dot ca

## Outstanding Issues ##

- The mouseover/hover event for the menu item doesn't work as expected. The main nav menu item still shows as a hover intent, even when the mouse isn't over it. Not sure how to fix this. Workaround: the user has to move the mouse into the megamenu and then out of it to hide the submenu
