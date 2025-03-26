# CertainKey Verification Report

## Bitcoin Balance and Control

**Client:** Horizon Trustees ATF Horizon Super Fund (ABN 12 345 678 901)  
**Purpose:** EOFY Bitcoin Holdings Verification  
**Balance Snapshot:** 30 June 2024, 23:59 AEST  
**Prepared by:** David Pinkerton, CertainKey  
**Date Issued:** 20 August 2024  
**Reference:** CK-example  

![brandimage](logo.png)

---

## Table of Contents

- [Executive Summary](#executive-summary)
- [Purpose and Scope](#purpose-and-scope)
- [How We Did It](#how-we-did-it)
- [Detailed Results](#detailed-results)
- [Final Statement](#final-statement)
- [Authentication](#authentication)
- [Disclaimer & Limitations](#disclaimer--limitations)
- [Notes](#notes)
- [Appendix: Wallet Descriptor Hash](#appendix-wallet-descriptor-hash)

---

## Executive Summary

### Entity Information

- **Entity Name:** Horizon Super Fund  
- **ABN:** 12 345 678 901  
- **Type of Engagement:** EOFY Proof of Holdings  
- **Report Date:** 20 August 2024  

### What We Did

- Confirmed the Bitcoin balance as at the Balance Snapshot (defined below).  
- Verified control of the wallet through a multi-signature key audit.  

### Key Findings

- **Balance:** **5.2371 BTC**  
- **Fiat Value:** **AUD 428,150** (using Bitaroo Pty Ltd's closing price)  
- **Wallet Descriptor Hash:**  
  `7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478`  

### Key Audit Results

#### Key Holder Verification

| Name          | Role             | Approved | Status |
|---------------|------------------|----------|--------|
| John Smith    | Trustee          | Yes      | Pass   |
| Emily Chen    | Trustee          | Yes      | Pass   |
| Michael Brown | Financial Advisor| Yes      | Pass   |

#### Quorum and Rating

- **Quorum:** 2 of 3 signers required — Exceeded (3/3 signed).  
- **Rating:** A+ for exceptional key participation.  

### Conclusion

Horizon Super Fund held **5.2371 BTC** as at the Balance Snapshot, with full control verified by all three key holders. Final assessment: **Pass (A+)**.

---

## Purpose and Scope

### Purpose

To provide independent verification that Horizon Super Fund owns and controls its Bitcoin holdings, and to confirm the balance as at 30 June 2024, 23:59 AEST (hereafter the "Balance Snapshot") for End of Financial Year (EOFY) reporting, ensuring compliance with ATO and ASIC requirements.

### Scope

This engagement encompassed a balance confirmation, multi-signature key verification, and quorum assessment to establish ownership and control as at the Balance Snapshot.

### Use

Meets ATO and ASIC requirements for SMSF tax and audit compliance.

---

## How We Did It

### Information Provided

- Horizon Super Fund supplied their wallet descriptor and a signed ownership declaration.  
- Verification was conducted as at the Balance Snapshot.  

### Balance Check

- Used Sparrow Wallet, a trusted open-source tool, to load the provided keys and confirm the balance of **5.2371 BTC** as at the Balance Snapshot. This was cross-verified using a local Bitcoin Node, Bitaroo Electrum Server, and Blockstream Electrum Server, ensuring accuracy.  
- Fiat value calculated at AUD 81,750 per BTC (Bitaroo’s closing price), totaling **AUD 428,150** as at the Balance Snapshot.  

### Key Verification

- Issued unique cryptographic challenges to each key holder, requiring them to sign with their respective private keys, ensuring individual control over their portion of the multi-signature wallet.  
- Verified all 3 signatures using Gatekeeper, a secure digital signature verification system for Bitcoin, confirming control by all parties as at the Balance Snapshot.  

### Report Process

- Drafted the report, reviewed it with Horizon Trustees, and finalised it on 20 August 2024.  
- Stored a PDF hash in our database for verification purposes.  

### Data Security

- Deleted all sensitive wallet descriptor and key data following finalisation to ensure confidentiality. The wallet descriptor hash, included in this report, is a one-way cryptographic output that protects privacy while allowing verification if needed.  

### Regulatory Fit

- Aligns with ASIC, ATO, and AASB 1056 standards for fair-value reporting of self-managed superannuation fund (SMSF) assets. Specifically, this report satisfies ATO requirements for SMSF cryptocurrency holdings (per TR 2023/1) and ASIC’s guidance on digital asset custody (INFO 225), ensuring auditable proof of ownership and valuation as at the Balance Snapshot.

---

## Detailed Results

### Blockchain Confirmation

- All sources (local Bitcoin Node, Bitaroo Electrum Server, Blockstream Electrum Server) confirmed: **5.2371 BTC** as at the Balance Snapshot.  

### Fiat Breakdown

- **Closing Price:** AUD 81,750 per BTC (sourced from Bitaroo Pty Ltd, Australia’s leading Bitcoin exchange, as at 30 June 2024, 23:59 AEST)  
- **Total:** **5.2371 BTC × AUD 81,750 = AUD 428,150** as at the Balance Snapshot  

### Key Audit

- 3/3 signatures passed, exceeding the 2/3 quorum requirement as at the Balance Snapshot.  
- Result: A+  

### Evidence

- **Wallet Hash:**  
  `7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478`  
- **Balance:** **5.2371 BTC**  

---

## Final Statement

Based on the verification process, Horizon Super Fund held **5.2371 BTC**, valued at **AUD 428,150**, as at the Balance Snapshot. Control was confirmed by the participation of all three key holders, exceeding the required quorum. Assessment: **Pass (A+)**.

---

## Authentication

A SHA-256 hash of this PDF is stored by CertainKey for verification purposes.

**Prepared By:**  
David Pinkerton - Principal Verifier, CertainKey  
**Date:** 20 August 2024  
**Contact:** <contact@certainkey.com.au>  

**For Queries:** Contact David Pinkerton at <contact@certainkey.com.au> for verification or clarification of this report.

**Customer Acknowledgement:**  
By signing below, the Customer confirms receipt of this report and agreement to the verification process outlined herein.  

**Customer Representative:**  
John Smith, Trustee  
**Date:** 20 August 2024  

---

## Disclaimer & Limitations

- **Scope:** This report reflects the Bitcoin balance and control status solely as at the Balance Snapshot.  
- **Limitations:** Balances are subject to change after this timestamp, and valuations rely on trusted third-party data from Bitaroo Pty Ltd.  
- **Not an Audit:** This verification does not constitute a comprehensive financial audit but serves as a targeted proof of holdings for EOFY purposes.  

---

## Notes

- **Multi-Signature Wallet:** A Bitcoin wallet requiring multiple private key signatures (in this case, 2 of 3) to authorize transactions, enhancing security.  
- **Wallet Descriptor Hash:** A SHA-256 cryptographic hash of the wallet’s technical configuration, protecting sensitive details while enabling verification.  

---

## Appendix: Wallet Descriptor Hash

The wallet descriptor (a technical wallet summary) is hashed using SHA-256 to protect privacy while allowing verification. This hash ensures that sensitive details remain confidential, but anyone with the exact descriptor can replicate the hash to confirm its authenticity. Example:

- **Input:**  

  ```text
  sh(multi(2,[fingerprint1/48'/0'/0']xpub1,
  [fingerprint2/48'/0'/0']xpub2,
  [fingerprint3/48'/0'/0']xpub3))
  ```

- **Hash:**  

  ```text
  7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478
  ```

Anyone with the exact descriptor can replicate this hash to verify the wallet.
