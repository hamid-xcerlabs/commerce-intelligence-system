# Demo Scenarios

## Scenario 1: Product Discovery & Recommendation

Customer Message:

"I need a black dress for a wedding next month."

System Flow:

1. Customer message received through Instagram DM
2. Intent Classifier identifies a product inquiry
3. Customer requirements extracted
4. Query converted into embeddings
5. Pinecone semantic search retrieves best matching products
6. Inventory levels validated
7. Product Matcher selects the most relevant option
8. Personalized concierge response generated
9. Product card delivered through ManyChat

Outcome:

- Relevant product recommendation
- Real-time inventory awareness
- Personalized customer experience

---

## Scenario 2: Low Stock Opportunity

Customer Message:

"Do you have this dress in medium?"

System Flow:

1. Product identified through semantic search
2. Inventory validation performed
3. Low-stock threshold detected
4. Concierge response generated with urgency messaging

Outcome:

- Customer informed of limited availability
- Increased purchase urgency
- Reduced lost opportunities

---

## Scenario 3: Out-of-Stock Recovery

Customer Message:

"I love this style. Is it available?"

System Flow:

1. Product retrieved through Pinecone
2. Inventory check returns unavailable status
3. Alternative products evaluated
4. Concierge generates recovery response
5. Customer offered alternative recommendations

Outcome:

- Lost sale recovery
- Improved customer experience
- Alternative product discovery

---

## Scenario 4: Human Escalation

Customer Message:

"Can I speak with the owner about a bulk order?"

System Flow:

1. Intent Classifier detects human request
2. Conversation bypasses product recommendation workflow
3. Human escalation flag triggered
4. ManyChat notifies team

Outcome:

- Immediate human intervention
- Better handling of high-value opportunities

---

## Scenario 5: General Business Question

Customer Message:

"What are your store hours?"

System Flow:

1. Intent Classifier detects general inquiry
2. Product search bypassed
3. AI generates direct answer
4. Response delivered immediately

Outcome:

- Faster customer support
- Reduced staff workload

---

## Scenario 6: Follow-Up Recovery Automation

Customer Journey:

1. Customer receives product recommendation
2. No purchase occurs
3. System waits for configured period
4. Shopify order history checked
5. Purchase status evaluated

Decision:

Purchased:
- Workflow ends

Not Purchased:
- Follow-up message triggered automatically

Outcome:

- Recovery of abandoned opportunities
- Automated customer re-engagement
