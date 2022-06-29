## Return Negative

```js
function makeNegative(num) {
  return -Math.abs(num)
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let positiveSum = 0
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      positiveSum += arr[i]
    }
  }
  return positiveSum
}
```

## Function 2

```js
function square(num) {
  return num * num
}
```

## Sum Arrays

```js
function sum(numbers) {
  'use strict'
  let sumNumbers = 0
  for (let i = 0; i < numbers.length; i++) {
    sumNumbers += numbers[i]
  }
  return sumNumbers
}
```

## Reversed Strings

```js
function solution(str) {
  let reverseString = ''
  for (let i = str.length - 1; i >= 0; i--) {
    reverseString += str[i]
  }
  return reverseString
}
```
