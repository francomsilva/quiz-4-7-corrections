# quiz-4-7-corrections

## Quiz 4 Corrections

### Question 9
This question asked to declare and initialize a variable called x with the value 27. I got this question wrong because I didn't know the difference between declaring and initializing so I selected the answer that only initializes the variable with the correct value, but doesn't declare it. The correct answer is the following:
```
let x;
x = 27;
```
### Question 10
I got points off of this question because it asked to select all that apply and I missed a few correct answers and chose a few incorrect answers. Therefore the question asked to choose all the following valid data types in Javascript and I chose `boolean`, `integer`, `number`, `string`, `null`, `character`, `undefined` and `integer`, but only 5 out these 7 were correct. Two of which I chose, `integer` and `character`, were incorrect and instead I should've chosen `object` and `symbol`.

### Question 11
For this question, I know for a fact that what I got wrong was that I used `Math.floor`, when I should've used `Math.ceiling`.

## Quiz 5 Corrections

### Question 1

This was a multiple choice question where I selected the wrong answer, which is because I didn't include one extra `=`. Instead I chose: 
```
x == y
x != y
```
when it was supposed to be:
```
x === y
x !== y
```
### Question 2
This was another multiple-select question where I missed correct answers and chose an incorrect one. This question asked for valid relational operators in Javascript and out of the ones I chose, I got one wrong and I incorrectly picked `=`.

### Question 4
This was another multiple-select question and for this one, I did not miss any, but I just selected an extra one, but it was a wrong one. I wrongly chose `?`.

###Question 5
This question asked to satisfy the above statements with two missing operators. I got this question wrong simply because I chose the answer that had `&&` and `&&`. I should've chosen the answer that had `&&` and `||`.

###Question 6 
This question asked what was the simplest way to achieve the goal stated. I chose the answer with the switch and case statements when I should've chosen the answer with the if statement and then the else statements that was the shortest since the longer one wasn't the simplest way.

###Question 8
For this question, it was another multiple-select question, and I selected 2 answers that were correct, but there was another answer that I missed. The one i missed was:
```
let status = (studentGrade < 88) ? "ND" : "HR";
```
###Question 11
This was a multiple choice question where I selected the wrong answer. I chose the answer without the `break;` when the correct answer included the `break;`.

###Question 12
I got this question wrong because I mixed up the four components of a `for` loop. The answer I chose had the steps in order of: setup, expression, loop body, update, and repeat. The correct answer had the steps in order of: setup, expression, loop body, update, and return to step 2.

## Quiz 6 Corrections 

### Question 2
I got this question wrong because I didn't know that if you pass in fewer arguments than there are parameters in the function definition, then the parameters that did not receive arguments will be undefined. I thought the parameters that did not receive arguments will take on the value of one of the parameters that did.

### Question 4
I got this question wrong because I included `Math.random` as a built-in function that accepts parameters, when in reality, it doesn't.

### Question 7
For this question I selected 2 answers, and only one was wrong. However, I missed two other answers that were correct. These were: 
```
I need to do chores, homework, and undefined... So busy!
```
and
```
I need to do homework, homework, and more homework... So busy!
```
### Question 8
I got this question wrong because I chose the wrong revision for the function provided so that it accepts as parameters the values being divided. The correct revision was as follows:
```
function divide (a, b) {
    return a / b;
}
```
### Question 10
I got this question wrong because the correct answer should have been that the both snippets of code that was provided will run infinitely and thats what they have in common.

### Question 11
I got this question wrong because I didn't know what would be the result of the code snippet provided:
```
function example() {        // line 1
    let x = 1;              // line 2
                            // line 3
    if (x === 1) {          // line 4
        var y = 2;          // line 5
                            // line 6
        console.log(x)      // line 7
    }                       // line 8
                            // line 9
    console.log(y);         // line 10
}                           // line 11
```
The answer I chose was that `2` will be printed to the console, and the correct answer was `1` and `2` will be printed to the console.

###Question 12
I got this question wrong because I didn't know what would be the result of the code snippet provided:
```
function example(a, b, c) {
    if (a === 1) {
        if (b === 2) {
            if (c === 3) {
                var d = 4;
            }
        }
    }
    
    console.log(d);
}
```
The answer I chose was that `4` will be printed to the console, and the correct answer was `4` or `undefined` will be printed to the console.

###Question 15
I got this question wrong because I didn't know what would be the result of the code snippet provided:
```
function example() {        // line 1
    let x = 1;              // line 2
                            // line 3
    if (x === 1) {          // line 4
        let y = 2;          // line 5
                            // line 6
        console.log(x)      // line 7
    }                       // line 8
                            // line 9
    console.log(y);         // line 10
}                           // line 11
```
The answer I chose was that `1` and `2` will be printed to the screen, and the correct answer was that a ReferenceError will occur on line 10. 

## Quiz 7 Corrections

### Question 2
I got this question wrong because I counted the numbers as if they were in an array so 0 was 0 and 20 was 10.

### Question 6 
I got this question wrong because I missed two correct answers, but chose one correct. The question provides the following code:
```
let a = [];
let b = [ 1, 2, 3 ];
let c = [ "a", "b", "c" ];
```
It asked which of the following represent the contents of each of these arrays, I chose `empty array`, `undefined, undefined, undefined`, and `null, null, null` because I wasn't sure what the question was asking and the `a, b, c` threw me off.

### Question 9 
For this question I thought what it asked was to remove `Honda` and add `Volkswagen` to the end to maintain the order of the items without `Honda`. The correct answer was `cars[3] = "Volkswagen";`.

### Question 13
This was a multiple-select question that asked which if statements would print the provided statement. I lost points on this question because I chose 2 correct answers and 1 incorrect answer, while there was another correct answer. Each of the correct answers use a built-in method of either `indexOf`, `includes`, or `lastIndexOf`.
