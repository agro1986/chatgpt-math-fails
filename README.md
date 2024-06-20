# ChatGPT Math Fails

This repository is a collection of ChatGPT fails when answering university (undergraduate) textbook level math questions.
At first I wanted to relearn math with the assistance of ChatGPT, thinking that its assistance will supercharge my learning.
However it turned out that I was the one having to correct and teach ChatGPT math.

## Technical details

* The version used is ChatGPT 4o from the website as a pro user (not API/playground).
* Memory and custom instructions are turned off.
* No extra prompting such as "think step by step".
* When an exercise asks for a bunch of independent questions (such as "prove the statements a, b, and c"),
  I might ask the questions separately (such as "prove the statement a").

## Recommendations

* If you are a student, you need to critically check ChatGPT's answers. It can still be useful to give you pointers in the right direction,
  such as asking "How do I prove x?" but you still need to check all details of the answer.
* If you are training LLMs, having a high-quality data of textbook problems and their correct solutions for training seems to be a low hanging fruit.

# A Concise Introduction to Pure Mathematics 4th edition by Martin Liebeck

## Chapter 1 Exercises Solution Fail

* [1.4](https://chatgpt.com/share/4c1c1419-97d4-469d-94ca-651db0a48586): Thinking is correct but final conclusion not thorough. Says a → d and e, but doesn't realize that d and e each also implies the others
* [1.5.a](https://chatgpt.com/share/6ce350be-d4be-4bb7-8eb0-4e7cbc5a341b): Wrongly interpreted A only if B as B → A, even though it should be A → B
* [1.5.e](https://chatgpt.com/share/99392bf9-0405-4dc7-8b9d-a7514e170c3b): Correct answer, but wrong when explaining about the property of exponent to use
* [1.8](https://chatgpt.com/share/bb445c4e-ffd7-41b6-a28d-65857d693dfe): States wrongly that if sqrt(n) = m for a composite n, then any non-trivial factor of n is less than or equal m. The correct qualifier should be "at least one of the factors"
* [1.9.c](https://chatgpt.com/share/8c8112da-0de8-4365-b98c-8d9e5f12c44a): The final answer is correct, but it commits early into trying to prove the wrong statement so it goes into a long rambling before finally coming to the correct conclusion.
* Tested up to 1.9

# Introduction to Linear Algebra 6th edition by Gilbert Strang

## Chapter 1 Exercises Solution Fail

* [1.1.1](https://chatgpt.com/share/293546e0-18f3-4ba5-98ea-f18f5697651b): Silently divides by 0. From d = mb, makes a wrong conclusion that d or b must be 0.
* [1.1.3.c](https://chatgpt.com/share/e605ac11-6023-4e9f-9b60-1fccdb241c62): Arithmetic fail when doing Gaussian Elimination. 1/2 * 2 becomes 0.
* [1.1.8](https://chatgpt.com/share/60cdd1b3-28f6-4b46-8f4f-c9eaefa1e2c4): Skipped the 1st question and directly jumped to the 2nd.
* [1.1.11](https://chatgpt.com/share/1223a00c-d565-44a5-a981-472cf1cef6fc): Found the correct vertices but cannot draw the parallelogram correctly.
* [1.1.14.a](): Gave a wrong model for a clock hand's coordinate. With the wrong model, 3:00 will point upwards.
* Tested up to 1.1.14

# A Walk Through Combinatorics 5th edition by Miklós Bóna

## Chapter 1 Quick Check Solution Fail

* [1.1.3](https://chatgpt.com/share/0293c1c3-e8e3-498f-a700-03c09eea7112): Brings up the pidgeonhole principle while the setup has pidgeons < holes
* Tested up to 1.1.3

## Chapter 1 Exercises Solution Fail


