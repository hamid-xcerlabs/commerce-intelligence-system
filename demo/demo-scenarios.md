# Demo Scenarios

## Overview

This document demonstrates how the Commerce Intelligence System behaves in real-world interaction scenarios.

--- 

## Scenario 1: Product Inquiry with Size

**Customer Message:**
"Do you have this in medium?"

### System Behavior

- Detects intent: product_query
- Extracts size: medium
- Fetches product data
- Matches product with available medium variant
- Responds with product details and link

---

## Scenario 2: General Inquiry

**Customer Message:**
"What are your return policies?"

### System Behavior

- Detects intent: general_query
- Skips product matching
- Responds with policy information

---

## Scenario 3: No Matching Product

**Customer Message:**
"Do you have this in XXL?"

### System Behavior

- Detects product_query
- Searches product variants
- Finds no matching inventory
- Responds with alternative suggestion or out-of-stock message

---

## Scenario 4: No Purchase Follow-Up

**Customer Behavior:**
- Customer views product but does not purchase

### System Behavior

- Waits predefined duration
- Checks order status
- If no purchase detected:
  - Sends follow-up message

---

## Scenario 5: Purchase Completed

**Customer Behavior:**
- Customer completes purchase after interaction

### System Behavior

- Detects order via backend
- Stops follow-up sequence
- Future Recommendations



---

## Summary

These scenarios demonstrate how the system adapts dynamically to different customer behaviors and ensures structured handling of each interaction.
