=============================================================================
🚀 CodeWeavers Learning Operating System
⚡ DAY 06 ENGINEERING LAB
=============================================================================

🎯 LAB THEME

"Teach Your Program to Think Before It Acts."

Yesterday your program learned how to perform calculations.

Today, you will teach it how to make intelligent decisions.

Welcome to the beginning of real programming.

=============================================================================

🎯 LAB OBJECTIVES

By the end of today's lab, you should be able to:

✅ Compare values using Comparison Operators.

✅ Combine conditions using Logical Operators.

✅ Write programs using if statements.

✅ Build decision-making programs using if...else.

✅ Handle multiple conditions using else if.

✅ Read and debug conditional logic.

✅ Think like a Software Engineer.

=============================================================================

📚 PREREQUISITES

Before starting this lab, you should know:

✔ Variables

✔ Data Types

✔ Operators

✔ console.log()

✔ Running JavaScript with Node.js

=============================================================================

⚠️ LAB RULES
Predict every output before executing.

Write code yourself.

Do not copy from others.

Debug first, ask later.

Every answer should have a reason.


=============================================================================

🧠 LAB 01 — DECISION THINKING

Write only the CONDITION.

Do NOT write code.

------------------------------------------------
A student can vote only if age is 18 or above.


Condition
if(age >=18){

}
_________________________

------------------------------------------------
A customer gets free delivery if the order amount is ₹499 or more.


Condition
if(orderAmount>=499){

}
_________________________

------------------------------------------------
A student passes if marks are 33 or above.


Condition
if(marks>=33){

}
_________________________

------------------------------------------------
A user can drive only if age is 18 or above AND has a driving license.


Condition
if(age>=18 && drivingLicense==true){

}
_________________________

------------------------------------------------
Today is a holiday if it is Saturday OR Sunday.


Condition
if(day== "Saturday" || day == "Sunday"){

}
_________________________

=============================================================================

🧪 LAB 02 — COMPARISON OPERATOR PRACTICE

Predict the output first.

Then execute.

------------------------------------------------

console.log(20 > 10);

Prediction
true
____________

Output
true
____________

------------------------------------------------

console.log(20 < 15);

Prediction
false
____________

Output
false
____________

------------------------------------------------

console.log(15 == "15");

Prediction
true
____________

Output
true
____________

------------------------------------------------

console.log(15 === "15");

Prediction
false
____________

Output
false
____________

------------------------------------------------

console.log(25 != 10);

Prediction
true
____________

Output
true
____________

------------------------------------------------

console.log(18 >= 18);

Prediction
true
____________

Output
true
____________

------------------------------------------------

console.log(12 <= 8);

Prediction
false
____________

Output
false
____________

=============================================================================

🧠 LAB 03 — LOGICAL OPERATOR PRACTICE

Predict first.

------------------------------------------------

console.log(true && true);

Prediction
true
____________

Output
true
____________

------------------------------------------------

console.log(true && false);

Prediction
false
____________

Output
false
____________

------------------------------------------------

console.log(false || true);

Prediction
true
____________

Output
true
____________

------------------------------------------------

console.log(false || false);

Prediction
false
____________

Output
false
____________

------------------------------------------------

console.log(!true);

Prediction
false
____________

Output
false
____________

------------------------------------------------

console.log(!false);

Prediction
true
____________

Output
true
____________

=============================================================================

💻 LAB 04 — FIRST IF PROGRAM

Create

eligibility.js

Store

Age = 20

If age is greater than or equal to 18

Print

Eligible for Voting

Expected Skills

✅ Comparison Operator

✅ if Statement

=============================================================================

💻 LAB 05 — IF...ELSE CHALLENGE

Create

pass-fail.js

Store

Marks = 29

If marks are 33 or above

Print

PASS

Otherwise

Print

FAIL

-----------------------------------------------------------------------------

Now change the marks to

45

75

92

Observe the output.

=============================================================================

🏆 LAB 06 — ELSE IF CHALLENGE

Create

grade-checker.js

Conditions

90 and above

↓

Grade A

--------------------------------

75–89

↓

Grade B

--------------------------------

60–74

↓

Grade C

--------------------------------

33–59

↓

Grade D

--------------------------------

Below 33

↓

Fail

Test your program using

95

82

69

45

18

=============================================================================

🌍 LAB 07 — REAL WORLD DECISION MAKING

Question 1

A student can enter the examination hall only if

Attendance >= 75

Write the condition.
if(Attendance >= 75){

}
________________________________

------------------------------------------------

Question 2

A customer receives free shipping if

Order Amount >= 999

Write the condition.
if(orderAmount >= 999){

}
________________________________

------------------------------------------------

Question 3

A person can drive only if

Age >= 18

AND

License == true

Write the condition.
if(Age >= 18 || License == true){

}
________________________________

------------------------------------------------

Question 4

Office is closed if

Saturday

OR

Sunday

Write the condition.
if(day == "Saturday" || day =="Sunday"){

}
________________________________

=============================================================================

🐞 LAB 08 — DEBUGGING MISSION

Find and fix every mistake.

------------------------------------------------

Program 1

let age = 20;

if(age >= 18){       // = -> >=

console.log("Eligible");

}

------------------------------------------------

Program 2

let marks = 35;

if(marks >= 33){   // >== -> >=

console.log("Pass");

}

------------------------------------------------

Program 3

let age = 17;

if(age >= 18) {

console.log("Eligible")

}
else{

console.log("Not Eligible")      // All correct but for better readability we can ensure to write if - else in block
}
------------------------------------------------

Program 4

console.log(20 === "20");   // 20" -> "20"

------------------------------------------------

Program 5

console.log(true && true);        // after && , we must have add one more condition like false /true or any condition
--> Output - true
=============================================================================

🧩 LAB 09 — OUTPUT PREDICTION

Predict before executing.

------------------------------------------------

let age = 22;

if(age >=18){

console.log("Adult");

}
 ---->> Adult
------------------------------------------------

let marks = 20;

if(marks >=33){

console.log("Pass");

}else{

console.log("Fail");

}

---->> Fail
------------------------------------------------

let x = 20;

if(x > 10){

console.log("A");

}else{

console.log("B");

}

---->> A
------------------------------------------------

let day = "Sunday";

if(day == "Sunday"){

console.log("Holiday");

}
 ----> Holiday
------------------------------------------------

let loggedIn = false;

if(!loggedIn){

console.log("Please Login");

}
----> Please Login
=============================================================================

🚀 LAB 10 — MINI PROJECT

Project Name

Student Scholarship Checker

Requirements

Store

Student Name

Age

Marks

Attendance

Rules

If

Marks >= 85

AND

Attendance >= 75

Print

Scholarship Approved

Otherwise

Print

Scholarship Not Approved

Bonus

Also print

Student Name

Marks

Attendance

Result

=============================================================================

🌟 BONUS CHALLENGE

Build

Simple Login Checker

Store

Username

Password

Correct Username

admin

Correct Password

1234

If both are correct

Print

Login Successful

Else

Print

Invalid Credentials

(Hint: Use &&)

=============================================================================

🎤 RAPID FIRE

Answer in ONE LINE.
What is Decision Making?
--> decision making is the process of making decision of what to do either this or that by using if-else, switch, ternary operators (mainly conditional operators)

------------------------------------------------
Difference between == and ===?
--> == compares only value but === compare both datatype and value

------------------------------------------------
Difference between && and ||?
--> && gives true only if all the conditions are true  and  || gives true if only one condition is true.

------------------------------------------------
When do we use if...else?
--> we use if...else , when there is more than one condition in which one is true and another is false

------------------------------------------------
What is Nested if?
--> Nested if is a loop of more than two condition , else if is used for nested if

------------------------------------------------
Which operator reverses a Boolean value?
--> not operator (!)

------------------------------------------------
What does >= mean?
--> greater than or equal to

------------------------------------------------
What does !== check?
--> Strictly not operator which checks datatype and value both

------------------------------------------------
Which operator checks Value AND Data Type?
--> === and !==

------------------------------------------------
Why do software applications use conditions?
--> Software applications use conditions to make decision

=============================================================================

📝 REFLECTION JOURNAL
Which topic was easiest today?
--> if...else condition
________________________________
Which operator confused you the most?
--> logical operator

________________________________
Which debugging question took the longest?
--> console.log(false || false);

________________________________
Name three real software applications that use Decision Making.

 1. Google Maps
________________________________
 2. Instagram
________________________________
 3. Netflix
________________________________
Today's Confidence Score


⭐ 10 / 10

=============================================================================

🏆 SELF ASSESSMENT

☑ I understand Comparison Operators.

☑ I understand Logical Operators.

☑ I know the difference between == and ===.

☑ I can use && correctly.

☑ I can use || correctly.

☑ I understand the NOT operator.

☑ I can write if statements.

☑ I can write if...else programs.

☑ I can write else if ladders.

☑ I can debug conditional programs.

☑ I can solve real-world decision-making problems.

=============================================================================

🎯 MISSION COMPLETE

Congratulations!

Your programs can now make decisions.

You have crossed an important milestone in programming.

Until yesterday, your programs could only store data and perform calculations.

Today, they became capable of thinking based on conditions.

Next Class:

🚀 switch Statement

Learn how professional software handles multiple choices more efficiently.

=============================================================================
END OF DAY 06 ENGINEERING LAB
=============================================================================