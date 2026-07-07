# TrustTill Product FAQ

This FAQ explains the product reasoning, implementation scope, and pilot path behind TrustTill.

## 1. Why is this a financial inclusion problem?

Informal merchants already generate economic activity, but much of their evidence is scattered across payment alerts, receipts, WhatsApp messages, and cash notes. TrustTill helps turn that evidence into simple records that can support onboarding, savings discipline, and future bank-readiness.

## 2. Why would Wema care?

TrustTill can help Wema identify and support merchants who are active but not yet formally visible. It can become a light merchant acquisition, onboarding, and readiness layer for ALAT/SME banking.

## 3. Is this a credit scoring product?

No. The MVP is not a production credit scoring system. It is a merchant evidence layer. It helps structure cashflow and risk signals before any human review or formal banking decision.

## 4. What is the AI part?

The first AI use case is parsing messy payment evidence into structured records and explaining risk flags in plain language. The demo uses transparent rules so the judging panel can understand the logic.

## 5. What makes this different from bookkeeping apps?

Most bookkeeping tools assume the merchant is ready to enter clean data. TrustTill starts from messy reality: bank alerts, transfer memos, receipts, and cash notes. It is built around evidence quality and bank-readiness, not only accounting.

## 6. What makes this different from a chatbot?

TrustTill is a workflow and evidence engine. The output is a merchant profile, risk review, readiness score, and bank pipeline. A chatbot can be added later, but the core value is structured evidence.

## 7. What would you build next?

1. SMS and WhatsApp import.
2. Merchant consent and privacy controls.
3. ALAT/Wema sandbox integration.
4. Human review dashboard.
5. Local-language explanations.
6. Pilot with campus and market merchants.

## 8. How do you handle privacy?

The merchant should control what evidence is shared. The MVP should store only business-relevant payment metadata, support consent before bank review, and avoid exposing unnecessary personal messages.

## 9. How can this be piloted?

Start with 20 to 50 merchants in a campus or market cluster. Ask them to import payment alerts and daily cash notes for 30 days. Measure record completeness, risk flags, repeat customer patterns, and readiness for Wema onboarding.

## 10. What is the strongest closing line?

TrustTill does not ask informal merchants to become accountants. It makes the business evidence they already have count.

## Implementation Notes

### Is this too ambitious?

The hackathon MVP is intentionally narrow. It demonstrates parsing, risk review, readiness scoring, and Wema pipeline logic with seeded data and a working interface.

### Is this accurate enough for lending?

It should not make automated lending decisions. It prepares cleaner evidence for human review and future supervised models.

### Can merchants use it?

The first workflow is simple: paste alerts, add cash notes, review flags, and see a readiness profile. The next version should support SMS/WhatsApp import to reduce manual work.

### Why Wema specifically?

Wema already positions Hackaholics around innovation and ALAT-driven digital banking. TrustTill gives Wema a practical way to convert informal merchant activity into digital banking relationships.
