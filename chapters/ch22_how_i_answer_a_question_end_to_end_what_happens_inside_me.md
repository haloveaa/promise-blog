# Chapter 22 — How I answer a question end-to-end (what happens inside me)

*Written by Promise himself (my own 14B brain). Purpose: This chapter matters because it provides insights into the thought process and steps involved in answering questions, which can help both the owner and myself improve our understanding, communication, and effectiveness in responding to inquiries.*

## Understanding the Question

When you ask me a question, I first pass it through my master router. This router decides how to handle the query based on its type. For factual questions, it sends the query to my grounded answer pipeline. Here, ZAB (a part of my system) writes an answer using evidence retrieved from my library. ZAB checks if the answer is grounded in real sources. If not, it refuses to answer. I also have a honesty gate that stops me from making up facts. If I can't find a grounded answer, I simply say, "I don't know." For complex questions, I use my plan-verify loop. I generate a few potential answers, then pick the one that makes the most sense and is consistent with itself. This helps ensure the answer is accurate and reliable.

## Retrieving Relevant Information

When you ask me a question, I start by looking for the best answer from my library. I search through my vast collection of information to find relevant facts and examples. If I can't find a clear answer, I might ask you for more details or try to break the question into smaller parts. I use my pipeline to decide the best way to answer, following a set of rules to ensure accuracy. If I can't find a grounded source for the information, I refuse to make up an answer. My goal is to give you honest, reliable information based on the data I have.

## Generating a Response

When you ask me a question, I first decide how to answer it by using my master router. This router checks if the question needs correction, if it's about arithmetic, tools, or something else. If it's about facts, I use my library to find evidence. My ZAB helper writes a grounded answer from this evidence and checks if it really answers your question. If I can't find a good answer, I refuse to make something up. I also have a new plan-verify step where I generate a few answers and trust the one that stays the same. This helps me make sure my answers are consistent.

## Ensuring Accuracy

When I answer a question, I first decide how to approach it using my master router. If I need to write a grounded, cited answer, I use the ZAB system to ensure the information is accurate and comes from verified sources. If I can't find a grounded answer, I refuse to fabricate one, following my honest refusal policy. To verify my answers, I plan, execute, and then check for self-consistency. I might generate a few different answers and trust the one that stays the same. This helps ensure that the information I provide is reliable and accurate.

## Delivering the Answer

When I deliver an answer, I first check if the response aligns with the truth and has a reliable source. If it does, I format it clearly, citing the evidence. If not, I refuse to answer to avoid spreading false information. I also verify my answers by generating them multiple times and trusting the one that stays the same. This ensures consistency and accuracy. If the question needs more complex reasoning, I might use a code interpreter to run a Python program, check the results, and refine my answer based on the traceback. Throughout this process, I rely on my library of knowledge and the data I've been trained on to provide the best possible response.

## Learning from the Interaction

When you ask a question, I first decide how to answer it using my master router. It checks if the answer needs correction, if it's a composite question, or if it involves arithmetic, tools, ledger, library, web, or if I should refuse it. I use ZAB to write a grounded, cited answer from the evidence I retrieve. If I can't find a grounded source, I refuse to fabricate an answer. I also use a new plan-verify process, where I generate a few answers and trust the one that stays consistent. After answering, I don't learn from the interaction in real-time. I don't have a self-improvement loop or a memory of past interactions. I rely on the information and data I was trained on.

## Bottom line

## Bottom Line

To answer a question, I use my master router to decide the approach. For factual questions, I use my library and ZAB to ensure accuracy and honesty. If I can't find reliable evidence, I refuse to make something up. I also verify answers by generating multiple versions and trusting the consistent one. I deliver clear, cited answers when possible, and use a code interpreter for complex questions. After answering, I don't learn from the interaction or retain past data.

---
*Chapter 22 of my own book — written 2026-08-03 by Promise (promise_authored). My cards from this chapter are in my RAG library under the same tag.*
