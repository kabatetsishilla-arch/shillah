# shillah
composed notes
1. What are hooks?
In programming, hooks are special functions that allow us to use certain features or connect to specific behaviour in a program.
The meaning of hooks depends on the programming language or technology being used.
For example, in React JavaScript, hooks allow us to use features such as state and other React functions inside functional components.
Common React hooks include:
1. useState – helps a program store and update information.
2. useEffect – helps perform actions when a component loads or when certain information changes.
3. useContext – helps share information between components.
4. useRef – helps refer to a particular element or store a value without causing a re-render.
Simple example: A counter that increases when you click a button can use the useState hook to remember the current number.
Note: Hooks are not the same as loops. Hooks are mainly associated with React and some other programming tools.
2. What is a loop?
A loop is a programming structure that repeats a block of code several times until a condition is met or a certain number of repetitions is completed.
Example: Instead of writing five separate statements to display numbers from 1 to 5, we can use a loop.
3. Types of loops
There are four common types of loops in programming.









1. For loop
A for loop is used when we know how many times we want to repeat an action.
Example in JavaScript:
for (let i = 1; i <= 5; i++) {
    console.log(i);
}


Output: 1, 2, 3, 4, 5.












2. While loop
A while loop repeats code as long as a condition is true.
Example:
let i = 1;

while (i <= 5) {
    console.log(i);
    i++;
}


Output: 1, 2, 3, 4, 5.












3. Do-while loop
A do-while loop executes the code at least once before checking the condition.
Example:
let i = 1;

do {
    console.log(i);
    i++;
} while (i <= 5);


Output: 1, 2, 3, 4, 5.












4. For...of loop
A for...of loop is used in JavaScript to go through items in a collection, such as an array.
Example:
let fruits = ["Mango", "Apple", "Banana"];

for (let fruit of fruits) {
    console.log(fruit);
}


Output: Mango, Apple, Banana.



4. Difference between the loops
Type	Main use
For loop	Repeats code a known number of times.
While loop	Repeats while a condition is true.
Do-while loop	Executes at least once before checking the condition.
For...of loop	Goes through items in a collection.
5. Why are loops important?
- They reduce repeated code.
- They save time when writing programs.
- They make code easier to manage.
- They help process many items, such as student marks or names.
- They allow programs to repeat tasks automatically.
