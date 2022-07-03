# A Megamenu for Elementor using ONLY Jquery and CSS and standard Elementor sections and blocks

| ![sample](chrome_ygWkjM7s1O.gif) |
|-|

About this repo:
Build your Megamenu content directly below your main navigation menu as a native Elementor section. Place your content inside a new section with a custom class ID and then use the provided script.html inside your footer in an HTML block so that it triggers when the page is rendered. 

Requirements:
1. Elementor (free or pro) installed and activated
2. A navigation menu widget (native Elementor widget) added into your page/section/header and displaying your main menu
3. A method to add html to your footer (I use a native footer section that display site-wide via Elementor Theme builder)
4. Basic understanding of CSS and how to DevTools (chrome) to find the unique class id of the main nav menu

How to use:
1. Directly below your main menu, build your submenu in a new section and give it a unique class id (unique per dropdown)
2. Drop the provided script inside your footer in an html block
3. Edit the provided script to reflect your unique css classes
- wherever you see **.gethelpmenu** change to the custom class ID assigned to the section you built inside Elementor
- wherever you see **.menu-item-37** change to the class id of the menu item from your main menu

If you need more help, email me hello @ mayur dot ca

## Outstanding Issues ##

- The mouseover/hover event for the menu item doesn't work as expected. The main nav menu item still shows as a hover intent, even when the mouse isn't over it. Not sure how to fix this. Workaround: the user has to move the mouse into the megamenu and then out of it to hide the submenu
