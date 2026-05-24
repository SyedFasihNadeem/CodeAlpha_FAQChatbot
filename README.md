# CodeAlpha FAQ Chatbot

Task 2 of CodeAlpha Artificial Intelligence Internship.

## Live Demo
https://v0-internship-task-completion-swart.vercel.app/chatbot

## Project Description
A hybrid AI chatbot that combines classical Natural Language Processing with generative AI. It uses TF-IDF vectorization and cosine similarity to retrieve relevant context from a curated knowledge base, then synthesizes unique, conversational answers using Google Gemini.

## NLP Techniques Used
- Tokenization with handling of special tech terms (C++, C#, Node.js)
- Stop-word removal
- TF-IDF style word vectorization
- Cosine similarity matching
- Top-k context retrieval

## AI Generation
- Google Gemini 2.5 Flash via Vercel AI SDK
- Context grounding from retrieved FAQs
- Conversation history memory for natural follow-ups
- Up to 60+ FAQ entries in the knowledge base

## Features
- Smart retrieval-augmented answers
- Remembers previous turns ("tell me more", "give an example")
- Confidence and matched-context display
- Quick-suggestion chips
- Animated chat UI with typing indicators

## Tech Stack
- Next.js 16, TypeScript, Tailwind CSS
- shadcn/ui components
- Custom NLP implementation (no external NLP library)
- Vercel AI SDK + Google Gemini

## Full Source Code
The complete portfolio source code:
https://github.com/SyedFasihNadeem/CodeAlpha_AI_Internship

Key files:
- app/chatbot/page.tsx — Chatbot UI
- app/api/chat/route.ts — Hybrid NLP + AI logic
- lib/nlp.ts — Tokenization, TF-IDF, cosine similarity
- lib/faqs.ts — FAQ knowledge base

## Author
Syed Muhammad Fasih — CodeAlpha AI Intern
