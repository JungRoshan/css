<div style="background-color: #f5f5f5; padding: 20px; border-radius: 8px; border: 1px solid #ddd; font-family: Arial, sans-serif;">

# CSS Animations Playground 

Explored CSS animations, focusing on keyframe animations and animation properties through practical implementation.

## What I Practiced

### Animation Implementation
- Created a pink box (400px × 80px) with color animation
- Defined `@keyframes` for both color and font-size animations
- Applied animation using individual properties:
  - `animation-name: coloranimate`
  - `animation-duration: 2s`
  - `animation-timing-function: ease-in`
  - `animation-delay: 0`
  - `animation-iteration-count: 8`
  - `animation-direction: alternate`
- Experimented with animation shorthand property

### Keyframe Definitions
- **Color Animation**: 
  - Smooth transition from green to blue
  - Alternate direction for continuous effect
- **Font Animation** (defined but not applied):
  - Extreme size change from 20px to 6000px
  - Demonstrates transform potential

## Key Observations

1. **Timing Control**: 
   - `ease-in` creates smooth acceleration
   - 2s duration provides visible transition
   - 8 iterations with alternate direction creates ping-pong effect

2. **Performance**:
   - Color animations are GPU-accelerated
   - Minimal repaint operations during transition

3. **Shorthand Advantage**:
   - Compact syntax: `animation: name duration timing-function delay iteration-count direction`


