## Return Negative

```js
const  makeNegative = (num) => {
    return -Math.abs(num);
  }
  
  console.log(makeNegative(5)); 
  console.log(makeNegative(-5)); 
  console.log(makeNegative(0));  
  
```

## Sum of Positive

```js

const numbers = [1,2,3,4,5,6,7,8,9,10,-11,-12,-13,-14,-15,100];
let sum = 0;

numbers.forEach((num) => { if(num > 0){ sum += num; }});

console.log(sum); 
```

## Function 2

```js
const sqReturn = (sqr) => {sqr = Math.sqrt(sqr) 
    console.log(sqr)};

sqReturn(25);

```

## Sum Arrays

```js
function sumOfNumbers(arr) {
    if (arr.length === 0) {
      return 0;
    }
    const sum = arr.reduce((acc, curr) => acc + curr, 0);
    return sum;
  }

  console.log(sumOfNumbers([1, 2, 3, 4])); 
  console.log(sumOfNumbers([-1, -2, -3, -4])); 
  console.log(sumOfNumbers([1.5, 2.5]));
  console.log(sumOfNumbers([])); 
```

## Reversed Strings

```js
const reverseString = (string) => {
    console.log(string.split("").reverse().join(""));
  }

 reverseString("some string of text here");
```
