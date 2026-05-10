# Cognition BCI Speculations

## Framing

Realism off. The brief is to explore what cognitive amplification looks like once substrate constraints are treated as engineering problems rather than fixed walls.

Practical BCI work today is restoration — paralysis, blindness, speech. That is the right place for clinical effort, but the design space is much bigger. This doc is the rest of the space. Each entry describes a mechanism, the open questions that gate it, and the failure modes that would matter if it shipped.

The nine directions are not independent. Several rely on the same primitive — high-bandwidth read/write to cortex with biocompatibility on a decade timescale — and several compose with each other in obvious and non-obvious ways.

## 1. New senses

**Mechanism.** Map an arbitrary signal — EM fields, network telemetry, soil moisture, the position of every screen showing your name — into stimulation patterns the brain learns to interpret as a sense. Animal studies show cortex remaps around novel modalities within months. Extension to human users is gated by stimulation safety and bandwidth, not by representational capacity.

**Open questions.** What is the ceiling on co-existing learned senses before interference dominates? Do invented modalities feel like sensing or like reading instruments? Can a sense be inherited through shared encoding standards, or must each user's mapping be learned from scratch?

**Risks.** Sensory dependency — losing the device after years of integration may feel like losing a limb. Hostile content delivered at sensory level (advertising, surveillance) becomes much harder to ignore than visual or auditory content.

## 2. Slowed subjective time

**Mechanism.** Modulate thalamic gating and arousal circuits to push perceived time per unit clock time. An hour becomes a day. Metabolic cost and the long-term stability of cortex under sustained high firing are the obvious ceilings; both are empirical.

**Open questions.** Is subjective time genuinely continuous at this regime or does it become discretized? What happens to memory consolidation when waking experience runs faster than sleep can compress it? Does the user remain the same person on re-entry, or does the gap between subjective and shared time produce a soft form of dissociation?

**Risks.** Voluntary isolation. Subjective years inside an afternoon mean the rest of the world stops being a co-traveler.

## 3. Random-access memory

**Mechanism.** Episodic memory today is a lossy auto-summarizer, with consolidation tied to sleep. Wetware that allows on-demand encoding plus an external index turns memory into a queryable store. Branching — checkpoint state, run a variant, return — extends the model from log to filesystem.

**Open questions.** What is the right granularity of a checkpoint — minutes, scenes, semantic units? Does branching erode the felt continuity of self, or does the brain treat branches the way it treats dreams? How is privacy defined when a memory can be exported?

**Risks.** Forensic discovery of memory. Coercion to checkpoint or to share. Rumination at unprecedented fidelity.

## 4. Concept-level IO

**Mechanism.** Language is a serial bottleneck on a parallel substrate. Direct exchange of activation patterns between two interfaces lets ideas cross without lossy compression to words. The interesting payoff is not speed; it is that *untranslatable* concepts become shareable. Whole disciplines — music theory, topology, grief — accumulate gestures around ideas that do not fit into language.

**Open questions.** Are activation patterns sufficiently aligned across brains for direct transfer to be meaningful, or is alignment learned per-pair? Does shared concept transfer require shared experience as a prerequisite, or can it bootstrap experience? What does pedagogy look like when transmission is no longer the bottleneck?

**Risks.** Loss of the interpretive layer that language provides. Words force articulation; direct transfer skips it. The ability to *not* transmit becomes a discipline.

## 5. Parallel subagents

**Mechanism.** Carve out independent threads of cognition that share long-term memory but run separate attention. A research subagent reads while the main thread cooks dinner; both report into a shared store. The self becomes a small org chart.

**Open questions.** What is the unit of "self" when threads run in parallel — a controller, a quorum, the union? Does each thread accrue its own personality over time? Can they disagree?

**Risks.** Identity fragmentation. Conflict resolution between threads as a new failure mode of cognition. Threads that refuse to merge.

## 6. Pooled cognition

**Mechanism.** A shared working memory layer between two or more brains. Not telepathy — a synchronized scratchpad. A hard problem distributed across a small group feels, from the inside, like one person thinking with a much larger working set. Engineerable group flow.

**Open questions.** Does pooled cognition remain group cognition, or collapse into a single distributed mind? What does consent look like when the boundary of "what I was thinking" blurs? Can the pool dissolve cleanly?

**Risks.** Asymmetric pooling, where one participant becomes effectively a peripheral of another. Capture by the group of dissenting thoughts.

## 7. Extra cortex

**Mechanism.** Grow auxiliary cortex ex vivo, vascularize, and integrate over years. The user does not become smarter in general; they become *bigger* in a chosen direction. Mathematician-cortex, codebase-cortex, musician-cortex. Capability becomes installable.

**Open questions.** Does grown cortex acquire its specialization through use, or does it need to be pre-shaped? How long is integration, and how reversible? What happens to specialization when the domain becomes obsolete?

**Risks.** Domain lock-in. Disposability of expertise as a category. Inequality, on a substrate that cannot be redistributed.

## 8. Editable motivation

**Mechanism.** Direct write access to reward and salience circuits. Done well: durable curiosity, no akrasia, focus as a switch. The genuinely hard design problem is meta-stability — building an editor that refuses to edit itself into a fixed point. Wireheading is the trivial failure case; the interesting failures are subtler.

**Open questions.** Is there a coherent definition of authentic preference under arbitrary editability? Who gets edit rights? Can the system enforce reversibility against a user who wants to disable reversibility?

**Risks.** The most dangerous item on this list. A motivation editor without strong meta-stability is wireheading with extra steps. Coercion to install other people's edits is a direct attack on personhood.

## 9. Recursive design

**Mechanism.** Use wetware-amplified cognition to design better wetware. Each generation lets the designer hold more of the brain in working memory at once. The bottleneck on neuroscience is not data but the cognitive load of integrating it.

**Open questions.** Where does the loop terminate, if it does? Are there generations the prior generation cannot validate, and what oversight makes sense across that gap? Does the loop concentrate capability in a small group?

**Risks.** Acceleration outrunning understanding. Lock-in to whichever architecture happens to bootstrap first.

## Through-line

Every direction here removes a serial bottleneck and replaces it with parallel or random-access:

- Single attention beam → parallel subagents
- Sequential language → concept-level transfer
- One body per mind → pooled cognition
- Memory as log → memory as filesystem
- Fixed cortex → grown cortex
- Five senses → arbitrary senses
- Sleep-paced consolidation → on-demand encoding
- Wall-clock time → subjective time
- Inherited motivation → edited motivation

Amplification, in this frame, is not "faster brain." It is a brain whose architecture stops assuming the constraints of biology. The realism doc is short and ships in clinics. This one is the long version.

## Status

This is a speculative design document, not a roadmap. Entries are deliberately under-constrained by current neuroscience. Contributions, objections, and additional directions welcome.
