Default behavior is `flex-direction: row`:
1->2->3->4->5

`flex-direction: column`:
1
|
2
|
3
|
4
|
5

The above two define the <b>main axis</b>.

You can also do 
 - `flex-direction: row-reverse`
 - `flex-direction: column-reverse`

Then with `flex-wrap: wrap` you define the <b>cross axis</b>. So in the case of the main axis goind right to left with default `flex-direction: row`, then the cross axis of `flex-wrap: wrap` is <b>top to bottom</b>.

But what happens when you update your cross axis to `flex-wrap: wrap-reverse`? Then your cross axis is <b>bottom to top</b>, so 1 starts on the bottom and 10 is at the top left (the left is because the main axis is unchanged). 

<h2>box-sizing: border-box</h2>

NOTE: Padding and border are part of box sizing border box while margin is not. So if you use marigin on this flexbox it will break.