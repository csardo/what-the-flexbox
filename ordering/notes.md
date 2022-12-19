<h2>flex:1;<h2>

This will take all of the width that you'll have and evenly distribute amongst each other.

<h2>Order</h2>

By default, the order of everything that is not set is <b>0</b>. So when you go ahead and set anything greater than 0 (like `order: 1;`), then it will put the flex item on the end.

Order is super helpful for responsive design, for example when you have a mobile site that totally changes the order/appearance  of things.

You can also use negatives to put things in the front.

PROBLEM: The in-browser selector will highlight things out of order because it's based on the html not the css manipulation.