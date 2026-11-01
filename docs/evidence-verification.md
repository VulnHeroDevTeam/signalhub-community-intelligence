# Evidence Verification: Public Principles

**Scope:** Public methodology and proposed interoperability terms; not a disclosure of SignalHub's proprietary scoring or moderation implementation.

## Separate the claim from its support

Store a claim (e.g. "public PoC reference exists") separately from source URL, publication date, observed date, reviewer decision, and claim-specific confidence. A blog post citing a GitHub repository does not make two independent sources.

## Distinct evidence dimensions

- **Reported:** submitted assertion; not endorsed.
- **Source checked:** reference resolves and materially supports the exact assertion.
- **Independently corroborated:** second independently originated source supports it.
- **Lab validated:** a narrowly defined behavior reproduced in an authorized controlled environment.
- **In-the-wild claim:** real-world exploitation report with attributable supporting evidence.

These are not ordered trust levels. A lab PoC does not prove real-world exploitation. Inability to reproduce does not prove non-exploitability.

## Review hygiene

Check CVE/product/version alignment, chronology, original sourcing, duplicates, conflicts, redistribution rights, and exposure of sensitive details. Use appropriate statuses (pending, accepted, rejected, needs changes, withdrawn), keep audit history, and allow corrections.

## Publication

Publish only reviewed, non-sensitive, licensed-for-redistribution information. Identify source and evidence limitations. Do not automatically publish an unreviewed submission or promote it to confirmed exploitation.
