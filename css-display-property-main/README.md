# css-display-property
# CSS Display Property & Block/Inline Switching – Day 9

Today, I explored how the **display property** in CSS allows us to switch elements between block and inline behaviors, and how that affects layout, sizing, and styling.

## 🔧 What I Practiced

- **Changed Block Elements to Inline:**  
  Used `display: inline;` on `<h2>` headers (normally block-level) to make them flow inline.
- **Changed Inline Elements to Block:**  
  Applied `display: block;` to `<span>` elements (normally inline) and styled them with width, height, margin, padding, and borders.
- **Styled Multiple Divs Side-by-Side:**  
  Created three `<div>` elements and used `display: inline-block;` to arrange them horizontally while allowing block-level styling.

## 📄 HTML & CSS Highlights

### First HTML & CSS File:
- Two `<h2>` elements set to `display: inline` with a pink background.
- Multiple `<span id="inline">` elements set to `display: block`, given width, height, padding, margin, and a border.
- Demonstrated how inline elements become block-level and accept box-model properties when their display is changed.

### Second HTML & CSS File:
- Three `<div>` elements:
  - `height: 200px; width: 200px;`
  - `background-color: greenyellow;`
  - `border: 2px solid black;`
  - `margin: 20px;`
  - `display: inline-block;` (so they appear side-by-side)

## 🧠 Key Takeaways

- The **display property** is powerful for changing how elements behave in the document flow.
- Block elements can be made inline, and inline elements can be made block, unlocking new layout possibilities.
- `inline-block` combines the best of both worlds: elements flow inline but accept block-level box model properties.

---
