# Description

The page consists of three parts: navbar, banner and logos. The libraries used in the project is Bootstrap and jQuery.

The first part navbar is justified by flexbox and I use Bootstrap dropdown button to hold the navbar items when the viewport is less than 768px.

As for banner, I use Bootstrap carousel component to build the slider, but rewrite the carousel indicator style to place it vertically. When you click the indicator, the slide will go to the corresponding image. A small amount of jQuery is to control the slider time, etc. The slider will go to next slide every 6 seconds. The form in the banner is laid out by Bootstrap grid system.

The third part (four logos) is implemented with Bootstrap grid system as well. It will become two rows when the viewport is less than 768px.

I use media query in the end of CSS file to adjust the style with different viewport. I also leave some comments in the HTML and CSS file to show different parts or what I am doing here.
