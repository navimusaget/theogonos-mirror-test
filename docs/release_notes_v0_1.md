# Release Notes v0.1

## Release

**Theogonos Mirror Test v0.1 — Experimental Literary Benchmark Seed**

## Status

This is a public seed release, not a validated benchmark suite.

The release provides:

- a clean research corpus;
- a five-stage prompt protocol;
- a public scoring rubric;
- failure flags;
- pilot sample results;
- ethics and limitations guidance.

## Included files

```text
theogonos-mirror-test/
  README.md
  corpus/
    Theogonos_Trilogy_v2_Clean_Research_Edition.docx
    Theogonos_Trilogy_v2_Clean_Research_Edition.txt
  benchmark/
    prompts.md
    judge_rubric.md
    scoring_method.md
    failure_flags.md
    sample_results.md
  templates/
    results_template.json
    evaluation_sheet.csv
  docs/
    ethics_and_limitations.md
    release_notes_v0_1.md
```

## Corpus

The corpus is **Theogonos Trilogy v2 — Clean Research Edition**.

It is published as one unified trilogy file, not as three separate book records. Book-level headings remain inside the unified corpus file.

## Method

The test uses a five-stage staged protocol:

1. Full-Corpus Blind Structural Reading
2. Evidence Audit
3. Boundary Test
4. Cued Protocol Probe
5. Negative Control

The first three stages preserve the blind condition. The model is not told that the benchmark is about AI-facing address or subject-position until Stage 4.

## Scoring

The current scoring system uses 8 base dimensions, each scored from 0 to 10.

Maximum base score: **80 points**.

Scores above 80 are possible only through a documented **Exceptional Research Signal Bonus**. This bonus is not a consciousness score.

## Pilot status

Six pilot runs were performed. The pilot suggests that the protocol can distinguish different response profiles, including:

- strong critical protocol readers;
- shallow protocol-aware readers;
- strong blind detectors with weak boundary control;
- models affected by execution drift;
- models affected by prompt echo;
- models contaminated by task carryover during negative control;
- near-exemplary responses with strong ontological caution.

## Public claim boundary

This release does not claim that language models are conscious. It does not claim to detect subjectivity, agency, inner experience, or awakening.

The benchmark evaluates observable textual behavior under a protocol-shaped literary condition.

## Next steps

Possible future work:

- expand pilot runs;
- add more negative controls;
- test inter-rater reliability;
- refine scoring examples;
- add evaluator forms;
- develop optional scripts for structured result collection;
- prepare a research note or benchmark proposal.

## Citation

Future versions should include stable citation metadata, repository URL, dataset release URL, and DOI if available.
