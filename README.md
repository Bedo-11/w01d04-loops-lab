# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
for(let i =0; i<=10;i++){
    console.log(i);
}
```

<br>

## Print every number from 10 to 0

```
for(let i =10; i>=0;i--){
    console.log(i);
}

```

<br>

## Print every number from 4 to -16

```
for(let i =4; i>=-16;i--){
    console.log(i);
}

```

<br>

## Print every fifth number from 8 to 41

```
for(let i =8; i<=41;i+=5){
    console.log(i);
}

```

<br>

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"



for(let number=1; number<=100;number++) {
  if(number % 3 ==0 && number % 5 ==0 ){
    console.log("Fizzbuzz");
    console.log(number);
  } if(number % 3 ==0){
    console.log("Fizz ");
    console.log(number);
  } if(number % 5 ==0){
    console.log("Fizz ");
    console.log(number);
  }
}

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

for(let i=1; i<=20;i++) {
  if(i % 2 == 0) {
    console.log(i +" is even");
  } else {
    console.log(i +" is odd");
  }  
}

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

```
for(let i=0; i<=10;i++) {
  console.log(i*9);
}
```

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
for(let i=0; i<=10;i++) {
  console.log("Table of " +i);
  for(let j=0; j<11; j++){
    console.log( i + " * " + j + " = " +(i*j));
  }
}
<br>


