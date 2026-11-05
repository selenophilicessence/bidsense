# BIDSENSE: Complete Hackathon Project Blueprint



Project concept defined

PayPal + AI



[Meridian – Luxury Auction & Portfolio Dashboards by Ben Simmons — B2B SaaS & Dashboard Product Design on Dribbble](https://images.openai.com/static-rsc-4/SiIB6Jj5svYmI1FMyzgsX_2OYvSpmmiyFUwrRTxUy-_XLOVKajKjeLYOEHtv4-IobBlPSoYqNrgAZgvbXasn5Ryv9JyVlDv8a5_WgXAnefj9-09nb-R6PFCZMNr6UrgtI6mJqrCz0B2_PDFfs_HHu_M5tVTi4IMv0yFT2YPoDqQ?purpose=inline)

[dribbble.com](https://dribbble.com/shots/27389255-Meridian-Luxury-Auction-Portfolio-Dashboards?utm_source=chatgpt.com)

# BidSense

The intelligent auction marketplace for collectibles and rare items.

Know the value. Bid with intelligence. Buy with confidence.

We're building an auction marketplace specifically for collectibles, rare items and valuable second-hand finds.

The differentiator is that BidSense doesn't simply let people bid. It helps buyers understand what an item might be worth, identifies suspicious marketplace activity and helps buyers manage their bidding strategy.

Our central idea:

An AI-powered auction intelligence system with buyer-controlled automatic bidding and PayPal-powered checkout.

Let's turn this into something judges can actually use.

# 1. The problem we're solving

Collectibles markets have several problems:

| Problem                                      | Our solution              |
| -------------------------------------------- | ------------------------- |
| Buyers don't know an item's fair value       | AI valuation assistant    |
| Fake or misleading listings                  | AI listing risk detection |
| Buyers struggle to understand bidding trends | Bid intelligence          |
| Buyers miss auctions or lose track of bids   | Automatic bidding         |
| Buyers worry about payment                   | PayPal Checkout           |

### Our target users

- Collectors buying rare items.
- People selling vintage and collectible products.
- Hobbyists trading collectibles.
- Buyers who are new to auctions.

Our initial categories:

[Tavannes Chronograph  – Analog:Shift](https://images.openai.com/static-rsc-4/rKQSuToVWNtS58nqLojFrlKEBDWAKxqZ1NE0TIn1lOc5AVbTPHUO1l4yKXHq61SGqPpRhGCzJI2g7CMp4A_z9MuI7Coz8-d3erIpbgNNsj8sX3w-WjedtLRCqjzck9qw_COCu_wwwL96049xAOU5uhMw7Aevdw0ZgPdR-jJHHXk?purpose=inline)

Vintage watches

[What's New at the 46th National Sports Collectors Convention in 2026 - Athlon](https://images.openai.com/static-rsc-4/S2tHYb7xlfEz4r-YBifn4wbNUb6C_6L6t9-J0_IWGEVPkJpmu8RrFYFfDZnZK_cxUYyYTbxUq2N9OGgiFlEKDMydXJtJdWo6sfCqEEGrgQsiyLpevSNlEWY2jkCzpCFOsgMiC0pImUMS7jtQZouCiG30GwpFHEgFp8fl1u-e7Tc?purpose=inline)

Trading cards

[Out of the Woodwork: Important Coins Are Coming Out of Hiding](https://images.openai.com/static-rsc-4/bYPrYUVxdoqIL4hOQ5N9PHLDNoZHOOfJLroJ5LUC_L8X04r_d26K5TS_xhT19amEJ-7Bz-UbrfQylCpvKChf8E5gTGBgJI-bvOMrO_f7xpnyg7rDX2G9Z9SnuijSB7nuIGTKB7rJoRjjo-fAtpMrhMHi_jYmCqXxYEGkXQY1gX8?purpose=inline)

Rare coins

[French Antique Collectibles | FrenchVintageAntik](https://images.openai.com/static-rsc-4/I0GArAOOJcsIaAeKcuMW2vm4gUCukV8bYp4EA4wzxR_E6tUXsje0aOJEezLPJiD55hmeguGZaeGVocudRqxlHsXMbjfaLQKKZfGXOl_AfmDr-Ngl9LjDFfKiUKJ95jL3-sG6y62SkzNKUkxLeQ4pjDNymBDGyVqGArGP7W3sJCo?purpose=inline)

Art and antiques

For our prototype, we'll use a curated catalogue of sample collectibles rather than claim to authenticate every rare item.

# 2. The five core features

These are the features I want us to build.

## Feature 1: AI Smart Valuation

[Mobile App UI UX Design In Figma by Chelsea Rose 🦋 | Dribbble](https://images.openai.com/static-rsc-4/IMSduulgdfyXZkQ60h0K3Vn4pPqPo5b49V4pDwdu0maxDvdyhmm7FfRWC8UuO97xh4kLDLKCAkvEPDbZVFzsn_GHh2exx_w-s_EUp6zrN05iR0GOB5n2Yi_5-QodcJlAUDvKLm9hRpu7HdvZw3MJSOT0JB7A0_lg0jaMBuvUOMs?purpose=inline)

What happens?

A seller uploads an item's photographs and enters its details. AI analyses the available information and produces an estimated value range.

Example:

Vintage watch

Illustrative estimate

# ₹18,000–₹23,000

Estimated market range, not an authenticated appraisal.

- Condition: Good
- Category: Vintage watches
- Description: Seller-provided
- Confidence: Moderate
- Recommendation: Request provenance and condition evidence.

AI implementation:

- Image understanding.
- Text analysis.
- Comparison against a curated reference-price database.
- Estimated price range and confidence level.

Important: AI should distinguish between a visual estimate and verified market evidence. It must not invent comparable sales.

## Feature 2: AI Fraud Detection

[SaaS Fraud Detection Dashboard by Yuliya Lebedeva on Dribbble](https://images.openai.com/static-rsc-4/em2ojPP79l0JnVg-qMA97c4-mMzedHe6E0FC-1vSyY0VTOayrz3Om5MhofVciju8jkSpUhvnjA7khJdiYVRREWITmWbsN8yBGqz2Oc4ODl4AjU8fHErqblHR8J6eU7N_I3zgCu1GWSUWS6IYP45YHQdI2lYsSTQWs-HJuNTGHkY?purpose=inline)

What happens?

AI evaluates listings and bidding activity to flag potential warning signs.

Examples:

- Reused or inconsistent product photographs.
- Contradictory descriptions.
- Unusual listing prices.
- Repeated suspicious bidding patterns.
- Accounts exhibiting unusual activity.

Output:

Listing risk report

Risk assessment

Needs review

Illustrative demonstration

- Image and description inconsistencies detected.
- Provenance information missing.
- Listing requires additional verification.

  A risk flag is not proof of fraud. Human review is required.

## Feature 3: AI Bid Intelligence

[Remove A Maximum Bid | Auctria](https://images.openai.com/static-rsc-4/UMa8i5xIUpBEC0jh2ljBJknC8U9om0daB2Pqsm3esK_vEgY6QZwf1UXI5TwkdYGZGz3ga9bKoExPFp1Za0EZoybqNTT-bKsvSq2tZ40xUHMbOSldiCBjSHkxvRgpJ0-DZq2frTG9NScOwpU4JIH6mguQlyiLvoVTnjRjK82H9fg?purpose=inline)

What happens?

AI analyses auction history and explains bidding trends to the buyer.

It can:

- Summarize bidding patterns.
- Show how quickly prices are increasing.
- Identify unusual bid activity.
- Explain whether a current price is above the estimated valuation.
- Show remaining auction time.

Example:

> Bidding has accelerated during the last few minutes. The current price is approaching the upper end of the estimated value range. Consider your budget before increasing your maximum bid.

This is decision support, not a guarantee of winning or investment advice.

## Feature 4: AI-Assisted Automatic Bidding

Our standout interaction

This is where BidSense becomes more than an ordinary auction platform.

Buyers set:

- Maximum amount they're willing to pay.
- Their preferred bid increment.
- Their approval and spending limits.

The system automatically places eligible bids on their behalf, but never exceeds the buyer's configured maximum.

Example:

A collectible has a current bid of ₹5,000.

A buyer sets a maximum bid of ₹8,000.

The system:

1. Monitors new bids.
2. Calculates the next permitted bid.
3. Checks the buyer's maximum.
4. Places a bid only when the rules allow it.
5. Stops at ₹8,000.

Automatic bidding configuration

Example prototype settings

Current bid

₹5,000

Your maximum

₹8,000

Bid increment

₹500

Auto-bidding

Enabled

The buyer can pause or cancel automatic bidding at any time. It cannot override the configured limit.

For the prototype, we'll implement a deterministic bidding engine. AI can explain the bidding strategy, but AI itself will not be allowed to decide or bypass spending limits.

## Feature 5: PayPal Checkout

[Accepter des paiements en ligne et en personne | PayPal CA](https://images.openai.com/static-rsc-4/3Wev6Cmu-WsCslVG6xZn1iykE127FrQBlUSOWrJOyoruZqHLySXxPM721X01-XLI8oBVj3w7ce5gbWQTuRn3z_qdJKFEVTzNyrg6t85R_nnqmIAHV9SeD9pB7_ADzLHPdOYc8-6CpQwL7AECODFnHx6wETjAEauLCGbDAkXKPYU?purpose=inline)

What happens?

When an auction closes, the winning buyer gets a checkout option powered by PayPal.

Payment workflow:

1. Auction closes.
2. System identifies the eligible winner.
3. Backend creates a PayPal order.
4. Buyer approves checkout using PayPal Sandbox.
5. Backend captures the approved payment.
6. Transaction status updates.

We will use sandbox transactions, not real money.

# 3. Complete application structure

BidSense will have three main areas.

## BidSense application

Buyer dashboard

- Explore live auctions
- View recommended collectibles
- See AI valuation reports
- Monitor active bids
- Configure automatic bidding
- View won and completed auctions

  Seller dashboard
- Create collectible listings
- Upload product images
- Generate AI descriptions
- View valuation reports
- Monitor bids and auction performance

  Admin dashboard
- Review flagged listings
- Investigate suspicious bidding
- Manage users and auctions
- View payment status
- Review fraud reports

# 4. Technical architecture

Here's how the different parts communicate.

React frontend

Buyer · Seller · Admin interfaces

Python Flask backend

Authentication · APIs · Business logic · Permissions

AI engine

Gemini · Valuation · Fraud · Insights

Auction engine

Bidding · Limits · Timers · WebSockets

PostgreSQL

Users · Items · Bids · Transactions

PayPal API

Order creation · Approval · Capture

### Technology choices

| Layer           | Technology               | Purpose              |
| --------------- | ------------------------ | -------------------- |
| Frontend        | React + Tailwind CSS     | User interface       |
| Backend         | Python Flask             | Server and APIs      |
| Database        | PostgreSQL               | Persistent storage   |
| AI              | Gemini API               | Image/text analysis  |
| Realtime        | Flask-SocketIO           | Live auction updates |
| Payments        | PayPal Checkout REST API | Sandbox payments     |
| Deployment      | Render                   | Hosting              |
| Version control | GitHub                   | Source code          |

I recommend Python Flask because we can implement the AI and auction logic in Python without introducing too many unfamiliar technologies.

# 5. Database design

We'll need these main tables.

| Table         | Important fields                                                |
| ------------- | --------------------------------------------------------------- |
| users         | user_id, name, email, role                                      |
| items         | item_id, seller_id, title, description, condition               |
| valuations    | valuation_id, item_id, min_value, max_value, confidence         |
| auctions      | auction_id, item_id, start_price, current_bid, end_time, status |
| bids          | bid_id, auction_id, buyer_id, amount, timestamp                 |
| auto_bids     | buyer_id, auction_id, max_limit, increment, active              |
| fraud_reports | report_id, item_id, risk_level, explanation                     |
| transactions  | transaction_id, buyer_id, auction_id, paypal_order_id, status   |

Important database rule: Every bid must be validated by the backend. The database must never trust a bid amount just because the frontend submitted it.

For automatic bidding, we also need transaction-safe bid processing so simultaneous bids cannot accidentally exceed a buyer's limit.

# 6. How our AI will actually work

This is important for the judges. We need to explain what AI does technically, not just say we use Gemini.

AI module 1: Valuation engine

Multimodal AI

1. Receive product image and seller details.
2. Extract visible characteristics and condition clues.
3. Compare with available reference listings and price records.
4. Generate an estimated price range and confidence level.

AI module 2: Fraud detection

AI + rule-based analysis

- Detect inconsistent descriptions.
- Analyse repeated image patterns.
- Identify unusual bidding behaviour.
- Generate explanations for risk flags.

AI module 3: Bid intelligence

AI + statistical analysis

- Analyse bid history.
- Calculate bid frequency.
- Track price movements.
- Explain trends in natural language.

One technical decision: we'll combine AI with normal Python algorithms. We should not ask an LLM to calculate every bid or make security decisions.

### Automatic bidding logic

```
def automatic_bid(current_bid, max_limit, increment):    next_bid = current_bid + increment    if next_bid <= max_limit:        return next_bid    return None
```

This is just the basic calculation. Our real engine will additionally check auction status, buyer authorization, bid ordering, increments, concurrent requests and auction closing rules.

The AI assistant can explain the buyer's options, but cannot increase their maximum limit.

# 7. PayPal integration architecture

Mandatory hackathon integration

[The PayPal Integration Journey: A Guide to Sandbox Testing and Webhooks | by Ajoy Ashwinth | Dec, 2025 | Medium](https://images.openai.com/static-rsc-4/FofUeaBmRqhsgPHOSEMRDpgXu097LYjmw-gFWfnh7WAliSLLWxA8I21M1nSj6ucs7lDZPvWhW4e9Fm42HqsvMMYGOd3ze_VhcKixkPsTlDcLLrVZ0DIcvAdVDFS4AVYwRrURZAaWz0RZfbEsLAYJ4smHrtKn-ImVsqSD6C6e7hw?purpose=inline)

[medium.com](https://medium.com/%40ajoy.ashwinth/the-paypal-integration-journey-a-guide-to-sandbox-testing-and-webhooks-243a67081e5b?utm_source=chatgpt.com)

Our payment workflow:

```
Auction closes
      |
      v
Determine eligible winner
      |
      v
Create PayPal order
      |
      v
Buyer approves payment
      |
      v
PayPal processes sandbox capture
      |
      v
Verify capture on backend
      |
      v
Update transaction status
```

We'll use:

- PayPal Developer account.
- Sandbox business account.
- Sandbox personal buyer account.
- PayPal Orders API.
- Server-side order creation and capture.
- Webhook verification where supported.

Critical: We must never mark an order as paid just because the browser redirects to a success page. The backend must verify the payment with PayPal.

For our student prototype, all transactions will use sandbox funds. We'll avoid collecting real payment details.

# 8. MVP: What we will actually build

We have to be realistic. Five sophisticated AI modules plus an entire marketplace can become too much.

I suggest dividing the project into three levels.

Level 1: Essential MVP

Must build

- User registration and login
- Seller product listing
- Product catalogue
- AI valuation
- Auction creation and countdown
- Live manual bidding
- Automatic bidding with maximum limits
- PayPal sandbox checkout\

  Level 2: AI differentiation

  High priority
- AI fraud risk reports
- Bid intelligence dashboard
- AI auction assistant
- Seller listing generator\

  Level 3: Polish

  If time permits
- Admin dashboard
- Notifications
- Auction history charts
- Responsive mobile interface
- Improved product recommendations

The essential MVP must be functional before we spend time on animations, fancy dashboards or advanced AI.

# 9. Development roadmap

I'd organise our work into seven phases.

1. Phase 1: Foundation

   First

   Set up GitHub, React, Flask, PostgreSQL and environment variables.

   Deliverable: Working frontend connected to backend.
2. Phase 2: Marketplace

   Implement login, product uploads, product catalogue and seller dashboard.

   Deliverable: Users can list and browse collectibles.
3. Phase 3: Auction engine

   Implement auction creation, countdown, bid validation and real-time updates.

   Deliverable: Two test users can participate in the same auction.
4. Phase 4: Automatic bidding

   Implement buyer-configured maximum limits, bid increments and automatic bid execution.

   Deliverable: Automatic bidding works without exceeding limits.
5. Phase 5: AI intelligence

   Implement valuation, fraud analysis and bid insights.

   Deliverable: Three working AI demonstrations.
6. Phase 6: PayPal

   Integrate sandbox checkout, capture verification and transaction history.

   Deliverable: A completed sandbox purchase after an auction.
7. Phase 7: Submission

   Test, deploy, document, prepare GitHub repository and record demo.

   Deliverable: Public working prototype and under-three-minute demo video.

# 10. Seven-day execution plan

Since this is a hackathon, I would work backwards from submission rather than spend three days designing the interface.

| Day   | Main objective       | Expected result                |
| ----- | -------------------- | ------------------------------ |
| Day 1 | Setup + UI           | Frontend and backend running   |
| Day 2 | Marketplace          | Listings and product catalogue |
| Day 3 | Auction engine       | Working bidding                |
| Day 4 | Auto-bidding         | Buyer limits enforced          |
| Day 5 | AI features          | Valuation, fraud, bid insights |
| Day 6 | PayPal               | Sandbox checkout working       |
| Day 7 | Testing + submission | Deployment, GitHub and demo    |

If a feature takes longer than expected, prioritise a working end-to-end auction and payment flow over adding more features.

# 11. What judges should see in our demo

I want our demo to tell a story, not be a random tour of the website.

## The BidSense demo story

1. The seller lists a rare collectible.

   Show image upload, AI-generated description and estimated valuation.
2. The AI flags a suspicious listing.

   Show the risk report and explain why it requires review.
3. Two buyers enter the auction.

   Show the live bidding interface and price updates.
4. One buyer enables automatic bidding.

   Set a maximum amount and demonstrate the system respecting it.
5. The auction closes.

   Show the winning bidder and auction summary.
6. PayPal completes checkout.

   Demonstrate a successful sandbox payment and updated transaction status.

Strong end-to-end demonstration

# 12. Important risks we must handle

| Risk                       | Our safeguard                           |
| -------------------------- | --------------------------------------- |
| Incorrect AI valuation     | Show estimates, evidence and confidence |
| False fraud flags          | Human review                            |
| Automatic bid overspending | Strict server-side maximum              |
| Simultaneous bids          | Atomic database transactions            |
| Fake payment confirmation  | Server-side PayPal verification         |
| Auction manipulation       | Bid audit logs and anti-abuse rules     |

We should also have transparent auction rules, clear cancellation policies and no hidden automatic spending.

# 13. Our final project definition

# BidSense

PROJECT SUMMARY

An AI-powered intelligent auction marketplace for collectibles and rare items.

BidSense combines multimodal AI valuation, suspicious activity detection, bidding intelligence and buyer-controlled automatic bidding with PayPal-powered checkout.

Core differentiator: Buyers don't just participate in auctions. They receive AI-powered insights and tools to make more informed bidding decisions while retaining control of their spending.

Target hackathon categories

- Best Use of PayPal + AI
- Best Use of Agentic Commerce
- Most Creative
- Most Impactful

# 14. What we should do first

My recommendation is to freeze the scope above and start with the foundation.

Our first milestone should be:

1. Create the GitHub repository.
2. Set up React and Flask.
3. Connect PostgreSQL.
4. Build the BidSense landing page and dashboard.
5. Get the first product listing working.

One important rule for our development: We'll build one module at a time. I'll give you the code, explain what it does, help debug it and then move to the next module.

We should aim for a working product, not five half-finished AI features.

Want a focused BidSense development task every day at 6 PM, following this roadmap?

🚀Daily BidSense development tasksTap to set up# bidsense
