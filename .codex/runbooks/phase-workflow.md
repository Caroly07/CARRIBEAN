# Codex Phase Workflow

This workflow maps the Kiro-native process to Codex execution.

## Phase map

### Phase 0 — Discovery
- Source material: `.kiro/specs/phase-0-discovery/*`
- Output: `DISCOVERY_SUMMARY.md`
- Goal: gather business context, regulatory constraints, infrastructure facts, and modernization objectives.

### Phase 1 — Codebase Analysis
- Source material: `.kiro/specs/phase-1-codebase-analysis/*`
- Output: `ASSESSMENT.md` per app + `CONSOLIDATED_ASSESSMENT.md`
- Goal: produce factual architecture assessment, 7 R's classification (Retain/Retire/Rehost/Replatform/Refactor/Rearchitect/Rebuild tagged [Tactical]/[Strategic]), and cross-application coupling analysis.

### Phase 2 — Pain Points
- Source material: `.kiro/specs/phase-2-pain-points/*`
- Output: `PAIN_POINTS.md`
- Goal: prioritize user pain, operational friction, and business impact.

### Phase 3 — Target Architecture
- Source material: `.kiro/specs/phase-3-target-architecture/*`
- Output: `TARGET_ARCHITECTURE.md`
- Goal: rationalize the application landscape first (should apps be consolidated/retired?), then define future-state architecture with modern capabilities opportunity scan, buy-vs-build decisions, SEO/AI discoverability strategy, red team critique on every major decision, and [Tactical]/[Strategic] tags.

### Phase 4 — Modernization Plan
- Source material: `.kiro/specs/phase-4-modernization-plan/*`
- Output: `MODERNIZATION_PLAN.md`
- Goal: sequence execution, estimate effort/cost with logistics multipliers scaled to org size (small 1.3-1.5x, mid 1.5-2x, enterprise 2-3x), and define risks/mitigations.

### Phase 5 — Supporting Docs
- Source material: `.kiro/specs/phase-5-supporting-docs/*`
- Outputs: `BUSINESS_CASE.md`, `DISASTER_RECOVERY_PLAN.md`, `STAFFING_RECOMMENDATION.md`, `SECURITY_REMEDIATION.md`
- Goal: complete executive and operational package.

## Session cadence
1. Re-state current phase and expected deliverable.
2. List known facts and open questions.
3. Produce/revise draft.
4. Run quality gates.
5. Stop for explicit human sign-off.

## Hook parity (manual in Codex)
- Checkpoint reminder: always pause after each phase deliverable.
- Open-questions tracker: maintain a dedicated section and unresolved items list.
- Compliance check: verify regulatory assumptions remain consistent across documents.
