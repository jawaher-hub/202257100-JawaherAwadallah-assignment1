# AI Usage Report: Portfolio Development Collaboration 

## Tools: Claude and Gemini 

### Phase 1: Structure (Gemini)
* **Initial Prompt:** "Is this HTML layout good? any suggestions?"
* **AI Insight:** The AI identified a critical syntax error in the section IDs (using `id="#about"` instead of `id="about"`), which would have broken the navigation link functionality.
* **Resolution:** I manually corrected the ID attributes and verified that the `href` anchors correctly mapped to the section IDs.

### Phase 2: Responsive CSS & Layout (Claude)
* **Requirement:** Positioning the Dark Mode toggle while maintaining a centered navigation menu.
* **Technical Challenge:** The initial CSS caused the button to overlap with the links or move to a new line on smaller screens.
* **AI Solution:** The AI suggested setting `flex: 1` on the `ul` to maintain centered alignment for the links.
* **Result:** A responsive header that adapts to desktop and mobile viewports.

### Phase 3: JavaScript State Management
* **Requirement:** Implementing a Dark/Light mode toggle that affects all sections.
* **Problem:** The initial script only changed the `body` background, leaving white backgrounds on `section` and `input` elements.
* **AI Intervention:** I provided the AI with my current CSS classes and asked to "fix the colors of dark mode." The AI provided specific CSS selectors for `body.dark section` and `body.dark .project` to ensure a consistent dark theme UI.

## Learning Outcomes

*  I learned about viewports, smooth scrolling, changing view modes.

* **DOM Manipulation:** I learned how to use `classList.toggle()` to manipulate the Document without reloading the page.

* **Debugging Logic** 


