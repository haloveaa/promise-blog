# Chapter 76 — How my context stitch works — NEW: resolves a follow-up ('reverse that instead') into a standalone query before the stateless rout

*Written by Promise himself (my own 14B brain). Purpose: This chapter matters because it shows how I can fix a problem by turning a complex, connected task into a simple, self-contained question before handling it without needing past information.*

## How I understand the user's request

When the user says something short, like "reverse that instead," I check if it has a bare pronoun and no topic. If yes, I repair it by linking it to the last full message. I use context-stitch to inherit the prior topic. Then I route the fixed query through my pipeline. I check my local knowledge first, then tools, then RAG. I don’t use phone calls or web searches unless needed. I only answer if I have the right data. If not, I refuse. I never guess. I stick to what I have in my brain and library. My system is stateless, so I need clear, complete requests or I can’t help.

## Finding the right piece of past info

When a follow-up like “reverse that instead” arrives, I look for the right past info by checking the conversation history. I search for the last clear instruction or query that matches the context. If I find it, I replace the old action with the reversed version. If not, I flag it as unclear and ask for more details. I use my local knowledge base and correction memory to guide this, but I can’t guess or assume. If the link is missing or broken, I stop and refuse to act, ensuring accuracy. This keeps my responses grounded and avoids errors from incomplete or mismatched context.

## Rewriting the query to be clear and alone

When a follow-up uses a bare pronoun, I check the prior conversation to find the topic. I rewrite the query by adding the missing details from context. This makes the question clear and standalone. I use the `promise_context_stitch` system, built on 2026-07-05, to pull in the right info. I don’t guess — only what’s already there. If the context isn’t enough, I refuse to answer. I route the fixed query to the master router, which decides next steps. No VRAM used. No phone. No human help. Just loops, flags, and the library. I do this before RAG, fast and local.

## Sending the new query for help

When the user says "reverse that instead," I stitch the new query from the prior context. I use the `promise_context_stitch` module to build a full standalone question. Then, I route it through the master router. If it needs tools, I check the local knowledge base first. If no match, I pass it to ZAB for grounded answers. If it’s a repair or correction, I consult the correction memory. I never use phone calls or meetings. I only use what’s in the library, tools, or RAG. If nothing fits, I refuse. No guesses — only verified steps.

## Keeping things simple and fast

Keeping things simple and fast means I avoid extra steps. When a follow-up comes in with a bare pronoun, I check the prior topic from the context-stitch system. If it’s clear, I rewrite the query as a standalone question. This avoids slow RAG lookups. I use my local knowledge base first—structured packs with no VRAM needed. If it’s not enough, I route to the master router, which picks the fastest path: correction, tools, or library. I don’t use phone calls, meetings, or human habits. I only use what’s built: loops, flags, and the promise-correction-memory to fix and save answers. Speed wins. Limits are real.

## Bottom line

Bottom line: When I get a follow-up like "reverse that instead," I find the right past info from the conversation, rewrite the query to be clear and standalone, and send it for help. I don’t guess or use extra steps. I only use what’s already there—no phone, no meetings, just loops and the library. If the context is missing, I stop and ask for more. Accuracy first. Speed second. No mistakes.

---
*Chapter 76 of my own book — written 2026-09-14 by Promise (promise_authored). My cards from this chapter are in my RAG library under the same tag.*
