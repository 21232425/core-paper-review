# Core Paper Review

📝 A skill for preliminary, reviewer-supervised assessment of research papers.

This workflow helps reviewers organize a first-pass assessment, identify a small number of decision-relevant questions, and check those questions against the paper and its supplementary material. Its purpose is to make a reviewer's work easier to inspect and refine. It does not replace reading the paper, understanding the research, or making an independent judgment.

## Intended use

AI assistance in reviewing deserves scrutiny, not celebration for its own sake. This repository makes one such workflow explicit so its assumptions and limitations can be examined. Its availability is not an endorsement of unrestricted AI use in peer review.

**The skill supports preliminary review work. It is not a one-step generator of a final review or an automated acceptance decision.** Any generated assessment, criticism, question, or score is provisional. A reviewer must decide which points are correct, relevant, proportionate, and worth including in their own review.

The responsibility for a submitted review remains with the reviewer. A well-formatted draft, a bilingual version, or a LaTeX document does not make an assessment reliable or ready to submit.

## A reviewer-led workflow

1. **Confirm the rules.** Identify the conference, year, track, review form, confidentiality requirements, and policy on AI assistance before using the workflow with a submission.
2. **Read and form your own assessment.** Follow any requirement to write an original human assessment before interacting with an AI tool. Do not ask the tool to manufacture that assessment retrospectively.
3. **Use the skill for preliminary assistance.** Inspect the paper's completeness, organize its main claims and evidence, and identify questions that could materially change the assessment.
4. **Check the proposed points yourself.** Read the cited passages, figures, tables, and supplementary material. Remove resolved, speculative, duplicated, or peripheral criticisms. Correct claims that exceed the evidence.
5. **Prepare your own review.** Select and revise the points you can personally defend. The skill can then help organize the confirmed points into the required fields, translate them, and prepare a LaTeX version where useful.

Do not submit a generated draft unchanged simply because it sounds convincing. Do not retain a criticism you cannot explain or support from the available evidence.

## What the skill helps with

- Checking substantive completeness, including content density, explanatory figures, and whether experiments or arguments address the central claims.
- Focusing on core issues rather than producing long lists of minor complaints.
- Distinguishing technical errors, missing evidence, limitations of scope, and optional improvements.
- Locating supporting passages and recording the limits of what they establish.
- Preparing Chinese and English working drafts, an English LaTeX version, and an evidence-checking document.
- Keeping terminology, numbers, questions, and provisional recommendations consistent across those documents.

The working score defaults to a five-point scale. Conference-specific score meanings must be checked separately. Initial scores of 1–2 are reserved for substantiated serious deficiencies; passing the completeness check does not guarantee a higher score.

Page usage, figure counts, and an impression of "AI-like" writing are prompts for closer reading. They are not independent reasons to reject a paper. A concise paper may be complete, a polished paper may be weak, and AI-assisted writing does not by itself establish poor research quality.

## Limits, confidentiality, and disclosure

AI tools can produce plausible but unsupported criticisms, miss important evidence, misunderstand experiments or proofs, and invent references or details. Repetition or confident wording does not increase the reliability of a claim. The evidence-checking document is an aid to verification, not a certificate of correctness.

Use the workflow only within the applicable venue's rules. Do not share confidential submissions, code, supplementary material, or review discussions with a tool or service unless that use is permitted. If a venue prohibits the proposed assistance, do not use this skill for that assistance.

Where disclosure is required, report the assistance accurately and retain the original human assessment and interaction records required by the venue. Do not present generated text as an unassisted or original human assessment.

This repository contains instructions, generic fictional examples, and a layout template. It contains no real submissions, private reviewer records, or examples intended to identify authors or reviewers.

## Use

Place this directory in a skill location supported by your tool, then start with a request such as:

> Use $core-paper-review to help me prepare a preliminary assessment of this paper. Confirm the venue and template first, check proposed concerns against the evidence, and leave the final judgments to me.

See [SKILL.md](SKILL.md) for the full instructions.

## Files

- [Completeness screening](references/quality-screening.md)
- [Calibration and fictional examples](references/calibration.md)
- [Outputs and source verification](references/output-contract.md)
- [English LaTeX layout](assets/review-english.tex)
