SVG PATH COMMANDS:

1. Line commands - (L,H,V,Z);
   L is length, H is Horezontal line, V is vertical line and z is End line or close path command
2. Cubic bezier curves - (C,S);
   C is used for lower curve & S is used for upper curve
3. Quadratic bezier curves - (Q,T);
   T can't do anything without Q
4. Arcs (A);
   Example (A30,20 0 0 1)
   There : 30 is X axis and 20 is Y axis ...
   There are there parameters :
   0 is first parameter it's X-axis-rotation
   0 is second parameter it's large-arc-flag
   1 is third parameter it's sweep flag

---

In path d means draw
<path d="M20,40 L80,40" stroke="blue"></path>
There L80 is X axis & 40 Y axis

1. M arc cursor start point
2. L means Line draw the line
