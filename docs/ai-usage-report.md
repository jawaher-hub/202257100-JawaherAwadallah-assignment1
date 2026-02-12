# AI Usage Report: Portfolio Development Collaboration 

## Tools: Claude and Gemini 
## 2. Prompt Engineering & Iterative Development
The development followed a specific sequence of technical prompts to ensure code quality and rubric compliance:

### Phase 1: Structure (Gemini)
* **Initial Prompt:** "Is this HTML layout good? any suggestions?"
* **AI Insight:** The AI identified a critical syntax error in the section IDs (using `id="#about"` instead of `id="about"`), which would have broken the navigation link functionality.
* **Resolution:** I manually corrected the ID attributes and verified that the `href` anchors correctly mapped to the section IDs.

### Phase 2: Responsive CSS & Layout (Claude)
* **Requirement:** Positioning the Dark Mode toggle while maintaining a centered navigation menu.
* **Technical Challenge:** The initial CSS caused the button to overlap with the links or move to a new line on smaller screens.
* **AI Solution:** The AI suggested setting `flex: 1` on the `ul` to maintain centered alignment for the links.
* **Result:** A polished, responsive header that adapts to desktop and mobile viewports.

### Phase 3: JavaScript State Management
* **Requirement:** Implementing a Dark/Light mode toggle that affects all sections.
* **Problem:** The initial script only changed the `body` background, leaving white backgrounds on `section` and `input` elements.
* **AI Intervention:** I provided the AI with my current CSS classes and asked to "fix the colors of dark mode." The AI provided specific CSS selectors for `body.dark section` and `body.dark .project` to ensure a consistent dark theme UI.

## 3. Learning Outcomes

* ** I learned what meta viewport

* **DOM Manipulation:** I learned how to use `classList.toggle()` to manipulate the Document Object Model without reloading the page.

* **Debugging Logic:** 


