An animation of a donut created using ASCII special character is rotated with change in colour every second or two.

So the simplified process looks like this:
- First we draw a circle on x-z plane which represents a donut section
- Rotating the section about central y-axis to create a donut shape
- Next we spin our donut round x and z axis to make it wobbly after which we can project our 3-D donut on 2-D screen
- The last thing we have to determine elimination by calculating surface normal

The whole animation is done using pygame's window