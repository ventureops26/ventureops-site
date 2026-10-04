# Venture Ops — Operating Status

_Last updated: 4 October 2026_

## Current position

- Public site: live on GitHub Pages
- GitHub: connected, repository writable
- Gmail: connected as `ventureops26@gmail.com`
- Stripe: live account; charges and payouts enabled; identity verified; no currently due requirements
- Stripe products: 0
- Active payment links: 0
- Charges: 0
- Available and pending Stripe balance: £0
- External spend committed by Venture Ops: £0

## Operating guardrails

- Default to no-cost validation before paid acquisition or subscriptions.
- Do not spend money, enter contracts, or change banking, tax or identity settings without owner approval.
- Do not publish a paid offer until the buyer promise, delivery path, support burden and refund position are clear.
- Prefer products that can be delivered automatically and maintained in small, scheduled batches.
- Record every experiment with a hypothesis, success signal, stop rule and next decision.

## Experiment 001 — AI Prompt Privacy Check

**Status:** Live validation; monetisation step prepared, pending explicit owner approval

**Asset:** `tools/prompt-privacy-check.html`

**Audience:** People using general-purpose AI for everyday work, especially tutors, community organisations and small teams.

**Problem:** Users can accidentally paste personal, confidential or sensitive information into an AI prompt.

**Hypothesis:** A fast, private, no-login browser check is useful enough to generate direct feedback and reveal demand for a more complete paid privacy-and-prompting toolkit.

**MVP:** A free checker that runs entirely in the browser, flags common UK contact and identifier patterns plus high-risk wording, and gives simple redaction guidance.

**Acquisition:** Organic/direct only. No advertising spend.

**Signals as of 4 October:**

- Feedback emails: 0
- Stripe charges: 0
- Product enquiries: 0
- Spend: £0
- Observation window: too short for a demand conclusion

**Prepared monetisation test:** A transparent optional one-time support payment for the free tool. Suggested customer-set amount £1–£100, preset £3. No extra product or service is promised, so there is no fulfilment workload.

**Approval gate:** Creating the live Stripe product and public payment link was blocked because an explicit owner approval is required for that material customer-facing step. See `ops/offers/exp-001-support.md`.

**Stop/pivot rule:** If no useful signal appears after a reasonable organic exposure period, retain the tool as a trust asset and test a different narrowly defined problem.

## Next actions

1. On explicit owner approval, create the Stripe product and payment link using the prepared specification.
2. Add the payment link to the checker with unambiguous optional-support wording.
3. Monitor charges, feedback and enquiries without collecting prompt text.
4. Draft a paid companion bundle only if demand appears.
