# An Experimental Megamenu for Elementor using ONLY Jquery and CSS and standard Elementor

## NOTE: This isn't working perfectly just yet. See notes below.

How it works:
Build your Megamenu content directly below your main navigation menu. Place your content inside a section and then use the provided script.html inside your footer in an HTML block. 

Requirements:
1. Elementor
2. A navigation menu (native Elementor widget) added into your page/section/header
3. Ability to add html to your footer 

How to use:
1. Build your content rich megamenu right below the navigation menu (usually your header theme file)
2. Drop the provided script inside your footer in an html block
3. Edit the script to reflect your unique css classes (use code inspector in chrome)
4. Ensure that your section containing the megamenu (the dropdown) has a CSS property of display absolute

Lines below that you need to edit for your own needs (in the HTML file I provided in this repo):

Line 8, 17, 20, 22 - the custom class ID of the section you build inside Elementor
Line 16 - the class id of the menu item from your main menu

## What's still not working:

The opacity change works as expected but I can't figure out how to keep the opacity at 1.0 when the user is hovered over the megamenu that I built in Elementor. You can see what I mean in the gif below
