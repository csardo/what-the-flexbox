What happens if you want to add two values for the same flex property?

Problem: We want to add `align-items: center` to center the text, but also have `align-items: stretch` so the links are all the same height.

Answer: Use nested flex box.

    /* our first flex item */
    .slider-nav li {
    flex: 2; /* as a flex item */
    text-align: center;
    display: flex; /* as a flex container */
    }

So the above element is both a flex items and containers. Very helpful if you want items to vertically stretch as well as be centered.