# Technical Documentation

## 1. Project Structure
The project is organized simply to keep things clean. I have the main `index.html` file in the root, and the rest of the files are in folders:
* `css/style.css` - the styling and theme colors.
* `js/script.js` - logic for the theme change.
* `assests/images/` - Where I kept my projects screenshots (using the `assests` folder name).

## 2. Layout Logic (CSS)
For the layout, I used **Flexbox**  
* **Navigation:** I used `display: flex` and `justify-content: space-between` in the nav. This keeps the links on one side and the theme button on the other.
* **Responsive Projects:** In the `.project-list`, I used `flex-wrap: wrap`. This is how I made the site work on mobile without using media queries
* **Spacing:** I used `margin: 30px auto` and `max-width: 1000px` on sections so the content stays centered and doesn't look stretched out on big screens.



## 3. Smooth Scrolling
I added `scroll-behavior: smooth;` to the `html` selector. This makes the page slide nicely to the About or Projects section when you click the menu links, better than sudden jump.

## 4. Dark Mode Implementation
The dark mode toggle is the main JavaScript part of the site.
* **The Toggle:** The script listens for a click on the `theme-toggle` button. When clicked, it adds or removes a `.dark` class from the `body`.
* **The Colors:** In the CSS, I created specific rules for `body.dark`. For example, I changed the section backgrounds to a darker color (`#1e1e2e`) and adjusted the text colors so they are still easy to read.
* **Smooth Transition:** I added a `transition` to the body so the color swap doesn't look stiff.



## 5. Form & Images
* **Form:** I used a standard flex column layout for the form so the inputs stack. I also used the `required` attribute so users can't send empty messages.
* **Images:** I set `max-width: 100%` on images inside the project cards so they stay inside their boxes and don't break the layout on small screens.