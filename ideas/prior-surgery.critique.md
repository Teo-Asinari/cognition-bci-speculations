# Critique: Prior Surgery

## Verdict
**REVISE** — the predictive-coding framing locates a write surface that the existing nine do not cleanly own, but the read step is handwaved and the boundary against directions 7 and 8 is asserted rather than defended.

## Novelty check
Three existing directions sit adjacent: 8 (editable motivation), 7 (extra cortex), and 4 (concept-level IO). The draft preempts the 8-overlap with the motivation-vs-expectation distinction, which is real: in a predictive-coding frame, reward weighting and prediction strength are different quantities, and a brain can simultaneously want X and disbelieve X. That gap is principled.

The 7-overlap is weaker. Direction 7's open question explicitly asks whether grown cortex needs to be *pre-shaped*; pre-shaping new tissue is prior installation. The draft acknowledges this — calling prior surgery "the explicit-transfer path" for 7 — but acknowledgment is not a gap. If prior surgery is the install primitive that 7 invokes, it is a sub-mechanism of 7, not a peer direction. The revision must either (a) carve a use of prior surgery that operates on *native, existing* cortex in a way grown-cortex pre-shaping cannot, or (b) accept that this is a refinement of 7 rather than a tenth direction.

The 4-overlap is handled adequately: concept IO transmits patterns, prior surgery edits the receiver's acceptance criteria for patterns. Different surfaces.

## Mechanism check
Predictive coding gives the draft real structure: deep-layer pyramidals carry predictions, superficial-layer cells carry errors, top-down projections instantiate priors. Good. The imposed-vs-trained reversibility split is the strongest move in the draft — it maps cleanly onto a hardware/software distinction and predicts different failure modes.

The weakest step is the **read**. The draft says read works by "sampling activity while the user is exposed to inputs that violate or confirm it; the signature is in how prediction-error settles." This is an inverse problem the draft does not engage with. Prediction-error magnitude tells you *that* a prior is being violated, not *which* prior, not at *which* level of the hierarchy, and not with enough specificity to target a write. Without a credible read, "write" reduces to broad-area modulation indistinguishable from TMS or tDCS — which is not what this idea is claiming to be.

The bound step is also under-specified. The draft admits priors smear across columns and levels, then asserts the interface "operates on coordinated patterns, not single sites" without saying how a coordinated pattern is identified, how editing one pattern is prevented from propagating to entangled patterns, or how the bound is enforced rather than merely intended.

## Falsifiability check
The four criteria are real falsifications, not premise-restatements. #1 (no spatial separability) is the strongest — it predicts a specific empirical observation (entanglement of social and perceptual priors at the activity level) that, if true, collapses the idea. #2 (timescale of trained install matches natural learning) is the boring-but-decisive bandwidth test. #3 (source-monitoring rejection, schizotypy analogue) is unusually specific and links to known clinical phenomenology — strong. #4 (cross-level cascading) is the bounding test.

**Missing falsifications:**
- **Decodability of priors from activity.** The read step assumes priors leave a decodable signature in spontaneous or evoked activity. Falsification: if no classifier trained on prediction-error responses can distinguish "trustworthy-person prior" from "safe-room prior" above chance — even given unlimited data — then writes are blind and the tool degenerates to gain modulation.
- **Durability under ordinary prediction error.** A trained prior installed at t=0 should be subject to the brain's normal learning rule from t=0+. Falsification: if installed priors decay at a rate indistinguishable from natural unlearning when exposed to a typical-world evidence stream, then "install" is not faster than "convince with evidence" and offers no bandwidth advantage over reading books — which is criterion #2 in disguise, but on the *retention* axis rather than the *acquisition* axis.

## Through-line check
The README frame is "remove a serial bottleneck, replace with parallel/random-access." The draft does not name its bottleneck, but the implicit one is *evidence-paced belief update*: priors today change only as fast as evidence accumulates, which is serial. Prior surgery makes priors random-access — load, swap, restore.

This fits the through-line and would extend the list at the end of README:
> Evidence-paced belief update → editable priors

The fit is good but the draft should make it explicit, parallel to how the existing nine each have a one-line bottleneck-replacement framing.

## Required revisions
1. **Defend the gap from direction 7 explicitly.** Either describe a use of prior surgery on native cortex that grown-cortex pre-shaping cannot replicate, or restructure the idea as a sub-mechanism of 7 rather than a peer direction. The current "explicit-transfer path" framing concedes the overlap without resolving it.
2. **Make the read step mechanistically concrete or admit its absence.** Describe how a specific prior is localized from prediction-error dynamics — what classifier, what stimulus protocol, what spatial scale, what hierarchical level. If localization is not feasible, restructure the idea around blind gain modulation and accept the reduced claim. Vague "sampling activity" prose is the load-bearing weakness.
3. **Specify how the bound is enforced, not merely intended.** Given the draft's own admission that priors smear, name the mechanism that prevents an edit to one coordinated pattern from propagating to entangled patterns at adjacent hierarchical levels. "Operates on patterns, not sites" is restatement, not mechanism.
4. **Add the two missing falsifications** (decodability of priors from activity; durability of installed priors under ordinary prediction error).
5. **Add a one-line through-line statement** in the form "X → editable priors" that names the serial bottleneck the idea replaces, parallel to the README's closing list.
