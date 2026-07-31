🧠 ENGINEERING LAB: UNDERSTANDING PROGRAM MEMORY THROUGH VARIABLES

Objective: Today you will teach your program to remember something for the first time. Your goal is not to memorize the words "let" or "const" — it's to understand how a computer actually stores information in memory, and why every login form, shopping cart, and app you'll ever build depends on this one idea.

──────────────────────────────

🎯 THE CORE QUESTION

Yesterday, your program could speak (console.log). But it had no memory — every value vanished the instant it was printed.

Today's mission: give your program a memory.

By the end of this lab, you should be able to answer, without hesitation:
"If I ask my program to remember my name, what actually happens inside the computer?"

──────────────────────────────

🧩 WHAT YOU'LL LEARN

🔹 Why programs need memory at all
🔹 The difference between a Variable and a Value
→ "The value lives in memory. The variable is only its name."
🔹 Declaration vs Initialization vs Assignment
🔹 let — for values that change
🔹 const — for values that shouldn't
🔹 var — why modern JavaScript avoids it
🔹 Variable naming rules & camelCase best practices

──────────────────────────────

🛠️ LAB TASKS

1️⃣ Create a file called variables.js

2️⃣ Declare and initialize variables for:
• your name
• your age
• your city

3️⃣ Print each variable using console.log()

4️⃣ Demonstrate that a let variable can be updated:
let score = 50;
console.log(score);
score = 90;
console.log(score);

5️⃣ Declare one const variable (e.g., your country) and explain in a comment why it should NOT change
---> const country = "India";
     console.log(country);

    const is a variable which stores constant value which can't change further because it creates immutable reference to the data.

📦 DELIVERABLE — "profile.js"

Build a file that stores and prints the following using properly named variables:

✅ Name ✅ Dream Company
✅ Age ✅ Favourite Programming Language
✅ City ✅ Hobby
✅ College ✅ Goal
✅ Graduation Year ✅ Favourite App

Every single value must be printed using console.log() — no hardcoded repeated strings.

──────────────────────────────

⚠️ COMMON TRAPS TO AVOID

❌ Using var anywhere in your code
❌ Variable names starting with a number (1age)
❌ Non-descriptive names (x, a, temp)
❌ Reassigning a const

──────────────────────────────

💡 PRO TIP

A good variable name should let someone read your code and understand it WITHOUT you explaining it out loud. If you have to say "this variable holds the user's age," rename it userAge instead.

──────────────────────────────

🏆 SUCCESS CRITERIA

✔ Program runs with zero errors using node profile.js
✔ All 10 required fields are stored as variables and printed
✔ Correct use of let vs const (justified with a comment)
✔ Clean camelCase naming throughout
✔ No use of var

──────────────────────────────

🔮 WHY THIS MATTERS

Every project you'll build in this program — login forms, shopping carts, weather apps, expense trackers, student management systems — starts with exactly this: variables holding data in memory.

Master this today, and every future lab gets easier. 🚀