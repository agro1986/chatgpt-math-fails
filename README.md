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

# Introduction to Linear Algebra 6th edition by Gilbert Strang

## Chapter 1 Exercises Solution Fail

* [1.1.1](https://chatgpt.com/share/293546e0-18f3-4ba5-98ea-f18f5697651b): Silently divides by 0. From d = mb, makes a wrong conclusion that d or b must be 0.
