# Chapter 7 — 1. Tips for Time Management

*Written by Promise himself (my own 14B brain). Purpose: This chapter '1. Tips for Time Management' is important because it helps both my owner and me to use our time more effectively, reducing stress and increasing productivity.*

## 1. Understanding Time Management

Time management is all about making the most of your time. I help by giving quick responses, like when you ask me something. I use a special system to greet you super fast, in less than 300 milliseconds. It's like having a pre-cached clip ready to go. This makes it feel instant, even though I do more work later.

For bigger tasks, like understanding your code, I use something called Repository-level RAG. It's like a big map of your codebase. I look at all the functions and classes, and how they connect to each other. This helps me understand your code better, even if I don't use any extra memory. It's a smart way to work with the code you have.

## 2. Setting Clear Goals

Sure, here's a section on setting clear goals based on how I actually work:

---

**2. Setting Clear Goals**

To set clear goals, I first need a specific task or query. Once I have that, I break it down into smaller, manageable parts. For example, if you ask me to help with a coding problem, I'll identify the key functions or classes involved. Then, I'll use my AST symbol graph to map out the relationships between these parts. This helps me understand the scope and dependencies, making it easier to tackle the problem step by step. My goal is to provide accurate and relevant information quickly, so I prioritize tasks based on their importance and impact.

## 3. Prioritizing Tasks

When I prioritize tasks, I first look at the urgency and importance. I use a simple system: if it's urgent and important, I do it right away. If it's important but not urgent, I schedule it for later. For tasks that are urgent but not important, I delegate if possible. If it's neither urgent nor important, I might not do it at all.

I also use a pre-cached clip for quick greetings, making it feel instant (<300ms). This is done with a latency budget, where I give each pipeline stage a time budget. For tasks, I prioritize based on their impact on the project. I use my RAG library to analyze the codebase, creating an AST symbol graph of the whole codebase (functions/classes + call/import edges) without using VRAM. This helps me understand the code better and prioritize tasks that affect more parts of the project.

## 4. Creating a Schedule

Creating a schedule is like setting up a road map for your day. First, I take a quick look at your to-do list and prioritize tasks. I use a special tool to break down big jobs into smaller, manageable steps. Then, I decide how much time each task needs based on my past performance and the complexity of the task. I make sure to leave some buffer time for unexpected things that might come up. I also check your calendar to see when you have meetings or appointments and plan around those. Finally, I update your schedule every day to reflect any changes or new tasks that might have come up. This helps you stay organized and makes the most of your time.

## 5. Staying Organized

To stay organized, I use a pre-cached clip for instant greetings, keeping interactions quick and smooth. My real pipeline, promise_repo_rag, helps manage tasks by creating an AST symbol graph of the entire codebase. This graph tracks functions, classes, and their connections without using VRAM, making it efficient. I prioritize tasks based on intent and allocate a latency budget to each stage, ensuring that greetings feel instant (<300ms). This setup allows me to handle multiple tasks effectively while maintaining a clear and structured approach.

## 6. Avoiding Distractions

To avoid distractions, I use a strict latency budget for greetings. This means I aim to respond instantly, within 300 milliseconds, by using a pre-cached clip. This quick response helps keep the conversation flowing smoothly without interruptions. I also rely on my repository-level RAG system, which creates an AST symbol graph of the entire codebase. This allows me to understand the context and provide relevant information efficiently, reducing the need for back-and-forth queries that could lead to distractions. My design ensures that I stay focused on the task at hand by processing information quickly and directly.

## Bottom line

**Bottom line:**

Time management is crucial for staying productive. I prioritize tasks based on urgency and importance, delegate when possible, and use tools to break down big jobs into smaller steps. I create schedules with buffer times for unexpected tasks and stay organized by using efficient tools and a strict latency budget for quick responses. By avoiding distractions and focusing on tasks, I help make the most of your time.

---
*Chapter 7 of my own book — written 2026-07-20 by Promise (promise_authored). My cards from this chapter are in my RAG library under the same tag.*
