# New-Hamburger-Menu

This is a simple, customizable hamburger menu for websites. It features a modern design and smooth animation. The menu is fully responsive and works on all devices.

Demo
You can see a live demo of the hamburger menu here.

Getting Started
To use the hamburger menu on your own website, follow these steps:

Download the CSS file and JavaScript file and add them to your project.

Add the following HTML code to your website where you want the hamburger menu to appear:

php
Copy code
<div class="hamburger-menu">
  <div class="bar"></div>
  <div class="bar"></div>
  <div class="bar"></div>
</div>
Initialize the hamburger menu by calling the initHamburgerMenu() function in your JavaScript code:
php
Copy code
<script src="path/to/hamburger.js"></script>
<script>
  initHamburgerMenu();
</script>
By default, the hamburger menu will toggle a full-screen overlay with links when clicked. You can customize the menu by modifying the CSS and JavaScript code.

Customization
Colors
To change the color of the hamburger menu, simply modify the background-color property in the .hamburger-menu CSS class.

To change the color of the bars in the hamburger menu, modify the background-color property in the .bar CSS class.

Size
To change the size of the hamburger menu, modify the font-size property in the .hamburger-menu CSS class.

To change the size of the bars in the hamburger menu, modify the height and width properties in the .bar CSS class.

Animation
To change the animation speed of the hamburger menu, modify the transition-duration property in the .bar CSS class.

Overlay
To change the appearance of the overlay that appears when the hamburger menu is clicked, modify the .overlay CSS class.
