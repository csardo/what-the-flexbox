`flex` property. At what proportion should I scale myself up or down if I mave extra/less space?

The whole point of flexbox is that it won't break your layout if you have too much or too little space.

The width of your flex items by default is `auto`.

The default `flex:` property value is `0`, meaning, "don't do anything special like growing or shrinking, just stay at your initial size. 

    .box {
        flex:1; // everyone is equal
    }

    .box2 {
        flex:2; //box 2 has double the amount of everything else
    }

`flex` properties can also be decimal points. It's all proportions.