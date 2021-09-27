Based on https://www.joshwcomeau.com/animation/3d-button/

Steps:

- Create simple button
- The button has a 3D volume as a dark shadow underneath
- On click, the button is pushed down
- On focus, the button outline has an offset
- The focus halo is only displayed on keyboard focus, not on click
- On hover, button raises a bit
- Hover and push effects are animated and have a duration
- Browser is aware that button will be animated
- On interaction, button animation is quick, but "return to equilibrium animations" are slower
- On mouseup the button has a spring-like animation
- Button has animated shadow visible only when not clicked
- The shadow is blurred
- Button corners are a bit darker, simulating that less light hits them
- On hover, the button color is a bit lighter
- On mobile, there's no color flash on tap
- Button text is not selectable