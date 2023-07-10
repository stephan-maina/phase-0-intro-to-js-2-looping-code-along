# Looping Lab

# Looping Code Along
This repository contains examples of looping code in JavaScript. Looping allows you to repeat a block of code multiple times, making it easier to perform repetitive tasks. Here are some examples of looping code:

# For Loop
The for loop is commonly used when you know the number of iterations required.

javascript
Copy code
for (var i = 0; i < 5; i++) {
    console.log("Iteration " + i);
}
This example demonstrates a for loop that iterates 5 times and logs the current iteration number to the console.

# While Loop
The while loop is used when you want to repeat a block of code while a specific condition is true.

javascript
Copy code
var count = 0;

while (count < 5) {
    console.log("Count: " + count);
    count++;
}
In this example, the while loop continues as long as the count variable is less than 5. The current count is logged to the console with each iteration.

# Do-While Loop
The do-while loop is similar to the while loop, but it executes the code block at least once before checking the condition.

javascript
Copy code
var i = 0;

do {
    console.log("Value of i: " + i);
    i++;
} while (i < 5);
This example demonstrates a do-while loop that executes the code block at least once and then continues as long as i is less than 5.

For...in Loop
The for...in loop is used to iterate over the properties of an object.

javascript
Copy code
var person = {
    name: "John",
    age: 30,
    city: "New York"
};

for (var prop in person) {
    console.log(prop + ": " + person[prop]);
}
In this example, the for...in loop iterates over the properties of the person object and logs the property name and its corresponding value to the console.

These examples provide a basic understanding of different looping constructs in JavaScript. You can modify the code examples and experiment with different loop conditions and iterations to suit your needs.


