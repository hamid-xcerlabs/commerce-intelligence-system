# AI Decision Logic

## Overview

This document outlines how the system processes customer input and converts it into structured decisions.
The system uses controlled AI outputs within a deterministic workflow to ensure reliability and reduce hallucinations.
---

## 1. Intent Classification

The system categorizes incoming messages into:

- **product_query**
- **general_query**

### Purpose

- Route messages through appropriate logic paths
- Avoid unnecessary processing

---

## 2. Context Extraction

The system extracts relevant attributes such as:

- Size (e.g. small, medium, large)
- Style (e.g. )
- Product-related keywords, Tags
- Customer intent signals

---

## 3. Conditional Routing

- Product-related queries → product intelligence pipeline
- General queries → direct response generation

---

## 4. Product Matching Logic

The system evaluates:

- Product title and keywords
- Tags and categories
- Variant availability
- Inventory status

### Matching Strategy

- Prioritize relevance over position
- Avoid out-of-stock items
- Consider variant-level availability

---

## 5. Response Generation

The AI generates responses based on:

- Customer query
- Matched product data
- Brand tone guidelines

### Constraints

- Concise responses
- Human-like tone
- Context-aware messaging

---

## 6. Follow-Up Decision Logic

After initial interaction:

- System waits for a defined duration
- Checks purchase status via backend

### Outcomes

- Purchase detected → no action
- No purchase → trigger follow-up message

---

## 7. Design Principles

- Deterministic flow with AI assistance
- Controlled output via structured parsing
- Business outcome-focused decision making

---

## Summary

The AI layer is not used for random responses, but as a structured decision-making component within a controlled system architecture.
