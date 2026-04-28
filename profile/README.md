---
title: Jennifer Woodfine — GitHub Profile
audience: identity-passport
last_edited: 2026-04-28
lang: en
---

# Jennifer Woodfine

I am an employee of Woodfine Management Corp. — a Customer of
PointSav Digital Systems in our development flow.

PointSav (the Vendor) operates the canonical engineering source for the
substrate stack. Woodfine Management Corp. (the Customer) operates the
downstream deployment, contributing code back to the Vendor through a
staging tier where Peter and I both author commits.

I work alongside Peter Woodfine. Together we contribute to the workspace
at `~/Foundry` on the shared development VM, alternating commit identity
per session. Our staging-tier repos at `github.com/jwoodfine/*` and
`github.com/pwoodfine/*` mirror the Vendor's canonical engineering source
before promotion to `github.com/pointsav/*`. The commit alternation is
deliberate — it makes the staging → vendor loop visible on GitHub so that
future contributors at either company have a reproducible example of how
to participate.

## What this account commits to

This account is the staging-tier identity for Jennifer Woodfine commits
in the substrate development flow. Every commit authored as `jwoodfine`
is signed with my SSH key and lands first in this account's mirror of
the canonical engineering repo, before promotion to the Vendor's
canonical source.

The substrate I contribute to is Foundry — a per-tenant content +
inference + editorial substrate that PointSav operates as Vendor and
that Woodfine Management Corp. consumes as the first Customer. The
substrate's design is documented at the Vendor's canonical doctrine
(`pointsav/foundry`).

## How to contribute via this account

This account is the staging-tier mirror only. Contributions to the
Foundry substrate flow:

- Authored locally on the workspace VM via the staging-tier commit
  helper, alternating identity Jennifer / Peter
- Pushed to the staging-tier mirror (this account)
- Promoted to the Vendor's canonical engineering source
  (`github.com/pointsav/<repo>`) via local promotion script, evolving
  toward GitHub Actions promotion as contributor count grows

External contributors do not open pull requests against this account
directly. The contribution flow runs through the Vendor's canonical
repos.

## Three-Tier Contributor Model

Per the substrate's published Three-Tier Contributor Model:

- Core (4–7) — substrate operators; doctrine + governance + cluster Task
  work
- Paid (50–100, planned) — Creative Contributors at the editorial
  cycle's end, refining substrate-generated drafts
- Open (10K+, planned) — wiki consumers; remixers; downstream
  contributors

I sit in the Core tier as a Customer-side contributor in the substrate
development flow. The Paid and Open tiers are planned per the Compounding
Substrate trajectory documented in the Vendor's substrate doctrine.

## See also

- `github.com/pointsav` — Vendor canonical engineering source; the
  destination for staged commits after promotion
- `github.com/woodfine` — Customer organisation; downstream deployment
  receiving Vendor-originated commits
- `github.com/pwoodfine` — Peter Woodfine, fellow staging-tier
  contributor
