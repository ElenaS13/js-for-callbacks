# js-for-callbacks
code for filter 
----filter in the above example is a so-called higher-order function. This is a fancy word for a function that accepts another function as an argument. In the above example, the function passed to filter will be called once with each item in the animals array as the argument. This passed function is sometimes referred to as the callback. If the callback returns true, the items makes the cut for the new array that filter is creating, which is what ends up in the oldDogs variable.
