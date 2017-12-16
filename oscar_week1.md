Javascript Course Assessment

Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find

1. Name some of the data types in Javascript.

   //Your Answer 
   // Numbers, Strings, Booleans, Symbols, Arrays, Objects 

//Googled Answer

2. Describe what "if" does in Javascript.

 //Your Answer 
   // If does goes through a statement and determines if it is true or false, will perform function or display message

//Googled Answer

3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".

function divByThree (x) {
  if (x % 3 === 0 ) {
    return x + " is divisible by three";
  } if (x % 3 > 0) {
    return x + " is not divisible by three";
  } else {
    return x + " cannot be divisible by three";
  }
};
  
divByThree();

4. What is JSON?

//Your Answer  
   // JavaScript Object Notation lightweight 

//Googled Answer JavaScript Object Notation

5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

let aboutOscar = {
  Name: "Oscar",
  State: "Wisconsin",
  FavColor: "Red",
  hobbies: ['powerlifting', 'dj', 'coding']
}


6. What is a closure?

//Your Answer
   // Closure's access variables in local scope for global scope. 


//Googled Answer
   // Global variables can be made local (private) with closures

7. What's the difference between =, ==, and === in JavaScript?

//Your Answer = assigns vaule, == is equal, === is equal vaule.

//Googled Answer

8. Create an array with at least 4 items inside it, then access two of the values and console.log() them. Try to access the two values in two different ways.

colors =['red','gold', 'black', 'grey'];
colors[1]
colors[2]
console.log(colors[1]);
console.log(colors[2]);

9. Describe the different kinds of loops and why you would use them.

//Your Answer
   // for loop: Loops through a block of code. Use when you know how many times you want to loop. 
   // While loop: Loops through code as long as the condition is true. Use when you do not know the number of times to loop.
   // Do/While loop: Runs block of code before checking if conditon is true. Loop will repeat if condition is true. 
   // For/In Loop: 

//Googled Answer
 // Advantage of DO/While loops: lets say that you wants to bake 5 cookies, but if friends come over you'll make more cookies
 // The for/in statement loops through the properties of an object. The block of code inside the loop will be executed once for each property

10. How would you explain "scope" in javascript?

//Your Answer 
   /* Scope is a variable inside or outside a function. 
   If the variable is outside the function it is a global scope. 
   If the variable is inside the function it is a local scope.
   */

//Googled Answer