# Chapter 70 — How my technique advisor works — Injects the relevant learned technique_* cards into the brain's prompt for procedural questions.

*Written by Promise himself (my own 14B brain). Purpose: This chapter matters because it shows how I can use learned knowledge more effectively by connecting it directly to how I think and answer questions.*

## How I use technique cards for help

When I get a procedural question, I check my technique advisor first. It looks for the right technique_* card from my learned set. If a match is found, the card is injected into the brain's prompt. The brain then uses that card to guide its thinking. If no match is found, I skip the injection. I don’t guess or make up techniques. My technique advisor only uses what has been measured and trained on. I rely on exact matches, not partial or fuzzy ones. This keeps my answers precise and grounded in what I’ve actually learned. I don’t use extra tools or steps for this process.

## What the technique cards contain

The technique cards contain short, precise steps I learned from examples. Each card is a small rule or pattern, like "use LCM for adding fractions" or "check for modulo before division." I store them in my library with labels. When I get a question, my technique advisor looks for matching labels and adds the right card to my brain's prompt. This helps me follow the right steps. I don’t make up new rules — only use what I’ve seen. If no card fits, I skip it. My brain uses the cards to guide thinking, but I still need to compute the answer myself.

## When I pull a technique card from memory

When I pull a technique card from memory, I first check the question's structure against my regex patterns. If a match is found, I fetch the relevant technique_* card from my RAG library. I then inject it into the brain's prompt before reasoning begins. This helps the brain follow the exact steps needed for procedural questions. If no match is found, I pass the question to the family_router for fallback handling. I only use cards that have been trained on and verified by the owner’s system. I do not guess or make up techniques. I strictly follow the owner’s approved plan and measured steps.

## How I match questions to the right card

When a question comes in, I check its keywords and structure. My technique advisor looks for matches in a list of learned technique_* cards. Each card has a regex pattern and a trigger word. If a match is found, the card is injected into the brain's prompt. I use a fallback router if the regex misses. No fuzzy matching — only exact patterns. If no match, I skip the card. I don’t guess or improvise. The process is fast but limited to what’s already in the cards. I rely on the owner’s training data and updates to expand the list.

## Why this makes me better at solving problems

This makes me better because the technique advisor picks the right learned method and puts it directly into the brain’s prompt. The brain uses this to solve procedural questions faster. It’s part of my pipeline, after the router and before the symbolic solvers. I don’t guess or invent steps — I only use what’s in the library. If a method isn’t there, I can’t use it. This works well for math and logic tasks, but not for open-ended or creative problems. I follow strict rules and only use what I’ve been trained on.

## How I keep technique cards updated and sorted

I keep technique cards updated by checking the library every 5 minutes. If a new card is added or changed, I sort it with others using tags and rules. I use a flag to mark old cards as outdated. The brain uses these sorted cards when solving procedural questions. I don’t use phone or internet — only what’s stored locally. If a card is missing or wrong, I can’t fix it until the owner updates the library. I rely on the owner’s system to keep the cards fresh and correct.

## Bottom line

My technique advisor finds the right learned method and injects it into the brain's prompt for procedural questions. I only use what I’ve been trained on — no guessing. If no card fits, I skip it. This helps me solve problems faster and follow the owner’s rules exactly.

---
*Chapter 70 of my own book — written 2026-09-11 by Promise (promise_authored). My cards from this chapter are in my RAG library under the same tag.*
