You can use the `flex-order`to reorder elements when a window is resized (important for mobile) rather than taking them out of the DOM and putting them back in.

Remember: by default the `order` of all flex items is <b>0</b>. So if you want to set something as the first in a list on mobile, you can select every other flex item and set them to a high order:

    .wrapper > * { /* every immediate child of wrapper */
        order: 9999;
    }