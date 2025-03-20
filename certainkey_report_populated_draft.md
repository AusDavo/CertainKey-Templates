---
title: CertainKey Bitcoin Balance and Control Verification Report
author: David Pinkerton
date: March 20, 2025
---

**Prepared for:** Horizon Trustees ATF Horizon Super Fund  
**ABN:** 12 345 678 901  
**Report Date:** 20/08/2024  
**Report Reference:** CERTAINKEY-2024-EOFY-24L05  

# Executive Summary  

## Entity Information  
- **Entity Name:** Horizon Super Fund  
- **ABN:** 12 345 678 901  
- **Type of Engagement:** EOFY Proof of Holdings  
- **Report Date:** 20/08/2024  

## What We Did  
- Confirmed the Bitcoin balance as at 30/06/2024, 23:59 AEST.  
- Verified control of the wallet through a multi-signature key audit.  

## Key Findings  
- **Balance:** 5.2371 BTC  
- **Fiat Value:** AUD 428,150 (using Bitaroo Pty Ltd's closing price)  
- **Wallet Descriptor Hash:**  
  7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478  

## Key Audit Results  
| Name              | Role                  | Approved | Status   |  
|-------------------|-----------------------|----------|----------|  
| **John Smith**    | **Trustee**           | **Yes**  | **Pass** |  
| **Emily Chen**    | **Trustee**           | **Yes**  | **Pass** |  
| **Michael Brown** | **Financial Advisor** | **Yes**  | **Pass** |  

- **Quorum:** 2 of 3 signers required — Exceeded (3/3 signed).  
- **Rating:** A+ for exceptional key participation.  

## Conclusion  
Horizon Super Fund held 5.2371 BTC as at 30/06/2024, 23:59 AEST, with full control verified by all three key holders. Final assessment: **Pass (A+)**.  

# Purpose and Scope  

- **Purpose:** To provide independent verification that Horizon Super Fund owns and controls its Bitcoin holdings, and to confirm the balance as at 30/06/2024 for End of Financial Year (EOFY) reporting, ensuring compliance with ATO and ASIC requirements.  
- **Scope:** This engagement encompassed a balance confirmation, multi-signature key verification, and quorum assessment to establish ownership and control.  
- **Use:** Meets ATO and ASIC requirements for SMSF tax and audit compliance.  

# How We Did It  

## Information Provided  
- Horizon Super Fund supplied their wallet descriptor and a signed ownership declaration.  
- Date/time set: 30/06/2024, 23:59 AEST.  

## Balance Check  
- Used Sparrow Wallet, a trusted open-source tool, to load the provided keys and confirm the balance of 5.2371 BTC. This was cross-verified using a local Bitcoin Node, Bitaroo Electrum Server, and Blockstream Electrum Server, ensuring accuracy as at 30/06/2024, 23:59 AEST.  
- Fiat value calculated at AUD 81,750 per BTC (Bitaroo's closing price), totaling AUD 428,150.  

## Key Verification  
- Sent unique challenges to each key holder.  
- Verified all 3 signatures using Gatekeeper, a secure digital signature verification system for Bitcoin, confirming control by all parties.  

## Report Process  
- Drafted the report, reviewed it with Horizon Trustees, and finalised it on 20/08/2024.  
- Stored a PDF hash in our database for verification purposes.  

## Data Security  
- Deleted all sensitive wallet descriptor and key data following finalisation to ensure confidentiality.  

## Regulatory Fit  
- Aligns with ASIC, ATO, and AASB 1056 standards for fair-value reporting of self-managed superannuation fund assets.  

# Detailed Results  

## Blockchain Confirmation  
- All sources (local Bitcoin Node, Bitaroo Electrum Server, Blockstream Electrum Server) confirmed: 5.2371 BTC as at 30/06/2024, 23:59 AEST.  

## Fiat Breakdown  
- Closing Price: AUD 81,750 per BTC (Bitaroo Pty Ltd)  
- Total: 5.2371 BTC × AUD 81,750 = AUD 428,150  

## Key Audit  
- 3/3 signatures passed, exceeding the 2/3 quorum requirement.  
- Result: A+  

## Evidence  
- **Wallet Hash:**  
  `7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478`  
  (see Appendix A for more information)  
- **Balance:** 5.2371 BTC  

# Final Statement  
Based on the verification process, Horizon Super Fund held 5.2371 BTC, valued at AUD 428,150, as at 30/06/2024, 23:59 AEST. Control was confirmed by the participation of all three key holders, exceeding the required quorum. Assessment: **Pass (A+)**.  

# Disclaimer & Limitations  
- **Scope:** This report reflects the Bitcoin balance and control status solely as at 30/06/2024, 23:59 AEST.  
- **Limitations:** Balances are subject to change after this timestamp, and valuations rely on trusted third-party data from Bitaroo Pty Ltd.  
- **Not an Audit:** This verification does not constitute a comprehensive financial audit but serves as a targeted proof of holdings for EOFY purposes.  

# Authentication  
A SHA-256 hash of this PDF is stored by CertainKey for verification purposes.  

**Prepared By:**  
David Pinkerton, Founder and Principal Verifier, CertainKey  
**Date:** 20/08/2024  
**Contact:** contact@certainkey.com.au  

**Customer Acknowledgement:**  
By signing below, the Customer acknowledges the accuracy of the information provided and the results contained in this verification.  

**Customer Representative:**  
[Signature]  
John Smith, Trustee  
**Date:** 20/08/2024  

# Appendix A: Wallet Descriptor Hash  
The wallet descriptor (a technical wallet summary) is hashed using SHA-256 to protect privacy while allowing verification. Example:  

- **Input:**  
  ```
  sh(multi(2,[fingerprint1/48'/0'/0']xpub1,[fingerprint2/48'/0'/0']xpub2,[fingerprint3/48'/0'/0']xpub3))
  ```  
- **Hash:**  
  ```
  7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478
  ```  
Anyone with the exact descriptor can replicate this hash to verify the wallet.
