Java Script

# **Key Notes**

**Creating a JavaScript Platform**

- You can write JavaScript code directly into the .HTML file, using the <script> tag

- Alternatively, you can create multiple .js file in the same repository as your HTML file, and link them into your .HTML file using the <script> tag.

**Tagging JavaScript Code**

- You write <script src="NameOfJsCode"></script> in the <head> segment of the .html

- Then you call on the function by <section> NAMEOFFUNCTION()</section>

**Defining Variables**

- The first time you define a variable, you have to define it with let
- The next time you use that variable, you should NOT use let any more. Just directly use the variable by its name.
- variable + 3 performs an operation that adds 3 to the variable. It does NOT modify the variable.
- Be careful of hardcoding. Do not replace variable + 3 with a number because we want our code to work for any value given to variable.

_Terms I've Learnt_

- **Variable** = for storing info for later on eg. let **age** = 21, the variable is age
- let = used to create a new variable, (example above) let is only used once for each variable. after this you can refer to the variable by name alone.
- **=** the equal sign is used to assign value
- **==** doubled up, this acts like a traditional equal sign in maths
- **Empty Variable** = does not have brackets
- **Conditional Statements**
  = **if** (WRITE CONDITION) {CODE RESPONSE;
  } **else if** (WRITE CONDITION) {CODE ALTERNATIVE RESPONSE;
  } **else** (WRITE CONDITION) {CODE FINAL POSSIBLE RESPONSE}
  FOR EXAMPLE:
  let **message**(_THIS IS AN EMPTY VARIABLE_);

if (time <= 11(_THIS IS THE CONDITION_)) {
message = ", HannahGood Morning " + myName + "!"(_THIS IS CODE REFERING TO THE EMPTY VARIABLE_);
} else if (time <= 18) {
message = "Good afternoon " + myName + "!";
} else if (time < 24) {
message = "Good evening " + myName + "!";
} else {
message = "c'mon " + myName + ", thats is not a valid time!";
}

**NOTE: JAVASCRIPT CONDITIONAL STATEMENTS MUST BE IN ORDER OF POSSIBILITY. THE VALUE WILL SETTLE ON THE FIRST STATEMENT THAT IT FINDS IS TRUE, DESPITE THERE BEING MORE ACCURATE ONES AVAILABLE LATER IN THE CODE.**
