# Shared Motorola device-tree branches

| Branch | Purpose |
| --- | --- |
| lineage-23.2 (default) | LineageOS 23.2 shared configuration, including merged mona hybrid bring-up work from PR #1. |
| lineage-24.0 | Distinct upstream LineageOS 24.0 development history, preserved unchanged; mona hybrid changes are not claimed to be ported or tested here. |

On 2026-10-31, PR #1 was merged with a normal merge commit to retain the exact original agy commits. Redundant lineage-23.2-mona and lineage-23.2-mona-agy branch pointers were removed only after checking their tips were ancestors of lineage-23.2. All changes, original authorship, credits and validation/limitation documentation remain in history. lineage-24.0 diverges from lineage-23.2 and was kept rather than combined with an incompatible platform version.

Use device/motorola/mona from the companion repository's lineage-23.2 branch with this tree. See docs/bringup-20261028/PUBLICATION.md for the tested stock-vendor hybrid scope and known limits, including the permissive ATEL service domain. This consolidation is not a new build or hardware validation. No executable code was changed beyond integrating the already published PR.

Codex performed this consolidation at sammyz's request. Original agy, LineageOS, moto-sm8450 and other contributor credits remain intact.
