# Pranav Bhave

I work on AI assurance and cloud security: measuring what a safety claim
actually establishes, and where the evidence runs out.

**Site → [cubits11.github.io](https://cubits11.github.io)** — technical claims
there either link to public evidence or are marked as attested rather than
shown.

## Now

- **[CC-Framework](https://github.com/Cubits11/cc-framework)** — Python.
  If two AI content filters each fail on 10% of harmful inputs, multiplying
  gives 1% for the pair — but that assumes their failures are independent.
  The real rate lies somewhere in [0%, 10%], depending on how far the two
  failure sets overlap, and measuring each filter alone never tells you which.
  CC-Framework reports the range the measurements actually support instead of
  assuming independence. Worked example:
  [When Marginals Are Not Enough](https://cubits11.github.io/essays/when-marginals-are-not-enough/).

- **[Ghost-Ark](https://github.com/PSUCyberSecurityLab/ghost-ark)** — TypeScript,
  AWS CDK. At Penn State's S2 Lab. A verifier that tests how far a signed audit
  receipt actually identifies the execution it claims to describe, and where
  that identification breaks down.

- **Assay** — private, early. What a verifier can and cannot conclude from AWS
  Nitro Enclave attestation.

Penn State CS '26, Cybersecurity minor · AWS Certified Cloud Practitioner and
AI Practitioner · Philadelphia, PA.

## Reading this account

Repositories marked **Archived** are earlier exploration kept as a record, not
as current claims — some carry language I would not write today. Current work
is what's pinned, plus the site above.
