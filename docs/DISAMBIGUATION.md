# Kadena ecosystem - what's live, what's defunct

There's confusion in the wild between several sites and repos that all
call themselves "Kadena". This file is the canonical map.

## Active

| Thing | Where | Status |
|-------|-------|--------|
| KDA-Community | github.com/KDA-Community | Active community fork and reference |
| AI-KDA-Community | github.com/AI-KDA-Community | Active - AI tooling and releases |
| sot (Source Of Truth) | private, released as binary | Active - canonical chain/web data |
| Chainweb (upstream) | github.com/kadena-io/chainweb-node | Active reference implementation |

## Defunct / historical

| Thing | Status | Note |
|-------|--------|------|
| kedena.io | defunct | Old domain, unrelated to current work |
| kedena.com | defunct | Same |
| kadena.io (docs) | partial | Corporate site - some docs still referenced but not authoritative |
| Various "kadena-" prefixed GitHub orgs | mixed | Check pushed_at; many are stale forks |

## How to tell what's current

1. Look at the release date on GitHub. Anything older than about 6 months
   in the AI-KDA ecosystem is likely superseded.
2. The sot binary is the authoritative reference. If a doc disagrees
   with sot, sot wins.
3. This bundle ships the version marker in ../VERSION. Anything not
   matching is out of sync.

## Reporting confusion

If you find a site, repo, or doc that contradicts this file, open an
issue against the releases repository that shipped this bundle.
