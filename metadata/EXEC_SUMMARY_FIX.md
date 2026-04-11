# Corrective Executive Summary

- Iteration 1 file count correct: yes (29 assets).
- Semantic mistakes found:
  - Iteration 1 mixed explicit language editions with a non-language bucket even when filename language markers were visible.
  - Iteration 1 did not separate the cover image cleanly from language deliverables in the release-grade matrix.
  - Iteration 1 underreported version drift and naming drift at release-packaging level.
- Correct number of language editions: 7.
- Correct per-format counts: md=7, pdf=7, epub=7, fb2=7, png=1, other=0.
- Real blockers before repo creation:
  - ru version drift: md/pdf/epub are v1.0 while fb2 is v1.1.
  - es version drift: master md is v1.0 while exports are v1.1.
  - en version drift: master md is v1.0 while exports are v1.1; English PDF also has a (1) copy suffix.
  - zh-CN version drift: master md is v1.0 while exports are v1.1; master naming family also drifts from export family.
