# How To Review

## Fast Review Path

If the reviewer only has 10 to 15 minutes:

1. Read `briefing/01_EXECUTIVE_SUMMARY.md`
2. Open `briefing/02_CANDIDATE_SUMMARY.md`
3. Inspect the four final CIF files in `evidence_bundle/computational_repro_bundle_2026-03-23/cif/`
4. Read `evidence_bundle/computational_repro_bundle_2026-03-23/README.md`

## Deeper Technical Review Path

If the reviewer wants to audit the logic rather than just inspect the outputs:

1. Read the campaign in `evidence_bundle/computational_repro_bundle_2026-03-23/context/hydra-one-campaign_4292e1d9-f2d8-44f9-8f0e-cecb7fa360b2.json`
2. Read the readiness review in `evidence_bundle/computational_repro_bundle_2026-03-23/context/hydra-one-readiness-review_c3665104-fd63-4ee0-a2da-f2337def338a.json`
3. Read the research packet in `evidence_bundle/computational_repro_bundle_2026-03-23/context/hydra-one-research-packet_e9c76c66-ca57-4f36-a6a5-4977703d6338.json`
4. Read the target dossier in `briefing/target-dossier.json`
5. Check `manifest.json` and then follow `seed -> relaxation -> cif` for any candidate of interest
6. Optionally run `node scripts/reproduce_bundle_outputs.mjs` in the evidence bundle

## Suggested Questions For A Professor

- Does the candidate ranking make sense given the stated target constraints?
- Are the selected material families scientifically plausible as a bounded exploration set?
- Is the surrogate structure packaging honest and useful enough for external review?
- Which follow-on step would add the most scientific credibility: stricter simulation, literature-backed seeds, or wet-lab collaboration?
- Which candidate family is the best next focus under the current green-hydrogen framing?

## What A Reviewer Can Safely Conclude

- the target framing is explicit
- the scoring and ranking outputs are inspectable
- the top candidates are clearly identified
- the structure artifacts are provenance-linked and reproducible as computational outputs

## What A Reviewer Should Not Infer

- that these are experimentally validated catalyst structures
- that the materials are ready for synthesis
- that the packet implies performance claims in a real electrolyzer stack
