Day 02 Engineering Lab: Communicating with Computers
**Objective:** Today you will communicate with a computer for the first time. Your goal is not to memorize JavaScript, but to understand how a computer receives, processes, and executes your instructions. Every great engineer understands how their programs actually work. **Submission Instructions:** 1. Copy the complete worksheet template provided below. 2. Create a new file named `day-02-lab.md` in your local GitHub repository. 3. Paste the template and fill in all the blanks (____) and tables with your answers. 4. Commit and push the changes to your remote GitHub repository. 5. Submit the direct GitHub URL of your completed file here. --- COPY WORKSHEET TEMPLATE BELOW --- # ============================================================================= # CodeWeavers Learning Operating System # Day 02 Engineering Lab # ============================================================================= 
# Program: MERN Job Ready Program # Phase: Phase 1 — Programming Foundations # Week: Week 1 — Think Like a Programmer 
# Day: 02 # Lab Theme: Communicating with Computers --- # Engineering Mission Today you will communicate with a computer for the first time. Your goal is not to memorize JavaScript. Your goal is to understand how a computer receives, processes and executes your instructions. 

---# Engineering Competencies After completing today's lab, you should be able to: [ ] Install and verify Node.js [ ] Create a JavaScript project folder [ ] Create and save JavaScript files [ ] Execute JavaScript programs using Node.js [ ] Predict program output before execution [ ] Explain the JavaScript execution pipeline [ ] Differentiate between VS Code and Node.js 

--- # Engineering Workflow Think -> Write -> Save -> Execute -> Observe -> Improve -> Repeat 


--- # Lab Activity 1: Development Environment Setup (15 Minutes) 
Step 1: Create a folder named Day02 
Step 2: Open the folder using VS Code. 
Step 3: Open Terminal. 
Step 4: Verify Node.js installation (Run: node -v) 
Step 5: Check npm (Run: npm -v) 

Mentor Verification: [ ] VS Code installed [ ] Node installed [ ] Terminal working 
---> yes all working

--- # Lab Activity 2: Your First JavaScript File (10 Minutes) 

Create a file: hello.js 
Write: console.log("Hello CodeWeavers!"); 
Run: node hello.js 

Reflection: How did the computer display your message? --> Hello CodeWeavers!


--- # Lab Activity 3: Predict Before You Run (15 Minutes) Do NOT execute immediately. First, predict the output. 

Program 1: console.log("Software Engineering"); 
Prediction: Software Engineering
Actual Output: Software Engineering


Program 2: console.log(100);
Prediction: 100 
Actual Output: 100


Program 3: console.log(50 + 25); 
Prediction: 75
Actual Output: 75

Program 4: console.log("Age:", 20); 
Prediction: Age: 20
Actual Output: Age: 20 

Engineering Reflection: Did your prediction match the output? Why?
--> yes, all prediction matches my output because i learn basics of js previously


--- # Lab Activity 4: Understanding the Execution Pipeline (10 Minutes) Arrange the following in the correct order: CPU, JavaScript Code, Node.js, Output, V8 Engine Correct Flow:
Javascript code -> Node.js -> V8 Engine -> CPU -> Output 
 
 
 
 --- # Lab Activity 5: Complete the Concept Map Fill the blanks.

 Human -> JS code -> Node.js -> v8 Engine -> Machine Language -> CPU  -> Output 
 
 
 --- # Lab Activity 6: Real-World Engineering Choose any software (e.g., WhatsApp, Instagram, Calculator). | Question | Answer | |----------|---------| | 
 
Web Whatsapp
 
Programming Language (Guess) |Javascript | |
Runtime (Guess) |Node.js(V8 Engine/spiderMonkey) | | 
Users |people who wants to communicate via messages/audio&video call | | 
Problem Solved | Communication/Audio & video call with internet| 
 
 
 --- # Lab Activity 7: Explore console.log() (15 Minutes) Experiment with different inputs. 
 
 Program A: console.log("Welcome"); Output: Welcome
 Program B: console.log(200); Output: 200
 Program C: console.log(15 + 5); Output: 20
 Program D: console.log("JavaScript"); console.log("Node.js"); 
 Output: JavaScript
         Node.js
 Program E: console.log("Code"); console.log(2026); console.log(50 + 50); 
 Output: 2026
         100
 
 
 --- # Engineering Challenge Without copying, create your own file named introduction.js. Print your Name, College, City, Favourite App, Dream Company, and Why you joined CodeWeavers. 
 


 --- # Mini Debugging Challenge Find the mistake. 
 
 Program 1: console.log("Hello) What is wrong? -> console.log("Hello"); 
 Program 2: Console.log("Hello"); What is wrong? --> Nothing
 Program 3: console.log("Welcome") \n console.log("CodeWeavers") Will it run? Yes / No. --> NO
Explain: because \n is not used in javascript, it gives a syntax error or invalid tokens used
 
 Program 4: console.log(10+) What is wrong? --> something missing after +, which gives error of unexpected token
 
 --- # Engineering Thinking Answer in your own words. 
 
 1. Why can't VS Code execute JavaScript? 
 ==> because vs code is only a code editor and it has not runtime environment like node.js and v8 engine to execute js.


 2. Why do we need Node.js?
 ==> Node.js is a runtime environment by which we can execute javascript code.


 3. What would happen if computers understood only Binary?
 ==> If computers understood only binary, humans have to program only in binary (0s & 1s) which make a extremely difficult to making any software and very time consuming.

 4. What is the purpose of programming languages? 
 ==> Programming language is like a mediator between human and computers , it helps to understand computers what actually human want.
 
 
--- # Team Activity Work in pairs. One student acts as "Human", the other as "Computer". The Human gives instructions to draw a square. The Computer follows the instructions exactly. Discuss how this relates to programming.
==>> When human gives intruction to draw a square , the computer compiler changes this instruction to a machine language code(binary) and then processes to find an output and this output is in binary then it converted to a human readable format then a sqaure is visible.
  
  
--- # Bonus Challenge ⭐ Research and write one interesting fact about each. 
  | Technology | Interesting Fact | |------------|------------------| 
  | JavaScript | Javascript runs almost everwhere in mobile, computers, server,smart devices etc| 
  | Node.js | After node.js , javascript used for both frontend and backend | 
  | Google Chrome | chrome using v8 engine to run js | 
  | VS Code | vs code do not have their own runtime environment for all programming languages, we have to download it seperately| 
  
  
  
  
  
  --- # Self Assessment Rate yourself honestly (1-5). | Skill | Rating | |------|---------| | 
  I understand why programming languages exist. | [5 ] | | 
  I can explain Binary. | [ 5] | | 
  I understand Node.js. | [5 ] | | 
  I understand Runtime. | [5 ] | | 
  I can execute JavaScript using Node.js. | [ 5] | | 
  I can predict simple program output. | [ 5] | 
  
  
  
--- # Home Assignment Create a project folder named MyFirstProject. Inside it, create three files: hello.js, about_me.js, dream.js. Each file should print meaningful information using console.log().
Try changing the messages, numbers, and calculations to observe how the output changes. 


--- **Engineering Lab Complete** **Today's Achievement:** You successfully communicated with a computer for the first time. That single step marks the beginning of your journey from learner to software engineer.