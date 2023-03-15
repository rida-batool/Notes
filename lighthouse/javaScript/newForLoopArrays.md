## Traditional for Loops

```
const amounts = [61.00, 52.25, 112.99, 5.00];

let total = 0;
for (let i = 0; i < amounts.length; i++) {
  total += amounts[i];
}
console.log('Order total is: ', total);
```

## Newer for..of Loops Are Simpler

```
let total = 0;
for (let amount of amounts) {
  total += amount;
}
console.log('Order total is: ', total);
```

Here the amount variable is automatically set to each item in the array (first 61.00, then 52.25 and so on).

# Conclusion

In summary, the for..of loop is ...

- A modern (newer) feature in JavaScript

- Simpler than the regular for loop

- But also less powerful than the regular for loop

- Only really useful for going through an entire array from beginning to end

- Not a solution to all our looping problems
