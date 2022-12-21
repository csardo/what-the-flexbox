<b>justify-content</b> is where content is aligned on the main axis (default left to right).
Options:
 1. `flex-start` (default)
 2. `flex-end` (pack all to end)
 3. `space-between` (items are evenly distributed in the line)
 4. `space-around` (Note that visually the spaces aren’t equal, since all the items have equal space on both sides, meaning start and end have 1x space, but space between is 2x space, one for each flex item)
 5. `center` 

<b>align-items</b> defines content on the cross axis. Remember that it takes the vertical center of the container, not the viewport, so you need to have container class have `height: 100vh` in order to vertically align.
 1. `center`
 2. `stretch`
 3. `flex-start` (default)
 4. `flex-end` (pack all to end)
 5. `baseline` (make sure the bottom of the text is all aligned properly when they are different sizes)

 For `align-content` you need to have some sort of wrap or it doesn't take effect. We are only concerned with the cross axis here.

<b>align-self</b> can override the rest of `align-items`, helpful if you want to just stretch one item, or put just one item at the start or end.