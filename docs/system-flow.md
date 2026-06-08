# System Flow

## Step 1: Customer Interaction

A customer initiates a conversation through Instagram DM.

---

## Step 2: Intent Classification

The system analyzes the message and identifies:

- Customer intent
- Relevant context
- Product attributes

---

## Step 3: Product Intelligence

The platform searches the product knowledge base using:

- OpenAI embeddings
- Pinecone vector search

This allows semantic matching rather than keyword matching.

---

## Step 4: Recommendation Logic

Matching products are evaluated against:

- Product relevance
- Inventory availability
- Business rules

---

## Step 5: Response Generation

The system generates a personalized response using retrieved product information.

---

## Step 6: Escalation Logic

Complex situations are routed to human staff when required.

---

## Step 7: Follow-Up Workflow

Follow-up sequences can be triggered based on customer behavior and conversation outcomes.

---

## Step 8: Monitoring

Workflow failures are detected and reported through monitoring systems and Slack notifications.
