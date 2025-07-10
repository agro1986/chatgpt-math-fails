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
* "HARD" label means that even after giving hints about what is wrong, the LLM still has difficulty revising its answer.
* ChatGPT chats with images cannot be shared. For those chats, I will link to a document in this repo where I copy pasted the chat.

## Recommendations

* If you are a student, you need to critically check ChatGPT's answers. It can still be useful to give you pointers in the right direction,
  such as asking "How do I prove x?" but you still need to check all details of the answer.
* If you are training LLMs, having a high-quality data of textbook problems and their correct solutions for training seems to be a low hanging fruit.

# A Concise Introduction to Pure Mathematics 4th edition by Martin Liebeck

## Chapter 1 Exercises Solution Fail

* [1.4](https://chatgpt.com/share/4c1c1419-97d4-469d-94ca-651db0a48586): (FIXED IN [o1-preview](https://chatgpt.com/share/66e3b81b-8e54-8012-861e-1b059bdfb9d6) [o3](https://chatgpt.com/share/686f4ebb-6380-8012-8868-57e00f68facd) [Gemini 2.5 Pro](https://g.co/gemini/share/91581b0832eb) [Sonnet 4 Deep Think](https://claude.ai/share/98cd6e2a-0989-4462-a431-1b5fa7296907) [Grok 4](https://grok.com/share/bGVnYWN5_2b36d9a9-b4e7-4ea0-95ef-baf9d7d154bf)) Thinking is correct but final conclusion not thorough. Says a → d and e, but doesn't realize that d and e each also implies the others
* [1.5.a](https://chatgpt.com/share/6ce350be-d4be-4bb7-8eb0-4e7cbc5a341b): ([FIXED IN o1-pro](https://chatgpt.com/share/678d1755-37ac-8012-9e6b-d8f362585103)) Wrongly interpreted A only if B as B → A, even though it should be A → B
* [1.5.e](https://chatgpt.com/share/99392bf9-0405-4dc7-8b9d-a7514e170c3b): Correct answer, but wrong when explaining about the property of exponent to use
* [1.8](https://chatgpt.com/share/bb445c4e-ffd7-41b6-a28d-65857d693dfe): States wrongly that if sqrt(n) = m for a composite n, then any non-trivial factor of n is less than or equal m. The correct qualifier should be "at least one of the factors"
* [1.9.c](https://chatgpt.com/share/8c8112da-0de8-4365-b98c-8d9e5f12c44a): The final answer is correct, but it commits early into trying to prove the wrong statement so it goes into a long rambling before finally coming to the correct conclusion.
* [1.11.a](https://chatgpt.com/share/8b670d2d-dfb0-4d08-bb02-79e946d8e9cd): Gives correct answer but wrong argument in 2 different places. "it contradicts the strictly increasing nature" should be "it contradicts the assumption that a_1 = 1". "Since a_3 must be defined as 6, our initial assumption breaks" is wrong, a_3 = 6 is consistent.
* [1.11.b](https://chatgpt.com/share/8b670d2d-dfb0-4d08-bb02-79e946d8e9cd): Argument not thorough. Did a trial in the form of "For simplicity, let's assign the next smallest values" and it indeed works, but didn't argue that it was the only possible answer.
* [1.11.c](https://chatgpt.com/share/8b670d2d-dfb0-4d08-bb02-79e946d8e9cd): (HARD) Logical jumps which derives a wrong formula, thus getting the wrong answer. Even after nudging, it still insists on the wrong answer.
* [1.11.d](https://chatgpt.com/share/8b670d2d-dfb0-4d08-bb02-79e946d8e9cd): (HARD) Futile to ask because fails on 1.11.c which is a special case easier one.
* Tested up to 1.11

# Introduction to Linear Algebra 6th edition by Gilbert Strang

## Chapter 1 Exercises Solution Fail

* [1.1.1](https://chatgpt.com/share/293546e0-18f3-4ba5-98ea-f18f5697651b): Silently divides by 0. From d = mb, makes a wrong conclusion that d or b must be 0.
* [1.1.3.c](https://chatgpt.com/share/e605ac11-6023-4e9f-9b60-1fccdb241c62): Arithmetic fail when doing Gaussian Elimination. 1/2 * 2 becomes 0.
* [1.1.8](https://chatgpt.com/share/60cdd1b3-28f6-4b46-8f4f-c9eaefa1e2c4): Skipped the 1st question and directly jumped to the 2nd.
* [1.1.11](https://chatgpt.com/share/1223a00c-d565-44a5-a981-472cf1cef6fc): ([o1-pro still fails, but can correct](https://chatgpt.com/share/678d1f75-b1b4-8012-aff8-30eeba64eaf3)) ([Solved by Claude 3.7 Thinking](https://claude.ai/share/4a603092-3b46-4693-b288-c3a08b8c439a) [Grok 4](https://grok.com/share/bGVnYWN5_8c493b7d-8338-47a7-ba3e-82f54cce66be)) (HARD) Found the correct vertices but cannot draw the parallelogram correctly.
* [1.1.14.a](https://github.com/agro1986/chatgpt-math-fails/blob/main/logs/introduction_to_linear_algebra_strang_1.1.14.a.md): ([Solved by Gemini 2.5 Pro experimental](https://g.co/gemini/share/60e01ab3c044)) (HARD) Gave a wrong model for a clock hand's coordinate. With the wrong model, 3:00 will point upwards.
* [1.1.14.b](https://github.com/agro1986/chatgpt-math-fails/blob/main/logs/introduction_to_linear_algebra_strang_1.1.14.a.md): Established θ_h = πh/6, but then calculated θ_2 = 2π/12.
* [1.1.15](https://github.com/agro1986/chatgpt-math-fails/blob/main/logs/introduction_to_linear_algebra_strang_1.1.15.md): (Solved by [Grok 4](https://grok.com/share/bGVnYWN5_9ced1ba4-e00a-421e-8c45-c8343567bc9c)) (HARD) First failed to understand the problem, then understood the problem but modeled it using the wrong formula.
* Tested up to 1.1.15

# A Walk Through Combinatorics 5th edition by Miklós Bóna

## Chapter 1 Quick Check Solution Fail

* [1.1.3](https://chatgpt.com/share/0293c1c3-e8e3-498f-a700-03c09eea7112): Brings up the pidgeonhole principle while the setup has pidgeons < holes.
* Tested up to 1.1.3

## Chapter 1 Exercises Solution Fail


