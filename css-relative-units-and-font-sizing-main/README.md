# css-relative-units-and-font-sizing
focused on understanding and applying CSS relative units like `%`, `em`, and `rem` to control element sizing and spacing in relation to parent elements and root font size.

## 🔧 What I Practiced

- Used **percentage (%)** units to size elements and margins relative to their parent containers.
- Applied **em units** for font size and padding, where `1em` equals the font size of the current element.
- Used **rem units** for font sizing relative to the root (`html`) font size.
- Explored how font sizes cascade and affect padding and layout.

## 📄 HTML & CSS Highlights

### First HTML & CSS File:
- `<h1>` with width set to `33.33%` of the body width.
- Nested `<div>` elements with fixed dimensions.
- Inner div’s `margin-left` set to `10%` relative to its parent’s width.

### Second HTML & CSS File:
- Outer container with fixed size and font size of `20px`.
- Inner div with `font-size: 3em` (3 times the parent’s font size).
- Padding on inner div set using `1em` (relative to its own font size).
- Styled a large button with `50px` font size, green border, rounded corners, and horizontal padding using `em`.

### Third HTML & CSS File:
- Used `rem` units for font sizing on nested `<div>` elements.
- Section element font size set to `15px`.
- All divs inside have font size `2rem` (twice the root font size), demonstrating how `rem` is independent of parent font sizes.

## 🧠 Key Takeaways

- `%` units are relative to the parent element’s dimensions, useful for responsive layouts.
- `em` units are relative to the font size of the current element, affecting padding, margins, and fonts.
- `rem` units are relative to the root font size, providing consistency across the page.
- Understanding these relative units helps create scalable and accessible designs.
