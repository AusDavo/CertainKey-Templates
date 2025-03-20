---
title: CertainKey Bitcoin Balance and Control Verification Report
author: David Pinkerton
date: March 20, 2025
---

**Prepared for:** Horizon Trustees ATF Horizon Super Fund

**ABN:** 12 345 678 901

**Report Date:** August 20, 2024

**Report Reference:** CERTAINKEY-2024-EOFY-24L05

# Executive Summary

## Entity Information

- **Entity Name:** Horizon Super Fund
- **ABN:** 12 345 678 901
- **Type of Engagement:** EOFY Proof of Holdings
- **Report Date:** August 20, 2024

## What We Did

- Confirmed the Bitcoin balance at June 30, 2024, 23:59 AEST.
- Verified control of the wallet through a multi-signature key audit.

## Key Findings

- **Balance:** 5.2371 BTC
- **Fiat Value:** AUD 428,150 (using Bitaroo Pty Ltd's closing price)
- **Wallet Descriptor Hash:**
  7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478

## Key Audit Results

| Name              | Role                  | Approved | Status   |
| ----------------- | --------------------- | -------- | -------- |
| **John Smith**    | **Trustee**           | **Yes**  | **Pass** |
| **Emily Chen**    | **Trustee**           | **Yes**  | **Pass** |
| **Michael Brown** | **Financial Advisor** | **Yes**  | **Pass** |

- **Quorum**: 2 of 3 signers required — **Exceeded** (3/3
  signed).
- **Rating**: A+ for exceptional key participation.

## **Conclusion**

We are pleased to confirm that Horizon Super Fund held 5.2371 BTC at
June 30, 2024, 23:59 AEST, with full control verified by all three key
holders. Final assessment: **Pass (A+)**.

# Purpose and Scope

- **Goal:** Prove Horizon Super Fund owns and controls its Bitcoin,
  and confirm its balance for EOFY reporting.
- **Scope:** Balance check, key verification, and quorum
  assessment.
- **Use:** Meets ATO and ASIC requirements for SMSF tax and audit
  compliance.

# How We Did It

## Information Provided

- Horizon Super Fund supplied their wallet descriptor and a signed
  ownership declaration.
- Date/time set: June 30, 2024, 23:59 AEST.

## Balance Check

- Used Sparrow Wallet to load the keys.

- Confirmed 5.2371 BTC via:

  - Local Bitcoin Node
  - Bitaroo Electrum Server
  - Blockstream Electrum Server
  - Fiat value: AUD 81,750 per BTC (Bitaroo's closing price),
    totaling AUD 428,150.

## **Key Verification**

- Sent unique challenges to each key holder.
- Verified all 3 signatures using Gatekeeper.

## **Report Process**

- Drafted, reviewed with Horizon Trustees, and finalised on August 20, 2024.
- Stored a PDF hash in our database.

## **Data Security**

- Deleted all sensitive wallet descriptor and keys post-finalisation.

## Regulatory Fit

- Aligns with ASIC, ATO, and AASB 1056 standards for fair-value
  reporting.

# Detailed Results

## **Blockchain Confirmation**

- All sources agreed: 5.2371 BTC at June 30, 2024, 23:59 AEST.

## Fiat Breakdown

- Closing Price: AUD 81,750 per BTC (Bitaroo Pty Ltd)
- Total: 5.2371 BTC × AUD 81,750 = AUD 428,150

## Key Audit

- 3/3 signatures passed, exceeding the 2/3 quorum.
- Result: A+

## Evidence

- **Wallet Hash:**
  `7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478`
  (see [Appendix A](#Appendix A: Wallet Descriptor Hash|outline))
- **Balance:** 5.2371 BTC

# Final Statement

Horizon Super Fund held 5.2371 BTC worth AUD 428,150 at June 30,
2024, 23:59 AEST, with control proven by all key holders. **Pass (A+)**.

# Disclaimer & Limitations

- **Scope:** Covers only this timestamp.
- **Limits:** Balances may change; relies on trusted third-party
  data.
- **Not an Audit:** Not a full financial audit.

# Authentication

A SHA-256 hash of this PDF is stored by CertainKey for
verification.

**Prepared By:**

David Pinkerton, Founder and Principal Verifier, CertainKey

**Date:** August 20, 2024

**Contact:** contact@certainkey.com.au

**Customer Acknowledgement**:

By signing below, the Customer acknowledges the accuracy of the
information provided and the results contained in this verification.

**Customer Representative:**

\[Signature\]

John Smith, Trustee

**Date:** August 20, 2024

# Appendix A: Wallet Descriptor Hash

We hash the wallet descriptor (a technical wallet summary) using SHA-256
to protect privacy while allowing verification. Example:

- Input:

  ```
  sh(multi(2,\[fingerprint1/48\'/0\'/0\'\]xpub1,\[fingerprint2/48\'/0\'/0\'\]xpub2,\[fingerprint3/48\'/0\'/0\'\]xpub3))
  ```

- Hash:
  ```
  7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478
  ```
  Anyone with the exact descriptor can replicate this hash.
