# HTML Structure for Interactive Boxes

This HTML document creates a simple interactive interface where clicking on a box reveals a hidden number.

- **Meta Tags**: Ensure proper character encoding, viewport settings, and compatibility with IE.
- **External Resources**: Links to a CSS stylesheet and a JavaScript file.
- **Content**: 
  - A main heading prompts user interaction.
  - A container holds six boxes, each with `data-number` and `data-state` attributes to manage their state and content dynamically.

# CSS Styling for Interactive Boxes

This CSS code provides styling for a webpage with interactive boxes, ensuring a consistent and visually appealing design.

- **Universal Selector**: Applies `box-sizing: border-box` to all elements for consistent sizing.
- **Body Styling**: Uses a sans-serif font and sets a light yellow background.
- **Heading Styling**: Centers the text, adds top margin, letter spacing, and sets a dark blue color.
- **Container Styling**: Sets the width to 80% of the viewport and centers it with auto margins.
- **Box Styling**: Floats the boxes, sets dimensions, margins, background color, border-radius, text alignment, and other visual properties.
- **Responsive Design**: Adjusts the box width for screens smaller than 740px.

# JavaScript for Interactive Box Click Event

This JavaScript code enables interactive functionality for boxes within a container, allowing users to reveal or hide numbers on click.

- **Container Selection**: Selects the container element that holds the boxes.
- **Event Listener**: Adds a click event listener to the container.
- **Event Handling**: 
  - Checks if the clicked element is a box.
  - Toggles the box state between hidden and visible.
  - Displays the number when the box is visible and hides it when the box is hidden.

* We have learned `getAttribute()` and `setAttribute()`. What other methods can you use to access an element's attributes?
In addition to getAttribute() and setAttribute(), there are several other methods hasAttribute(name): Checks if an element has a specific attribute.
removeAttribute(name): Removes an attribute from an element.
attributes property: Provides a live collection of all attributes of an element.
Direct property access: Access standard attributes directly (e.g., element.id, element.className).
dataset property: Access custom data attributes (data-*).

