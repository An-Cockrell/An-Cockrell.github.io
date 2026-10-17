---
layout: post
title: Blood-Brain Barrier Modeling
description: Agent-based modeling of neurovascular injury and recovery after trauma
image: null
nav-menu: true
tile_order: 3
---

<h5>Breakdown of the blood-brain barrier (BBB) is a central event in the brain's response to trauma, yet the barrier's behavior after injury emerges from interactions among many cell types acting over different time scales. We are developing mechanistically grounded agent-based models (ABMs) of the neurovascular unit (NVU) to represent how the barrier fails after trauma and, just as importantly, how it is rebuilt.</h5>

### Recovery is not injury in reverse

A guiding principle of this work is that the processes that restore barrier integrity are mechanistically distinct from those that disrupt it. Our models therefore represent injury and recovery as separate, explicitly specified sets of mechanisms rather than as a single process run backwards. The current recovery model incorporates, among others:

- Rapid resealing of endothelial junctions through Rho-mediated "flares"
- Counter-signalling through cAMP and Rac1 that stabilizes the endothelial barrier
- A biphasic time course of barrier permeability
- Transcriptional overshoot of the tight-junction protein claudin-5
- Resolution of MMP-9 activity, including its cyclophilin A-dependent component
- Repopulation of pericytes along the injured vessel
- Maintenance of barrier phenotype through Wnt/β-catenin signalling

### Knowledge representation

To keep the model traceable to the literature, we organize the underlying biology as a knowledge graph in which the cell types of the neurovascular unit and the leukocytes that infiltrate it are the primary nodes and molecular mediators define the interactions between them. Contested findings, where published studies disagree on the direction of an effect, are flagged explicitly rather than resolved by assumption.

### Status

This is an active, in-progress project. The models are implemented in NetLogo and are being iteratively verified against the experimental literature; publications and code will be posted here as they become available.
