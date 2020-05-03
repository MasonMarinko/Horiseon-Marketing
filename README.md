# Code Refactor Starter Code
Website URL: https://masonmarinko.github.io/Horiseon-Marketing/
github URL (For Repositories) https://github.com/MasonMarinko/Horiseon-Marketing

Changes:
Added Title for tab, used to say Website now says "Horiseon Marketing Solutions" 

Seperated HTML into sections for easier readability and future changes.
    -Added markups to each section of website, this will allow for readability as well as seperate each section so its not just one chunk of code.

All images, including hero <div> have alt/title attributes for accessibility.
    - All images in webpage have a brief description and alt elements. Also added Title element to Hero section since this was in CSS alt would not work.

Condensed CSS to avoid duplicates and condensed.
    - 2 sections of code (vertical and horizontal banners) used the exact same parameters with 3 different class names. Made it into one class name and updated the class on each HTML element.


Put CSS in order that made sense and was semantic with the HTML.
    - CSS now is in order with the website, so when viewing HTML and CSS side by side they go in same order. Also put elements that were either universal to whole HTML or specific to just 1 part (Span in this case) were at the top, and not in the middle of the sections.

Changed some elements to Section/Article for easier readibility and better SEO.
    -Too many <div> sections that weren't properly divided. This will allow for better SEO and organization.


Fixed Broken Links
    -One of the 3 links in header didn't link, fixed the ID so that it worked properly.

Cleaned up HTML code that was unlinked or not closed.