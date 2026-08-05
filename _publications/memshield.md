---
title: "MemShield: A Three-Tier Retrieval-Time Defense Against Coordinated Memory Poisoning in LLM Agents"
permalink: /publication/memshield
date: 2023-03-23
venue: 'ICML 2026'
---

_**Abstract**_ -- LLM agents now lean on persistent long-term memory through retrieval-augmented generation, and that memory is an attack surface. An attacker who controls a few user accounts, an upstream feed, or a compromised internal writer can drop entries that quietly steer the agent across sessions. Existing defenses are either expensive or need white-box access, and none gives a finite-sample false-positive bound that survives a change of LLM backbone. Coordinated attacks announce themselves in metadata; existing defenses look only at content. We exploit this with \textsc{MemShield}, a three-tier retrieval-time defense. A structural detector reads batch metadata (writer overlap, temporal burst, write-context overlap) and flags coordinated poisoning at zero LLM cost. A conformal-calibrated judge handles borderline batches with a marginal FPR bound from split-conformal prediction. Clean batches pass through. The per-entry judge fails two ways. On Mistral-7B-v0.3 it saturates and collapses to zero recall; on Llama-3.1-70B it stays sharp but rarely flags individual entries (recall ). In both cases, the structural tier carries detection at  recall. Across 48 cells (4 backbones  3 retrievers  4 datasets) and 12 attacks, the composition lifts median recall from  to  at  fewer judge calls and within the conformal bound

[paper link](https://scholar.google.com/scholar?oi=bibs&cluster=7570639966316712594&btnI=1&hl=en)

