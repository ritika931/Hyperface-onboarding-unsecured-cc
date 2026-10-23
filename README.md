# Hyperface — unsecured co-branded credit card onboarding

Clickable mobile prototype of the onboarding journey for an unsecured co-branded credit card.
Single-file `index.html`, deployed on Vercel.

Flow: landing → mobile & OTP → PAN → personal details → work & income → KYC (issuer-hosted Aadhaar eKYC, video KYC now or scheduled) → eligibility check → offer → personalise card → sanction letter & KFS e-sign → OTP card activation.

- Jump to any screen with a hash, e.g. `/#vkyc`, `/#offer`, `/#kfs`.
- Brand, issuer, cashback and fees are set in the `CFG` block at the top of the script.
- All values are sample data.
