# Prior Surgery

## Premise

The brain runs the world as a Bayesian generative model. Beliefs update slowly, opaquely, and asymmetrically — priors learned in childhood often outlive every adult experience that contradicts them. Direct write access to the cortical prediction hierarchy turns prior-editing into a deliberate act: clear a stuck assumption, install an unfamiliar one for the duration of a task, run inference under a prior different from the one your history would produce. The amplification is not memory or motivation. It is the ability to think under chosen expectations.

## Mechanism

Predictive coding locates the priors of perception and cognition in the top-down projections of the cortical hierarchy. Deep-layer pyramidal cells carry predictions; superficial-layer cells carry prediction errors. The prior at any point in the hierarchy is a learned function of synaptic weights on those top-down projections. To edit a prior is to modify those weights, transiently or permanently, in a targeted region.

The interface needs to read, write, and bound. Read locates a prior by sampling activity while the user is exposed to inputs that violate or confirm it; the signature is in how prediction-error settles. Write modulates top-down projections in the implicated columns, either through optogenetic-style targeting of layer 5/6 pyramidals or through electrical patterns calibrated to shift effective gain. Bound limits the edit to a hierarchy level (sensory, semantic, social) and a time window. The hard problem is that priors are not localized switches; they smear across columns and across levels. A useful interface operates on coordinated patterns, not single sites.

Reversibility splits the design into two regimes. Imposed edits — transient gain shifts that decay when stimulation ends — give clean reversibility but demand continuous hardware support. Trained edits — synaptic changes induced through artificial prediction-error injection that recapitulates the brain's own learning rule — persist, but are harder to remove than to install. Most workloads probably want imposed-by-default with explicit promotion to trained.

A working interface lets a user say: for this conversation, run my social inference under priors that do not include my history with this person. Or: for this session, install priors typical of a topologist. The user remains the inferring agent. What is edited is the model their inference runs under.

## Composition

The closest pairing is with direction 7 (extra cortex): grown cortex is blank and acquires priors by use or by transfer, and prior surgery is the explicit-transfer path. It also composes with 4 (concept-level IO), where transmitted activation patterns arrive in formats the receiver's priors reject as noise; a prior-edit during transmission lets the pattern stick. With 5 (parallel subagents), each thread can run under different priors — a research subagent investigating an idea under its strongest priors and its weakest simultaneously. The composition is distinct from 8 (editable motivation): motivation is what you want, priors are what you expect. You can want a result you cannot bring yourself to believe in, and vice versa. These are different write surfaces in the brain.

## What would falsify it

- If priors at any useful level of abstraction turn out not to be spatially separable — the prior over "this person is trustworthy" lives in patterns indistinguishable from "this room is safe" — then targeted edits collapse into mood modulation and the idea reduces to direction 8.
- If installing a trained prior requires a duration comparable to natural learning (years for stable social priors, months for technical-domain priors), the bandwidth advantage vanishes and the tool offers no improvement over reading books.
- If the brain has hard self-source-monitoring checks that flag artificially-induced prior shifts as alien — the failure mode that produces schizotypal symptoms when endogenous signals are misattributed — edits do not integrate; they sit as foreign thoughts the user routes around.
- If prior shifts at one hierarchical level always cascade unpredictably downstream — a social prior edit reshapes visual face perception, a perceptual prior edit reshapes semantic categories — then the bounding requirement cannot be met and the tool is unusable in practice.

## Open questions

- What is the smallest editable unit: a single prior, a coherence class of priors, or the entire generative model. The answer determines whether the tool is scalpel or sledgehammer.
- Does running inference under non-native priors produce conclusions the user endorses after prior-restoration? If the topologist-prior version of you reaches a result the default version cannot reconstruct, who is the author of the result?
- Can edits be audited? Does the brain leave traces of an externally imposed prior, or relabel it as native? If the latter, the user cannot distinguish learned belief from imposed belief.
- Is there a principled way to expose the current prior to the user before letting them edit it? Editing what you cannot see is a different operation than editing what you can.

## Risks

- Adversarial prior installation. An interface that can install a topologist's priors can install a believer's priors. Cult mechanics with a wetware lever.
- Coercion at the level of expectation. Propaganda today has to defeat priors. With prior-edit access, it bypasses them. The defensive posture has to move down a layer of the cognitive stack.
- Worldview lock-in via convenience edits. A user who routinely edits out skepticism for productivity loses the practice that distinguishes belief from convenience belief.
- Differential auditability. If installed priors feel native, the user cannot tell which beliefs are theirs, and so cannot consent to retaining one rather than another.
- Inheritance via shared prior libraries. A standard "engineer's priors" package distributed in a developer toolchain quietly homogenizes a discipline's expectations, with the homogenization invisible to participants.
