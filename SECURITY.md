# Security policy

Thanks for taking the time to look at midfeed's security. We take
reports seriously and appreciate responsible disclosure.

## Reporting a vulnerability

Please email **[dev@midfeed.com](mailto:dev@midfeed.com)** with the
details. Do **not** open a public GitHub issue, post in discussions,
or share the report on social media until we've had a chance to
investigate and ship a fix.

When you write to us, include as much of the following as you can — it
helps us reproduce and triage faster:

- A clear description of the issue and the impact you believe it has.
- Step-by-step reproduction (URLs, payloads, request/response samples).
- The affected component or surface (admin, public site, API, etc.).
- Your environment details (browser, OS, account type) where relevant.
- Any proof-of-concept code, screenshots, or recordings — encrypted
  attachments are welcome.

You can encrypt sensitive material against the public PGP key on
request — just ask in your initial email and we'll send it back.

## What to expect

- **Acknowledgement** within 2 business days of your report.
- **Initial assessment** with severity and next-steps within 7 business
  days.
- **Status updates** at least every 14 days while a fix is in
  progress.
- **Coordinated disclosure** once a fix has shipped and any affected
  customers have had time to update — we'll credit you in the release
  notes if you'd like.

## Scope

In scope:

- The midfeed platform and its public-facing services at `midfeed.com`.
- The midfeed API surface and authentication flows.
- The browser extension and any other client we ship.

Out of scope:

- Reports based purely on automated scanner output without a
  demonstrated impact.
- Denial-of-service via volumetric / network-layer attacks.
- Social engineering of midfeed staff or customers.
- Vulnerabilities in third-party services we integrate with —
  please report those to the vendor directly.
- Issues that require a fully compromised end-user device, browser,
  or account to exploit.

## Safe-harbour

We won't pursue or support legal action against researchers who:

- Make a good-faith effort to follow this policy.
- Avoid privacy violations, data destruction, and service disruption.
- Stop testing and report immediately if they encounter customer data,
  and don't access more than is needed to demonstrate the issue.
- Don't extort, threaten, or hold disclosure as leverage.

Thanks for helping keep midfeed and our customers safe.
