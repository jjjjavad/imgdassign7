# imgdassign7
For this performance, my aesthetic intent was to explore the tension between rigid order and  fluid movement.
I wanted to create a neon, retro-futuristic grid that slowly warps and breathes as if it were a living topological map.
I kept the visual palette constrained to shifting cyan and magenta hues to emphasize the structural changes of the grid itself.
I utilized the fract() function to instantly generate an infinite grid from normalized pixel coordinates. I use the examples in chapter 3 of the book of shaders.
To achieve the breathing effect, I manipulated the UV space using overlapping `sin()` and `cos()` functions driven by the time uniform before the grid calculation occurs.
This effectively bends the space the grid inhabits rather than moving the lines individually. Finally, I used smoothstep() instead of hard conditional logic to draw the lines.

