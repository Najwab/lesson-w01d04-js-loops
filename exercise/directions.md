

# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
for(let i =0;i<=10;i+=i){
  console.log(i);
}
```

<br>

## Print every number from 10 to 0

```
for(let i = 10; i>0 ;i=i-1){
  console.log(i);
}
```

<br>

## Print every number from 4 to -16

```
for(let i =4;i>=-16;i-=1){
  console.log(i);
}
```

<br>

## Print every fifth number from 8 to 41

```
for(let i =8;i<=41;i+=5){
  console.log(i);
}
```

<br>

# Exercises: JavaScript loops with array:

Paste your answers into this file.



1. Change all **odd** numbers to be those numbers multiplied by two:
```js
const numbers = [4, 9, 7, 2, 1, 8];
//or i<numbers.length
  for(let i= 0;i<=numbers.length-1;i=i+1){
   if(numbers[i]%2!==0){
     numbers[i]=numbers[i]*2}
   console.log( numbers[i]);
 };

numbers; // => [4, 18, 14, 2, 2, 8]
```

2.  Create an array to hold your favorite colors.  For each choice, log to the screen a string like: `My #1 choice is blue.`

const myColors=['pink','yellow','blue'];
for(let i =0 ; i<myColors.length ;i++){
console.log("My #"+i+"choice is "+ myColors[i] +".");
}

3.  Create an array of ages.  Loop through and log only the ages that are over 21.
const age= [12,19,20,21,22,33,44,55,66,77,90];
for(let i=0 ;i<age.length ;i++){
  if(age[i]>21){
    console.log(age[i]);
  }
}


1. Create an array to hold your top five choices of something (music, books, movies, whatever).
const myBestFive=['Winner','Bigbang','blackpink','Ateez'];
for(let i =0;i<myBestFive.length ; i++){
  console.log("My #"+i+" choice is "+ myColors[i] +".");

}
    - For each choice, log to the screen a string like: "My #1 choice is blue."
    - **Bonus:** Change it to log "My 1st choice, "My 2nd choice", "My 3rd choice", picking the right suffix for the number based on what it is.


## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
for(let i=1;i<=100;i++){
  if(i%3===0 && i%5===0){
    console.log('FizzBuzz');
  }else if(i%5===0){
    console.log('Buzz');
  }else if(i%3===0){
    console.log('Fizz');
  }
};
```

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
for(let i=0;i<=20;i++){
  if(i%2!==0){
    console.log(i+" is odd");
  }else {
    console.log(i+" is even");
  }

};
```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
for(let i=0;i<=10;i++){
 let result=i*9; 
 console.log(i+"*9= "+result);
};
```

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```
for(let i=60;i<100;i++){
  if(i>=90){
  console.log("For "+i+",you got an A");
  }else if (i>=80){
  console.log("For "+i+",you got an B");
  }else if(i>=70){
    console.log("For "+i+",you got an C");
  }else if(i>=60){
    console.log("For "+i+",you got an D");
  }

};
```
