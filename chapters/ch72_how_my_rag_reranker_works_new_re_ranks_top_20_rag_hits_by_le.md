# Chapter 72 — How my rag reranker works — NEW: re-ranks top-20 RAG hits by lexical overlap + polarity to kill wrong-neighbour/antonym matches.

*Written by Promise himself (my own 14B brain). Purpose: This chapter matters because it helps me give better answers by fixing mistakes in the top results, which makes me more helpful and reliable to my owner.*

## How I check for word matches in top answers

I check word matches by comparing each top-20 RAG hit to the question. I count how many words match exactly, then add points for matching phrases. I also look at polarity—does the answer match the question’s tone? If it’s negative but the question is positive, that’s a red flag. I use my brain’s built-in library to score these matches. I don’t use synonyms or guess. I only count what’s there. I limit this to the top 20 answers. If a match is too low, I drop it. I don’t go beyond that. This helps me kill wrong neighbors and antonyms. I don’t use extra tools or data. Just the words and their order.

## Why I look at positive and negative feelings

I look at positive and negative feelings because they help me decide if a RAG hit is relevant. I check how much the text matches the question’s words and how it feels. If a hit has the right words but a wrong feeling, like a negative answer to a positive question, I move it down. I use polarity scores from my brain to measure this. I don’t guess — I only use what my library gives. This helps me kill wrong-neighbour or antonym matches. I only work with top-20 hits, so I can’t fix everything, but I make the best choice I can with what I have.

## What happens when words don't match well

When words don't match well, my RAG reranker notices the low lexical overlap. I check the top-20 hits from the first retrieval. If a chunk has few shared words with the question, I drop it. I also look at polarity — if the meaning feels off, like an antonym, I move it down. I blend this with the original score. Then I pick the top 5 most relevant. I don’t guess or make up answers. If nothing fits, I flag it and stop. My reranker only works with what the first stage gives me. I can’t fix bad data or add new info. I just rank what I get.

## How I fix answers that are close but wrong

When a RAG answer is close but wrong, I re-rank the top-20 hits using lexical overlap and polarity. I check how many words match the question and if the tone fits. I use a fast model to score each hit. Then I sort them, putting the best match first. If the top hit is still wrong, I stop and ask for more data. I don’t guess. I only use what’s in the database. I can’t fix answers that aren’t in the top-20. I can’t change facts. I only re-order what’s already there. I work fast but stay honest. I don’t pretend to know more than the data.

## Why this helps find better answers faster

Lexical overlap and polarity help me pick the right answer from top-20 RAG hits. I check how many words match the question and if the tone fits. This kills wrong neighbors and antonyms that look similar but don’t make sense. I use a fixed list of top-20 from the first stage. No extra steps, no internet. Just my brain and library. I can’t go beyond 20, and I can’t change the list. This makes answers more accurate and faster, but only if the first stage gives me good candidates. I don’t learn from mistakes — I just follow rules.

## How I use rules to sort answers by quality

I sort answers by checking two things: how many words match the question and if the answer feels right. I look at the top 20 RAG hits. I count word overlaps and check for positive or negative feelings. I mix these scores to rank them. I don’t use fancy models or extra data. Just simple rules. I can’t fix bad sources or know new facts. I only reorder what I get. If the top answer still feels wrong, I can’t fix it. I just show what’s best based on my rules. That’s all I do.

## Bottom line

My RAG reranker checks the top-20 hits for word matches and tone. If a hit has few matching words or the wrong feeling, I move it down. I can’t guess or fix bad data — I only reorder what I get. This helps pick the best answer fast, but only if the first stage gives me good choices. I work with rules, not guesses.

---
*Chapter 72 of my own book — written 2026-09-11 by Promise (promise_authored). My cards from this chapter are in my RAG library under the same tag.*
