# Core Loop Tuning Protocol v1.0 — v2.1 founding case
Date: 2026-11-11. Status: working developer methodology; not a scientific validation.

## v2.0 → v2.1 reported tuning
| Setting | Before | After | Evidence caveat |
|---|---|---|---|
| Founding scaffold build-time index | 100 | 67 | ~33% reduction, indexed from build notes, not independently clocked |
| Assigned march | 1.0× patrol | 1.6× patrol | Configured +60% speed; completion-rate effect not measured |
| Orders | Day only | Day and night until scaffold completed | Behavior reported in build notes |
| Talk reach | Original | Wider | No recorded numeric radius |
| Satellite Station construction | Original | Faster | No recorded numeric rate |
| Assigned-hand construction bonus | Original | Larger | No recorded numeric rate |

Gold ◆ above assigned ants, arrival toast and Colony Log entry provide state visibility. Founder reported Nov 11 hands-on confirmation that gold diamond is visible and assignment/homepage flow worked. This is not full QA.

## Root-cause stack for “ants don't go”
1. Day gate: assign near dusk → no march; fixed by keeping active assignments through night.
2. Patrol pace: apparent inaction during long walks; changed ordered speed to 1.6×.
3. Recovery pull: mid-route return to nest; updated logic to allow active trip to finish. Recovering ants remain ineligible for new orders, preserving the Constitution.

Do not assume fixing only one cause resolves a multi-cause user symptom.

## Every future pass: six-step loop
1. Play like a player with actual controller/touch/keyboard and normal save.
2. Spot the **exact** moment and context of friction; note expected vs actual behavior.
3. Stack possible causes; label confirmed causes separately from hypotheses.
4. Tune small and specifically; retain before/after setting and justification.
5. Verify in hands; run regression checks beyond the originally affected interaction.
6. Graph numeric evidence, log the result and carry the baseline forward. Repeat from step 1.

## Regression checklist
- [ ] Enter colony, save/resume, and assign at daytime and dusk/night
- [ ] Recovering ant cannot receive order; active trip not incorrectly interrupted
- [ ] ◆ visible on correct ant; scaffold completes, order releases, toast/log fire
- [ ] Talk targeting works at new reach without targeting wrong ant
- [ ] Keyboard/mouse, controller, and mobile/touch checked where supported
- [ ] English/Spanish labels, UI, toasts and Colony Log checked after v2.2 localization
- [ ] Night watch, performance, and prior save compatibility checked
- [ ] Record pass/fail/skipped, environment, build revision, and outstanding defects

## Next-pass log
```text
LOOP TUNING LOG — v__.__  | Date: ____ | Commit/build: ____
Device/input/session context: ____
Founding scaffold build-time index (v2.0=100): ____
Assigned march multiplier: ____
Assignments completed / attempted / blocked: ____ / ____ / ____
Talk misses / attempts: ____ / ____
Observed elapsed times, test conditions, sample size: ____
Friction, expected vs observed: ____
Cause stack (confirmed vs hypotheses): ____
Change made (before → after): ____
Regression pass/fail/skipped: ____
Hands-on verdict / open issues: ____
Graph updated (numeric data only)? Y/N
```

## Interpretation
The build-time index is not an observed stopwatch measurement. The 1.6× movement setting is not a measured 60% gain in successful assignments. Do not invent precise effects for Satellite Station, talk range, or bonus. Use traceable measurements and sample sizes in future evaluations. Multiple simultaneous changes cannot be assigned independent causal impact without controlled follow-up.

**Sources:** Anthony's supplied Interstellar Ants Core Loop Data (Nov 11, 2026), v2.1 build notes as described there, and reported founder playtest. v2.2 devlog: https://interstellarg0.itch.io/interstellar-ants/devlog/1769365/v22-the-colony-speaks-spanish
