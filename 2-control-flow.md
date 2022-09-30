# Control Flow Exercises

Create a single JavaScript file to complete all five of these exercises. Add comments above each section to indicate the question number. The [MDN website](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference#control_flow) should be your first reference for doing these exercises. You can use other resources too, like Steve's YouTube channel.

Eg:

```js
//exercise 1

//exercise 2
```

## Exercises

1. Convert the following nested `if...else` statements into a compound `if...else if...else` statement using `&&`. The new version should output the same three messages. Copy the commented part to start. The finished version should have this structure.

```js
if (a > 5) {
  if (b > 5) {
    console.log('both a and b are greater than 5');
  } else {
    console.log('one bigger. one smaller.');
  }
} else {
  if (b > 5) {
    console.log('one bigger. one smaller.');
  } else {
    console.log('both a and b are less than or equal to 5');
  }
}

//if( ){
//both a and b are greater than 5
//}else if( ){
//both a and b are less than or equal to 5
//}else{
//one bigger. one smaller.
//}
```

2. Convert the following code into a single line with a `ternary` statement.

```js
let isTony;
let name = 'Bob';
if (name == 'Tony') {
  isTony = true;
} else {
  isTony = false;
}
```

3. Write a multiline comment with the list of all the possible `falsey` values in JavaScript.
4. Write a `for loop` that will `console.log` each of these values `1, 4, 7, 10, 13, 16, 19`. It should not output any numbers other than the ones listed. Do not use an Array to accomplish this. The output values should be only the value of your counter variable.
5. Write a `for loop` that will `console.log` only the numbers from 25 to 5 in descending order. Eg: `25, 24, 23, 22, 21,...7, 6, 5`. Do not use an Array to accomplish this. The output values should be only the value of your counter variable.

## Submission

Copy and paste the contents of your whole JavaScript File into the text box in the Control-Flow Hybrid Assignment in BS LMS.
