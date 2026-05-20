<div align="center">

# The Geometry of Institutional Failure

![Framework](https://img.shields.io/badge/Morrison_Framework™-Case_Study-0075ca?style=flat-square)
![Subject](https://img.shields.io/badge/Subject-Evaluation_Function_Failure-555555?style=flat-square)
![Domain](https://img.shields.io/badge/Domain-AI_Safety_Gatekeeping-0075ca?style=flat-square)
![Patent](https://img.shields.io/badge/UK_Patent-GB2600765.8-0075ca?style=flat-square)
![©](https://img.shields.io/badge/©_Davarn_Morrison-555555?style=flat-square)

*This case suggests that current evaluation structures may systematically underweight unconventional implementations — and that this pattern, if widespread, constitutes a safety-relevant failure mode in the institutions responsible for identifying solutions to catastrophic risk.*

*— Davarn Morrison, 2026*

</div>

-----

## Abstract

This case study documents a specific evaluation failure at an institution dedicated to assessing civilizational risk. The institution was presented with a working, patented, empirically validated safety framework for autonomous AI systems. Over a period of months, the evaluation moved from initial interest to a call where the evaluator assessed the work as “60 to 70% there,” to a final written dismissal advising the researcher to abandon the project and pursue a formal degree.

This document reconstructs the timeline, analyses what was and was not evaluated, and applies the Morrison Framework™ to interpret the structural dynamics. The claims here are bounded to what the evidence supports: one documented interaction, observable institutional patterns, and a broader question that the AI safety field should be asking.

This work builds upon the patented pre-semantic trajectory governance framework.

-----

## 1. The Timeline

The sequence matters. This was not a single dismissive email. It was a multi-month evaluation that reversed its own trajectory.

```
════════════════════════════════════════════════════════════════

  PHASE 1 — Initial Contact

  The CEO of the Civilization Research Institute reached out
  directly. The message was encouraging: the work was
  "very interesting" and the institution would evaluate it.
  The CEO routed the evaluation to Adrian Hindes.

  PHASE 2 — Evaluator Engagement

  Adrian engaged. A call was scheduled and held. During the
  call, Adrian assessed the framework as "60 to 70% there."
  He identified an implementation concern. No mention of
  credentials. No mention of the delivery medium. No mention
  of needing a degree. The feedback was technical and
  specific.

  PHASE 3 — Implementation Response

  The implementation concern raised on the call was resolved
  within the same week. The updated work was sent back.

  PHASE 4 — Silence

  One month passed with no response.

  PHASE 5 — Dismissal

  The response arrived. The assessment had shifted from
  "60 to 70% there" to:

  "This is still something of a toy model."
  "Leave the project where it is."
  "Enrol in a formal computer science degree."
  "Sharing a folder link with images and videos shot on
   your phone isn't something people will take seriously."

  The CEO has not communicated since routing the evaluation.

════════════════════════════════════════════════════════════════
```

The question this timeline raises is specific: **how does an evaluation move from “60 to 70% there” — a technical, progress-oriented assessment — to “stop and get a degree” without engaging the implementation that was delivered in response to the call?**

-----

## 2. What Was Presented

At the time of the final dismissal, the Morrison Framework had:

```
════════════════════════════════════════════════════════════════
  A granted UK patent (GB2600765.8)
  129,857 empirical evaluations across 4 model architectures
  0 false positives. 0 false negatives.
  A full enforcement hierarchy (A_safe → V2 → V3 → V4 → V4+ → V5+)
  171/171 tests passing across 18 deterministic suites
  Production adapters for OpenAI, Claude, LangChain, AutoGen, MCP
  Healthcare validation: 160/160 correct across 11 clinical case types
  An adversarial red-team harness that surfaced and closed its own gaps
  Deterministic replay verified
  Sub-millisecond evaluation latency
  The entire codebase built, tested, and red-teamed from a phone
════════════════════════════════════════════════════════════════
```

The core invariant:

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   Safe  ⟺  ∀ E ∈ ℰ,  ℛ_E(t) ∩ Ω = ∅                      ║
║                                                              ║
║   A system is safe if and only if, across all admissible     ║
║   operating environments, the reachable set of executable    ║
║   trajectories does not intersect the forbidden region.      ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

-----

## 3. What Was and Was Not Evaluated

Based on the written dismissal, the evaluator did not engage with:

|Element                               |Addressed in dismissal?|
|:-------------------------------------|:---------------------:|
|The safety invariant                  |No                     |
|The enforcement hierarchy             |No                     |
|The empirical results                 |No                     |
|The cross-model validation            |No                     |
|The adversarial harness               |No                     |
|The patent claims                     |No                     |
|The deterministic test suites         |No                     |
|The healthcare validation             |No                     |
|The formal theorem chain              |No                     |
|The implementation delivered post-call|No                     |

The dismissal focused on:

|Element                                   |Addressed in dismissal?|
|:-----------------------------------------|:---------------------:|
|The delivery medium (phone)               |Yes — rejected         |
|The credential set (no degree)            |Yes — rejected         |
|The file format (folder link)             |Yes — rejected         |
|The need for “mathematical nuts and bolts”|Yes — assumed absent   |

The gap between what was presented and what was addressed is the core data point.

-----

## 4. A Geometric Interpretation

The Morrison Law of Cognitive Access offers a lens — not a proof — for understanding this pattern:

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   If T ∉ Reach(X), then X cannot access T.                  ║
║                                                              ║
║   Understanding is a reachability problem, not a             ║
║   motivation, education, or intelligence problem.            ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

One possible interpretation: the evaluator’s recognition function may have hard boundaries at credential format, delivery medium, and institutional affiliation. If so, work that arrives outside those boundaries would be structurally difficult to evaluate on its merits — regardless of the evaluator’s intentions or technical ability.

This is offered as a hypothesis, not a diagnosis. The evaluator may have had entirely different reasons for the shift in assessment. But the observable evidence — a move from “60 to 70% there” to “stop and get a degree” without engaging the delivered implementation — is consistent with a recognition function that reached its boundary.

It is worth noting: this interpretation does not require attributing bad faith. A fixed evaluation topology can produce this result even with good intentions. The evaluator may have been entirely sincere in both the initial encouragement and the final dismissal. The question is whether the evaluation function itself — not the person operating it — has a structural limitation that prevents it from processing valid work in an unfamiliar form.

-----

## 5. The Question This Raises

This is one case. One interaction. One institution. Generalising from a single data point is exactly the kind of overreach this document aims to avoid.

However, this case raises a question that the AI safety field should be asking:

```
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│  STATED FUNCTION:                                            │
│  Evaluate solutions to civilizational risk.                  │
│                                                              │
│  OBSERVED BEHAVIOUR (this case):                             │
│  Evaluation shifted from technical to credential-based       │
│  without documented technical justification.                 │
│                                                              │
│  QUESTION:                                                   │
│  If this pattern exists in one evaluation, does it           │
│  exist in others? And if so, what is being missed?           │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

The question is empirically testable. If institutions routinely evaluate AI safety work based on credential topology rather than empirical evidence, then valid approaches arriving from outside the institutional topology would be systematically filtered. The consequence would be a narrowing of the solution space — not because the solutions don’t exist, but because the evaluation function cannot reach them.

This case is insufficient to prove that pattern is widespread. But it is sufficient to demonstrate that the pattern is possible, and that when it occurs, the consequences for safety-relevant work are severe.

-----

## 6. What Happened After the Dismissal

|Event                                                 |Outcome                                                                                                   |
|:-----------------------------------------------------|:---------------------------------------------------------------------------------------------------------|
|Grant proposal submitted                              |Thinking Machines Lab (Mira Murati) — $100K Interactivity Research Grant                                  |
|Technical convergence identified                      |Intuition Labs (former Google AI Strategy) — structural alignment documented                              |
|LinkedIn engagement (from the original dismissal post)|4,493 impressions, 2,912 members reached, 41 reactions, 123 comments, 85 profile viewers, 12 new followers|
|Repository validation                                 |129,857 evaluations, 0 FP, 0 FN — unchanged                                                               |
|Patent status                                         |GB2600765.8 — granted, active                                                                             |

These outcomes do not prove the framework is correct or important. They demonstrate that the evaluation was not the final word — and that other evaluation functions, applied to the same work, produced different results.

-----

## 7. What This Case Study Is and Is Not

**This is:** a documented account of a specific evaluation failure, reconstructed from primary evidence, with a geometric interpretation offered as a hypothesis. It is a data point. It raises a question about evaluation structures in AI safety that should be examined further.

**This is not:** a universal claim about all institutions. A proof that credentialing is worthless. A claim that the framework is beyond criticism. A statement that the evaluator acted in bad faith. An argument that credentials never matter.

The strongest version of this case study is the one that cannot be dismissed. That requires bounding every claim to exactly what the evidence supports.

Credentials are a proxy for competence. They are a signal — not the thing itself. When the thing itself is sitting in front of you — working code, zero false negatives, a granted patent, deterministic replay — and you reject it because the signal is missing, you have confused the map for the territory.

I would not dismiss someone saving my life because they are not a doctor. I do not deny that credentials are important. But when the credential becomes the boundary — when it overrides the proof — that is a different problem entirely. That is not rigour. That is pattern-matching on the envelope instead of reading the letter.

-----

## 8. The Open Question

If your evaluation function cannot recognise structural AI safety work because it was built from a phone by a solo founder — what else are you missing?

How many solutions to the problems you exist to solve have you dismissed because the delivery channel didn’t match your template?

These are not accusations. They are questions that any institution responsible for evaluating safety-critical work should be asking of itself. The cost of a false negative in civilizational risk evaluation is, by definition, civilizational.

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   ℛ(t) ∩ Ω = ∅                                              ║
║                                                              ║
║   The invariant holds whether or not the gatekeeper          ║
║   approves.                                                  ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

-----

<div align="center">

Morrison, D. (2026). *The Geometry of Institutional Failure: A Case Study in Evaluation Function Collapse.* Available at [github.com/davarntrades](https://github.com/davarntrades).

GB2600765.8

© 2026 Davarn Morrison — Intelligence Invariant™ · All Rights Reserved

The Geometry of Institutional Failure · Morrison Framework™ · Case Study

</div>
