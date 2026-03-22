# Xago Legal Documents

## Folder Structure

```
xago-legal/
├── README.md                        # This file
├── licenses/
│   ├── 01-microsoft-csp-agreement.md   # Reseller agreement for BC licenses (CSP)
│   └── 02-pte-license-agreement.md     # License for Xago's own BC extensions
├── privacy/
│   ├── 03-privacy-statement.md         # End-user facing privacy notice (GDPR Art. 13)
│   └── 04-dpa-annex.md                 # Data Processing Agreement (GDPR Art. 28)
└── templates/
    └── 05-eula.md                      # End User License Agreement

```

## File Overview

### licenses

#### 01-microsoft-csp-agreement.md
> Comment: This is the draft of the CSP related agreement with Xago Software AS customers that purchase Microsoft licenses from us.

#### 02-pte-license-agreement.md
> Comment: This is the draft of the PTE license agreement with Xago Software AS customers that purchase PTE licenses from us. 

> A **Per-Tenant Extension (PTE)** in Microsoft Dynamics 365 Business Central is a deployment model for custom-developed software that is installed individually in each customer’s Business Central environment.

> Although the same extension codebase is used across multiple customers, it is **not distributed through Microsoft AppSource** and is instead deployed directly to each tenant. This means the solution is technically treated as a **customer-specific customization**, even if it is standardized in practice.

> PTEs are subject to fewer platform restrictions than AppSource apps and allow deeper integration with the customer’s ERP environment. However, they are **not centrally published, validated, or managed by Microsoft’s marketplace**, and responsibility for deployment, updates, and compliance rests with the provider.

> **In summary:**  
> A PTE is a **privately distributed extension, installed per customer environment, even when the functionality is standardized across customers**.

#### mca_no_for_reference.md
> Comment: This is added as a reference for the Microsoft Customer Agreement that our customers sign. It's between the Customer and Microsoft, added for reference purposes only.

#### microsoft-partner-agreement_for_reference.md
> Comment: This is added as a reference for the Microsoft Partner Agreement Xago Software AS have with Microsoft. It's between Xago Software AS and Microsoft, added for reference purposes only.

### privacy

#### 03-privacy-statement.md
> Comment: This is the draft of the privacy statement for Xago Software AS.


#### 04-dpa-annex.md
> Comment: This is the draft of the DPA Annex for Xago Software AS

#### dpa_iktNorge_for_reference.md
> Comment: This is added as a reference for the DPA Annex for Xago Software AS. Not using this agreement, we have a license for it now but plan to not renew it.

### Status

| Document | Status | Last Updated |
|---|---|---|
| 01 Microsoft CSP Agreement | 🟡 Draft | 2026-03-19 |
| 02 PTE License Agreement | 🟡 Draft | 2026-03-19 |
| 03 Privacy Statement | 🟡 Draft | 2026-03-19 |
| 04 DPA Annex | 🟡 Draft | 2026-03-19 |
| 05 EULA | 🟡 Draft | 2026-03-19 |

## Placeholders to fill in before use

- `[ORG.NO]` — Xago Software AS org number (922 021 074)
- `[ADDRESS]` — Frydenbergveien 46B, 0575 OSLO
- `[DATE]` — Agreement date
- `[CUSTOMER NAME]` — Customer legal entity name
- `[CUSTOMER ORG.NO]` — Customer org number
- `[SUB-PROCESSORS]` — Confirm current sub-processor list
- `[PRIVACY EMAIL]` — e.g. privacy@xago.no
- `[PRIVACY URL]` — e.g. xagosoftware.no/privacy

## Notes

- All documents are drafts and should be reviewed by a Norwegian lawyer before use.
- Norwegian law governs all agreements (norsk rett, Oslo tingrett som verneting).
- DPA Annex (04) is designed to be attached to both 01 and 02.
- mca_no_for_reference.md is the agreement between the Customer and Microsoft, added for reference purposes only.
- dpa_iktnorge_for reference.md is added for reference purposes only, to analyze gaps in the DPA Annex. 