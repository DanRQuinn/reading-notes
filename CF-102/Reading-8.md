# Operators and Loops

## Expressions and Operators

From [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

### Comparison Operators

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values

The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons

const var1 = 3;
const var2 = 4;

### Assignment Operators

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

## Loops and iteration

From: [Loops and iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

### For Statements

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

When a for loop executes, the following occurs:

The initializing expression initialization, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
The condition expression is evaluated. If the value of condition is true, the loop statements execute. Otherwise, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
If present, the update expression afterthought is executed.
Control returns to Step 2.

<!-- <form name="selectForm">
  <label for="musicTypes"
    >Choose some music types, then click the button below:</label
  >
  <select id="musicTypes" name="musicTypes" multiple>
    <option selected>R&B</option>
    <option>Jazz</option>
    <option>Blues</option>
    <option>New Age</option>
    <option>Classical</option>
    <option>Opera</option>
  </select>
  <button id="btn" type="button">How many are selected?</button>
</form> -->


### While Statements

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition)
  statement

If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ }) to group those statements.

The following while loop iterates as long as n is less than 3:

let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}

With each iteration, the loop increments n and adds that value to x. Therefore, x and n take on the following values:

After the first pass: n = 1 and x = 1
After the second pass: n = 2 and x = 3
After the third pass: n = 3 and x = 6
After completing the third pass, the condition n < 3 is no longer true, so the loop terminates.

Avoid infinite loops. Make sure the condition in a loop eventually becomes false—otherwise, the loop will never terminate! The statements in the following while loop execute forever because the condition never becomes false:

// Infinite loops are bad!
while (true) {
  console.log("Hello, world!");
}

1.What is an expression in JavaScript?

-It is a piece of code that produces value

2.Why would we use a loop in our code?

- So that you can execute a block of code multiple times

3.When does a for loop stop executing?

- When the loop condiotions become false

4.How many times will a while loop execute?

- If the condition in the loop header remains true it will execute indefinatly
