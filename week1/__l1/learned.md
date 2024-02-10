Here's what i've picked up from this code:

-   Difference between Var and Let
-   Difference between the assignment opperator (=)
-   The basics in If and Else statements

while making this simple code ive managed to learn the difference between Var and Let. I was already familiar with Const, Var and Let in Javascript and i have managed to pick up that Var and Let in Swift arent that much appart from how its used in Javascript.

With ```var```, you can create variables whose value can be changed after they're assigned.

in my code i can use ```var``` to create a variable. in this case called ```y```
i gave ```y``` the value of ```100```. but because i use ```var``` i can always change the value of ```y```.

With ```let```, you can create constants whose value cannot be changed after they're assigned. This means the value is set once and cannot be changed.

in my code i can use ```let``` to create a variable. in this case called ```x```
i gave ```x``` the value of ```10```. but because i use ```let``` i can never change the value of ```x```

The ```=``` operator is used to assign a value to a variable or a constant.
The ```==``` operator is used to compare two values to check if they are equal.

```
let x = 10
var  y = 100

y = x

if x == y {
    print("the value is the same")
}
else{
    print("the value is different")
}
```

if i where to change ```var y``` into ```let y``` i would get an error because i cant change y into x anymore using ```x = y```. but if i where to keep both variables as a ```let``` i could always turn ```y = x``` into ```y == x``` to get the terminal to say ```The value is different```.
that is because in this case i asked the operator to check if y and x are equal. wich they are not.