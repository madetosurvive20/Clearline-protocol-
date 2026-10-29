# Clearline Protocol

Main site (clearlineprotocol.com).

## Security, legal and downtime

Clearline's security program, its legal position and its downtime plan are
kept with the product that carries customer data, in the
[CP-RAILOPS](https://github.com/madetosurvive20/CP-RAILOPS) repository under
`security-agent/`:

- `security-agent/AGENT.md`: how the Clearline Security Agent works and what
  it may do.
- `security-agent/checks/`: the weekly security check-up (dependencies,
  secrets, code, the live sites, the database, the platform settings). This
  site is in its list (`security-agent/sites.json`).
- `security-agent/playbooks/`: what to do when something is attacked, broken,
  leaked or litigated.
- `security-agent/knowledge/legal/`: Texas law and cases, rail regulation,
  what comparable vendors publish, and the gap analysis of the Terms of Use,
  Privacy Policy, Cookies Policy, Master Subscription Agreement, SLA and
  continuity plan.

The public policies live on the Rail site: [Terms of Use](https://clearlineprotocolrail.com/terms/),
[Privacy Policy](https://clearlineprotocolrail.com/privacy/),
[Cookies](https://clearlineprotocolrail.com/cookies/),
[Security](https://clearlineprotocolrail.com/security/),
[Continuity](https://clearlineprotocolrail.com/continuity/).
Security issues: security@clearlineprotocol.com (see `/.well-known/security.txt` on each site).
