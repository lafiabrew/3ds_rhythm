# Rhythm — parallel first-release plan

## T1 — Usable first slice, not bootstrap acceptance
- Status: pending.
- Objective: Original rhythm game: one original tune/chart, stylus/button play, scoring/retry and a small chart editor.
- Areas: src/include/tests/Makefile/meta/scripts/README/specs, declared actual engine/dependencies where applicable; vendor shared journal only as reviewed dependency.
- Validation: make test && python3 -m unittest discover -s tests -p test_contract.py -v && make 3ds && make verify-3ds && git diff --check. 
- Acceptance: Audio buffers, note timing/scoring, input/reset and native NDSP lifecycle are real; calibration is measured/labeled, not imaginary hardware latency. Built-in music is original; missing DSP support is visible. Native module must be called by main, not only linked. Correct UID/artifacts, new error/retry/cleanup tests and actual own-app emitted log. Existing journal smoke preserved. Native data/device tests clearly labeled. Candidate stays in_progress after local checks until external exact-pin review.
- Demo: start real session, exercise actual controls/objective or recording/query/player, end/reset, explicitly export actual diagnostics; no synthetic runtime success markers.

## T2 — Review/API/demo/publication handoff
- Status: pending.
- Areas: exact code pin/real logs/native artifacts, review/report/doc evidence; no author moves to parent/root.
- Validation: repeat explicit T1 chain on final SHA; coordinator real Drop daemon api/logs/api/pull byte parity; current scoped RUGGED, fresh spec and quality PASS, mean atomic acceptance>=95; final docs audit. Confirm remote source SHA when coordinator publishes.
- Acceptance: source/license/privacy/genuine engine and actual behavior proved; source/evidence refs persistent. Public WIP is not accepted release. Physical tier remains separate, no phantom time/serial speedup.

## Boundaries and shared state
Read specs/app.md and AGENTS.md. User consent extends to this repo; no data upload by default. Source/failure evidence stays in durable workspace/ref, no temp-only work. Root constitution approved diagnostic journal exception only; old saves remain protected. The coordinator supplies read-only references/current image and owns timing, independent reviewers and publication. Work exactly one task/iteration; loop commits exact owned paths. Author model `gpt-6.1-sol`; source identity `0x0D3F5` / `CTR-P-RHYT`.
