# The Boundary Atlas

*Sample AI Architecture, work 01 — a design study in five figures.*

Vendor-neutral, model-neutral, deliberately generic. The point is a way of
thinking, not a reference implementation. No client data appears anywhere in this
series.

**The brief — a composite, invented for this study.** A supply chain operating
across regions that are drifting apart: data-residency laws, export controls,
regulatory walls. Inside it, people and businesses have to prove who they are,
constantly. The ask: verify the required identity claims in every region, keep raw
PII and source documents out of checkpoints, and stay neutral about vendors and
models.

## The five figures

0. [Draw the borders before the arrows](00-boundary-map.en) — jurisdictional and
   trust boundaries, and the kinds of thing allowed to cross them.
1. [The border ledger](01-border-ledger.en) — data classes against borders, with a
   verdict in every cell and no blank ones.
2. [The ceremony, and the second missing arrow](02-ceremony.en) — minimal
   disclosure step by step, and why the verifier never calls the issuer back.
3. [The standard cell, and where products are allowed to live](03-deployment.en) —
   deployment, ownership, and the adapter layer.
4. [The drill, and the contract this series kept deferring](04-partition-drill.en)
   — what the design does when the link is down, and what every attempt records.

Each figure is published as an essay and a self-contained SVG. The SVG sources are
in this repository; the figures state invariants, and the essays carry the
reasoning. They are meant to be read together.

---

© 2026 Takaaki Suzuki · [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)
