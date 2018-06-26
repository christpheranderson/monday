## Data Types

What is the return value of each of the below code snippets? After coming up with each answer, test it out in the console.

```js
typeof( 15 );
// Include your answer below each line using a comment, like this.
// Then, include the actual output of the command entered, in this case, the output of typeof( 15 );

typeof( 5.5 ); "number"
typeof( NaN ); "number"
typeof( "hello" ); "string"
typeof( true ); "boolelan"
typeof( 1 != 2 );"boolean"

"hamburger" + "s";"hamburgers"
"hamburgers" - "s"; "NaN"
"1" + "3" ; "13"
"1" - "3" ; -2
"johnny" + 5; "johnny5"
"johnny" - 5 ; NaN
99 * "luftbaloons"; NaN
```

What's going on in the second half of the previous question? What "rules," if any, can we pull from those examples? Well when it comes to concatenating when your adding the values together (rather if they are numbers or strings)  your just putting them together. However, when you are concatenating number values using the minus sign it will return back a number but when your are concatenating just strings it will return a NaN which means not a number.