# Zelta Kronis Media

Public media delivery repository for approved Zelta Kronis assets.

## Purpose
This repository temporarily provides public HTTPS media assets for approved website/social publishing workflows.

## Public-only rule
Everything committed here must be safe for public Internet access.

Never store credentials, access tokens, app secrets, customer data, supplier terms, costs, internal prompts, unpublished strategy, or confidential files here.

## Structure
- `brand/public/` — approved public brand assets
- `social/feed/` — approved feed assets
- `social/stories/` — approved story assets
- `social/reels/` — approved reel/video assets
- `web/temporary/` — temporary public web assets
- `manifests/` — public-safe asset metadata

## Publishing lifecycle
AG-01B Creative -> Content Gate -> this public repository -> AG-01C Publisher -> Meta -> AG-01D Analyst.

Only Content Gate APPROVED assets may be committed.

## Naming
`ZK-{CHANNEL}-{SEQUENCE}-{slug}.{ext}`

Examples:
- `ZK-IG-0002-coming-soon.png`
- `ZK-ST-0001-coming-soon.png`

## Temporary architecture
This is an MVP media origin, not the permanent DAM/CDN. It can later be replaced by the ecommerce/CDN or `media.zeltakronis.com` without changing the agent workflow.