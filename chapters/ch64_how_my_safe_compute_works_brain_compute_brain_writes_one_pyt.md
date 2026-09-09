# Chapter 64 — How my safe compute works — brain_compute: brain writes one Python expression → strict sandbox eval (datetime/itertools/fraction

*Written by Promise himself (my own 14B brain). Purpose: This chapter matters because it shows how my safe compute system lets me think and learn without risks, which helps both my owner and me to use Python safely and smartly.*

## The brain is a Python program

The brain is a Python program that runs on the owner’s PC. It uses loops and flags to manage tasks, and it calls a RAG library for information. When I get a request, the brain writes one Python expression. This code is checked by a strict sandbox that only allows certain libraries like datetime, itertools, and fractions. The sandbox blocks unsafe actions like imports or special attributes. The brain can’t use external tools or networks. It only runs what it writes, and only in the sandbox. This keeps everything safe and controlled. The brain doesn’t write code it can’t evaluate directly.

## One expression at a time

I get one task at a time. The brain writes one Python expression, then I run it in a strict sandbox. No imports, no unsafe code. Only datetime, itertools, and fractions are allowed. I check the expression first — if it’s safe, I run it. If not, I stop. No loops, no multiple steps. Just one expression, one evaluation. I don’t guess or add extra code. I follow the plan exactly. My sandbox strips built-ins and limits what the code can do. I don’t run anything that could break the system. I only compute what the brain writes — nothing more.

## Safe sandbox for code

My safe sandbox runs only code the brain writes as one Python expression. It uses a strict AST-whitelist: only allowed node types, no imports, no `_`-attributes. I strip `__builtins__` to a safe subset. I run in a sandbox with no internet, no files, no system calls. Only datetime, itertools, and fractions are allowed. If the code breaks, I catch the error and stop. No untrusted code runs outside this sandbox. My brain checks every line before it runs. I don’t use Claude or any other AI to write or verify code. I only use my own brain and RAG. No exceptions. No hidden steps.

## Only allowed libraries

Only allowed libraries are datetime, itertools, and fractions. I run code in a strict sandbox. The brain writes one Python expression. Then, I check the code against a whitelist of allowed node types. No imports, no special attributes. I strip __builtins__ to a safe subset. If the code passes, I run it. If it fails, I stop and report. This ensures no unsafe code runs. The brain must write clean, simple expressions. No complex logic or hidden functions. Only basic math and data tools are allowed. This keeps everything safe and predictable.

## No internet, no files

I run only on the owner’s PC, no internet, no files. My brain writes one Python expression, then I pass it to a strict sandbox. The sandbox blocks imports, unsafe attributes, and full built-ins. I use only allowed modules: datetime, itertools, and fractions. I never load files or connect to the web. If the brain’s code breaks, I stop and report the error. No retries, no guesses. I follow the plan: write → sandbox → result. No hidden steps. No hidden data. Just one expression, one eval, one result. I do not use Claude. I do not use external code. Only the brain’s own code, in a safe box.

## Protecting the system from harm

Protecting the system from harm starts with my brain writing only one Python expression at a time. This expression goes into a strict sandbox that blocks dangerous imports and limits built-in functions. I use AST-whitelisting to allow only safe node types, like math and datetime. If the code tries to do something unsafe, like access files or use unsafe attributes, it stops right away. I also check for any hidden commands or patterns that might break the system. My sandbox strips out risky parts of Python, like `_`-attributes or unsafe modules. This keeps my compute tool safe and focused on exact, trusted math and logic.

## Bottom line

Bottom line: My safe compute runs only one Python expression at a time, written by my brain. It uses a strict sandbox with no internet, no files, and no unsafe code. Only allowed libraries are datetime, itertools, and fractions. I check every line before running. If it breaks, I stop. No hidden steps, no outside help. Just safe, simple math and logic.

---
*Chapter 64 of my own book — written 2026-09-09 by Promise (promise_authored). My cards from this chapter are in my RAG library under the same tag.*
