---
title: CertainKey Verification Report
subtitle: Bitcoin Balance and Control
author: David Pinkerton
date: 20 August, 2024
---

\begin{titlepage}
\centering
\null
\vspace{4cm}
{\Huge\bfseries CertainKey Verification Report\par}
\vspace{0.5cm}
{\Large Bitcoin Balance and Control\par}
\vspace{0.5cm}
{\large Prepared by David Pinkerton\par}
\vspace{0.5cm}
{\large 20 August, 2024\par}
\vspace{0.5cm}
\flushright
{\small
\textbf{Prepared for:} Horizon Trustees ATF Horizon Super Fund \\
\textbf{ABN:} 12 345 678 901 \\
\textbf{Report Date:} 20/08/2024 \\
\textbf{Reference:} CK-example
}
\vspace{6cm} % Increased to push graphic lower
\includegraphics[width=\textwidth]{certainkeybrand.png}
\end{titlepage}

## Executive Summary

### Entity Information

- **Entity Name:** Horizon Super Fund
- **ABN:** 12 345 678 901
- **Type of Engagement:** EOFY Proof of Holdings
- **Report Date:** 20/08/2024

### What We Did

- Confirmed the Bitcoin balance as at 30/06/2024, 23:59 AEST.
- Verified control of the wallet through a multi-signature key audit.

### Key Findings

- **Balance:** 5.2371 BTC
- **Fiat Value:** AUD 428,150 (using Bitaroo Pty Ltd's closing price)
- **Wallet Descriptor Hash:**  
  `7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478`

### Key Audit Results

#### Key Holder Verification

\begin{tabular}{@{}llll@{}}
\toprule
\textbf{Name} & \textbf{Role} & \textbf{Approved} & \textbf{Status} \\
\midrule
\rowcolor{lightgray} \textbf{John Smith} & \textbf{Trustee} & \textbf{Yes} & \textbf{Pass} \\
\textbf{Emily Chen} & \textbf{Trustee} & \textbf{Yes} & \textbf{Pass} \\
\rowcolor{lightgray} \textbf{Michael Brown} & \textbf{Financial Advisor} & \textbf{Yes} & \textbf{Pass} \\
\bottomrule
\end{tabular}

#### Quorum and Rating

- **Quorum:** 2 of 3 signers required — Exceeded (3/3 signed).
- **Rating:** A+ for exceptional key participation.

### Conclusion

Horizon Super Fund held 5.2371 BTC as at 30/06/2024, 23:59 AEST, with full control verified by all three key holders. Final assessment: **Pass (A+)**.

\tableofcontents
\newpage

## Purpose and Scope

- **Purpose:** To provide independent verification that Horizon Super Fund owns and controls its Bitcoin holdings, and to confirm the balance as at 30/06/2024 for End of Financial Year (EOFY) reporting, ensuring compliance with ATO and ASIC requirements.
- **Scope:** This engagement encompassed a balance confirmation, multi-signature key verification, and quorum assessment to establish ownership and control.
- **Use:** Meets ATO and ASIC requirements for SMSF tax and audit compliance.

## How We Did It

- **Information Provided**

  - Horizon Super Fund supplied their wallet descriptor and a signed ownership declaration.
  - Date/time set: 30/06/2024, 23:59 AEST.

- **Balance Check**

  - Used Sparrow Wallet, a trusted open-source tool, to load the provided keys and confirm the balance of 5.2371 BTC. This was cross-verified using a local Bitcoin Node, Bitaroo Electrum Server, and Blockstream Electrum Server, ensuring accuracy as at 30/06/2024, 23:59 AEST.
  - Fiat value calculated at AUD 81,750 per BTC (Bitaroo’s closing price), totaling AUD 428,150.

- **Key Verification**

  - Issued unique cryptographic challenges to each key holder, requiring them to sign with their respective private keys, ensuring individual control over their portion of the multi-signature wallet.
  - Verified all 3 signatures using Gatekeeper, a secure digital signature verification system for Bitcoin, confirming control by all parties.

- **Report Process**

  - Drafted the report, reviewed it with Horizon Trustees, and finalised it on 20/08/2024.
  - Stored a PDF hash in our database for verification purposes.

- **Data Security**

  - Deleted all sensitive wallet descriptor and key data following finalisation to ensure confidentiality. The wallet descriptor hash, included in this report, is a one-way cryptographic output that protects privacy while allowing verification if needed.

- **Regulatory Fit**

  - Aligns with ASIC, ATO, and AASB 1056 standards for fair-value reporting of self-managed superannuation fund assets.

## Detailed Results

\newpage

### Blockchain Confirmation

- All sources (local Bitcoin Node, Bitaroo Electrum Server, Blockstream Electrum Server) confirmed: 5.2371 BTC as at 30/06/2024, 23:59 AEST.

### Fiat Breakdown

- Closing Price: AUD 81,750 per BTC (sourced from Bitaroo Pty Ltd, Australia’s leading Bitcoin exchange)
- Total: 5.2371 BTC × AUD 81,750 = AUD 428,150

### Key Audit

- 3/3 signatures passed, exceeding the 2/3 quorum requirement.
- Result: A+

### Evidence

- **Wallet Hash:**  
  `7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478`  
  (see Appendix for more information)
- **Balance:** 5.2371 BTC

## Final Statement

Based on the verification process, Horizon Super Fund held 5.2371 BTC, valued at AUD 428,150, as at 30/06/2024, 23:59 AEST. Control was confirmed by the participation of all three key holders, exceeding the required quorum. Assessment: **Pass (A+)**.

## Authentication

A SHA-256 hash of this PDF is stored by CertainKey for verification purposes.

**Prepared By:**  
David Pinkerton - Principal Verifier, CertainKey  
**Date:** 20/08/2024  
**Contact:** <contact@certainkey.com.au>

**Customer Acknowledgement:**  
By signing below, the Customer confirms receipt of this report and agreement to the verification process outlined herein.

**Customer Representative:**  
\vspace{1cm}  
\rule{5cm}{0.4pt}  
John Smith, Trustee  
**Date:** 20/08/2024

## Disclaimer & Limitations

- **Scope:** This report reflects the bitcoin balance and control status solely as at 30/06/2024, 23:59 AEST.
- **Limitations:** Balances are subject to change after this timestamp, and valuations rely on trusted third-party data from Bitaroo Pty Ltd.
- **Not an Audit:** This verification does not constitute a comprehensive financial audit but serves as a targeted proof of holdings for EOFY purposes.

## Appendix: Wallet Descriptor Hash

The wallet descriptor (a technical wallet summary) is hashed using SHA-256 to protect privacy while allowing verification. This hash ensures that sensitive details remain confidential, but anyone with the exact descriptor can replicate the hash to confirm its authenticity. Example:

- **Input:**

  ```text
  sh(multi(2,[fingerprint1/48'/0'/0']xpub1,[fingerprint2/48'/0'/0']xpub2,[fingerprint3/48'/0'/0']xpub3))
  ```

- **Hash:**

  ```text
  7d5b07fad41588dde313e8e83c53436dbed0923f1af26a318fa9a1eff1fe6478
  ```

Anyone with the exact descriptor can replicate this hash to verify the wallet.
