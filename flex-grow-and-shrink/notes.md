    .box2 {
        flex:1 1 400px;
    }

The above actually has 3 properties:
 1. flex-grow
 2. flex-shrink
 3. flex-basis

So `flex: 1` is shorthand to set both `flex-shrink` and `flex-grow` to 1.

`flex-grow: 10` says that the element has 10x the amount of extra space to grow than the other element.

`flex-shrink` is how should we shrink the elements down when there is less than the ideal space for it.

`flex-basis` is the ideal/initial amount of space.