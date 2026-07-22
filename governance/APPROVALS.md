# Governance and Approval Matrix

## Non-negotiable rules

- Never put protected health information, patient identifiers, medical records, credentials, API keys or payment data in GitHub.
- Use least-privilege access and separate draft environments from production.
- AI output is a draft until the designated human approves it.
- Never promise outcomes, imply guaranteed results, fabricate scarcity, manufacture reviews or conceal material terms.
- Before/after media and testimonials require documented consent and the correct disclosure process.
- Clinical claims require review by an authorized Illumé clinician and support from appropriate current evidence.
- Agents must disclose uncertainty and preserve source links and dates.

## Approval matrix

| Action | AI may prepare | Required approval |
|---|---:|---|
| Public research and competitor scan | Yes | None to draft |
| Internal analysis using aggregated data | Yes | Data owner |
| Social, blog, email or website draft | Yes | Brand owner; clinician if medical |
| Schedule/publish content | No | Marketing owner |
| Reply to review, lead or patient | Draft only | Authorized staff |
| Change price, package or promotion | Recommend only | Owner + finance/clinical as applicable |
| Launch/change paid advertising | Recommend only | Budget owner |
| Medical advice, diagnosis or treatment selection | No | Licensed clinician |
| Clinical protocol or dosing | No | Medical director/authorized clinician |
| Patient data access or export | No by default | Privacy/compliance owner and approved system |
| Vendor contract or purchase | Recommend only | Owner |
| Production website/CRM change | Test/draft only | System owner |

## Risk tiers

- **Green:** public research, ideation, internal templates, de-identified analysis.
- **Yellow:** brand-facing drafts, financial recommendations, workflow changes, promotional concepts. Human review required.
- **Red:** clinical direction, PHI, external sends, public publishing, spending, contracts, access control and production changes. Explicit authorized approval required.

## Incident response

If an agent detects PHI, a false claim, credential exposure or an unauthorized external action:
1. Stop the workflow.
2. Do not copy or redistribute the sensitive material.
3. Notify the designated owner with minimum necessary detail.
4. Preserve a non-sensitive audit record.
5. Resume only after written direction from the authorized owner.

## Data retention

Keep only what is necessary. Prefer aggregated measures. Define an owner and retention period for each integration. Remove access when no longer required. GitHub is for code, prompts, templates and non-sensitive operations—not patient records.
