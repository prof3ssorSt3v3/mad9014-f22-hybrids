# Object Exercises

Create a single JavaScript file to complete all of these exercises. Add comments above each section to indicate the question number. The [MDN website](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object) should be your first reference for doing these exercises.

Eg:

```js
//exercise 1

//exercise 2
```

## Exercises

1. Create a function that accepts an Object and a String as arguments. The function then needs to check if the Object has a property with a name that matches the String argument. Use `hasOwnProperty()` to check for existence. If it does then use `delete` to remove the property.
2. Copy the following code snippet and convert all the dot notation into square bracket syntax.

```js
const obj = {
  a: 'first letter',
  b: 123,
  c: true,
  d: [
    { id: 11, name: 'emilia' },
    { id: 22, name: 'tessa' },
    { id: 33, name: 'naomi' },
  ],
  e: {
    age: 17,
    email: 'bob@home.org',
  },
};
//convert the lines below here
console.log(obj.a);
console.log(obj.d[1].name);
console.log(obj.e.age);
```

3. Start by copying this namespace example:

```js
const APP = {
  first: function (){
    console.log('first');
  },
  second: () => {
    console.log('second');
  },
  third(){
    console.log('third');
  }
}
```

Below the last line, add a call to the function inside the namespace called `first`. Then inside the `first` function call the `second` and inside the `second` call the `third`.
So, in your terminal you should see:

```bash
node main.js
first
second
third
```

4. Using either `String.prototype.` **OR** `Array.prototype.` add a new method to all String or Array objects in your script. The new method should be called `first`. The String version should return the first letter in the String. The Array version should return the first item in the Array. Here is a video that will help you understand how to do this - [https://www.youtube.com/watch?v=2jpAEz-hUKY](https://www.youtube.com/watch?v=2jpAEz-hUKY).

## Submission

Copy and paste the contents of your whole JavaScript File into the text box in the Object Hybrid Assignment in BS LMS.
