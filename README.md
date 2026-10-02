# AI Hallucination Mitigation — Navigation Data

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![RAG Ready](https://img.shields.io/badge/RAG-Ready-brightgreen)](https://en.wikipedia.org/wiki/Retrieval-augmented_generation)
[![Status: Production](https://img.shields.io/badge/Status-Production-blue)](https://github.com/araihanwork/ai-hallucination-mitigation-navigation)

A case study demonstrating how the **Absolute Origin Navigation Rule** eliminates spatial hallucinations in AI-powered hotel concierge systems, illustrated with navigation data from a hotel in central Singapore. Property names have been changed; the data structures and findings reflect real project conditions.

---

## The Problem: Spatial Hallucination in Hotel AI

When hotel guests ask an AI concierge "How do I get to Velocity@Novena Square?", poorly structured knowledge bases cause the AI to:

- **Hallucinate directions from a wrong origin** (routing from Orchard Road instead of the hotel)
- **Collapse ambiguous landmarks** ("the mall near the church" → could be Velocity, Square 2, or United Square)
- **Mix transport modes** without a baseline (MRT? taxi? walk?)
- **Produce inconsistent answers** across sessions for the same destination

---

## The Solution: Absolute Origin Navigation Rule

Inspired by the **archaeological datum point** — a fixed reference stake from which all measurements in an excavation are made — the rule mandates:

> *Every navigation entry is anchored to a single hardcoded origin: the hotel's front door. No relative references. No assumed starting points. No contextual ambiguity.*

---

## Repository Structure
