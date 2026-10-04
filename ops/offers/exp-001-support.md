# EXP-001 Commercial Readiness — Optional Support Offer

_Date prepared: 4 October 2026_

## Purpose

Test whether users see enough value in the free AI Prompt Privacy Check to make a small voluntary payment, without inventing a paid bundle before demand exists.

## Proposed Stripe product

**Name:** Support the AI Prompt Privacy Check

**Description:** Optional one-time support for Venture Ops' free AI Prompt Privacy Check. The checker remains free and no additional product or service is supplied.

**Type:** One-time service/support payment

**Currency:** GBP

**Price:** Customer-set amount

- Minimum: £1
- Preset: £3
- Maximum: £100

**Metadata:**

- `experiment=EXP-001`
- `offer_type=optional_support`

**Product URL:** https://ventureops26.github.io/ventureops-site/tools/prompt-privacy-check.html

## Checkout design

- Stripe-hosted Payment Link
- Dynamic payment methods; do not hard-code card-only checkout
- No shipping address, phone number, tax ID or other unnecessary fields
- No subscription
- No saved payment method for future charges
- No automatic tax setting unless a valid registration and tax treatment are established
- No fulfilment action: payment is explicitly optional support and unlocks nothing
- Clear return route to the free checker

## Website copy

> Useful? You can make a small one-time payment to support further development. The checker stays free, and supporting does not unlock an additional product or service.

Button label: **Support this tool**

## Risk and workload

- Spend required: £0
- Contract required: none beyond the existing Stripe account terms
- Owner fulfilment: none
- Customer promise: accurately limited to optional support
- Reversibility: payment link can be deactivated; product can be archived
- Tax/accounting: any receipts remain business income and should be recorded
- Refund/support contact: ventureops26@gmail.com

## Approval state

**Pending explicit owner approval.**

The live Stripe write was not performed. Once approval is recorded, create the product first, then create a Payment Link using its default price, then add the resulting link to the tool page and update the experiment status.
