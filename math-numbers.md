# Math and Number Exercises

Create a single JavaScript file to complete all five of these exercises. Add comments above each section to indicate the question number. The [MDN website](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number) should be your first reference for doing these exercises.

Eg:

```js
//exercise 1

//exercise 2
```

## Exercises

1. Create a function, with one input argument, that uses `console.log` to output the input number formatted to 2 decimal places, using `.toFixed()`.
2. Create a function that accepts three arguments, each with a default value of zero. The function then uses `Number.isNaN()` to test that each argument provided was actually a number. If all three are numbers then the function returns `true`. Otherwise it returns `false`.
3. Create a function that accepts three arguments, each with a default value of zero. The function then uses `Math.min()` or `Math.max()` to determine which is the largest of the three. Then return the largest number.
4. Create a function that creates a random **INTEGER** between the minimum and maximum values provided as arguments to the function. The random integer needs to be inclusive, which means that if 2 and 5 were provided as the min and max then the random number could be 2, 3, 4, or 5. It includes the min and max values as possibilities. Use `Math.random()` wrapped in `Math.floor()` to generate the random integer. Remember that an integer has no decimal value. The general formula / algorithm for calculating a random number is `(random value * (max - min)) + min`.
5. Create a function that will create a random integer between 0 and 1000 and then convert the number to base 16 using the `toString()` method. The function should use `console.log` to output the new base-16 string.

## Submission

Copy and paste the contents of your whole JavaScript File into the text box in the Number Hybrid Assignment in BS LMS.
