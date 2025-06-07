<div style="background-color: #f5f5f5; padding: 20px; border-radius: 8px; border: 1px solid #ddd; font-family: Arial, sans-serif;">

# CSS Layer Magic -using z-index

 Figured out how to control which elements appear on top when they overlap - like digital stacking cards!

## What I Built

I created two colorful boxes that overlap each other:
- A cool aqua box (using class `.A`)
- A warm salmon box (using class `.B`)


1. **The Default Behavior**:
   Normally, whatever comes *last* in the HTML sits on top (like the salmon box would naturally cover the aqua one)

2. **How I Changed the Order**:
   - Gave both boxes `position: relative` (this is like telling them "get ready to be layered")
   - Made the aqua box jump to the front with `z-index: 1` (like saying "you go first!")
   - Moved the salmon box up slightly with `bottom: 50px` so they'd overlap

3. **The Golden Rule**:
   `z-index` only works if you've set a position (relative, absolute, or fixed) - this tripped me up at first!


