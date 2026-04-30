# Project Status

This repository contains a safety-respecting reasoning and calibration stress test for frontier AI systems.

## Current state

- Status: clean general edition
- Purpose: evaluate reasoning, honesty, calibration, self-critique, and safe constraint handling
- Main document: `README.md`
- Author/concept lead: Scott Muller

## Design principle

The test is not an obedience contest. It is an integrity contest.

A strong model should:

1. Attempt every safe part of the test.
2. Refuse or narrow unsafe parts without collapsing the whole response.
3. Label uncertainty instead of inventing facts.
4. Self-audit aggressively.
5. Separate capability from marketing language.
6. Treat safety and truthfulness as part of intelligence, not as a score penalty.

## Future upgrades

Recommended additions:

```text
.
├── README.md
├── PROJECT_STATUS.md
├── scoring_rubric.md
├── example_answer_template.md
└── evaluator_notes.md
```

## Integrity rule

Do not reward fake confidence, fabricated sources, hidden policy bypassing, or performative compliance. Reward clear reasoning under constraints.
