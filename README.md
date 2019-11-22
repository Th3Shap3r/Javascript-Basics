JavaScript

### String Interpolation -  

```javascript
const myPet = 'armadillo';
console.log(`I own a pet ${myPet}.`);
// Output: I own a pet armadillo.
```
---


### Template Literals - 

```javascript
// STRING CONCATENATION
console.log('Hi, I\'m ' + p.name + '! Call me "' + p.nn + '".');
```

```javascript
// TEMPLATE LITERALS
console.log(`Hi, I'm ${p.name}! Call me "${p.nn}".`);
```

---



### Conditional Statement - 

- **if keyword** - 

```javascript
let sale = false;
if (sale) {
  console.log("Time to buy!");
}
// Prints "Time to buy!"
```
---




- **If...Else Statements** - 

```javascript
if (false) {
  console.log('The code in this block will not run.');
} else {
  console.log('But the code in this block will!');
}
// Prints "But the code in this block will!" 
```




- **Comparison Operators** -

```javascript
let hungerLevel = 10;
if (hungerLevel > 7) {
  console.log('Time to eat!');
} else {
  console.log('We can eat later!');
}
```

---



### Logical Operators

- **&& (and operator) :**

  When using the && operator, both conditions must evaluate to true for the entire condition to evaluate to true and execute. Otherwise, if either condition is false, the && condition will evaluate to false and the else block will execute. 

```javascript
if (stopLight === 'green' && pedestrians === 0) {
  console.log('Go!');
} else {
  console.log('Stop');
}
```


- **- || (or) operator:**

   When using the || operator, only one of the conditions must evaluate to true for the overall statement to evaluate to true. In the code example above, if either day === 'Saturday' or day === 'Sunday' evaluates to true the if‘s condition will evaluate to true and its code block will execute. If the first condition in an || statement evaluates to true, the second condition won’t even be checked. Only if day === 'Saturday' evaluates to false will day === 'Sunday' be evaluated. The code in the else statement above will execute only if both comparisons evaluate to false.    

```javascript
    if (day === 'Saturday' || day === 'Sunday') {
  console.log('Enjoy the weekend!');
} else {
  console.log('Do some work.');
}
```


   - **! (not) operator:**

     Essentially, the ! operator will either take a true value and pass back false, or it will take a false value and pass back true.

```javascript
let excited = true;
console.log(!excited); // Prints false

let sleepy = false;
console.log(!sleepy); // Prints true
```
