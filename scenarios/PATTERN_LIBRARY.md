---
id: CIVCOHE-PATTERN-LIBRARY
type: reusable-pattern-registry
status: governed-working-library
---

# Reusable Sociotechnical Pattern Library

The library should grow by **composing reusable patterns**, not by inventing new domain-specific systems repeatedly.

## P01 — Discover Relevant Capability
Useful competence exists but is not visible at the moment of need.

\[DistributedCapability \rightarrow DiscoverableCapability\]

Possible implementation example: EkoH-like contextual capability discovery.

## P02 — Qualify Contextual Credibility
Interpret competence relative to domain, task, context, evidence and time.

\[Competence \neq UniversalRank\]

## P03 — Route Information to the Relevant Actor

\[AvailableInformation \rightarrow RelevantInformation \rightarrow RelevantActor\]

Possible implementation example: Orgo routing.

## P04 — Route Work to Capable Actors

\[Need \rightarrow Task \rightarrow Owner \rightarrow Execution\]

Possible implementation example: Orgo.

## P05 — Preserve Provenance

\[Claim \rightarrow Source \rightarrow TransformationHistory \rightarrow ReusableArtifact\]

Possible implementation example: Kristal.

## P06 — Keep Knowledge Artifacts Separable
Prevent domains, records, interpretations or authorities from silently collapsing together.

## P07 — Realize Structured Meaning in Multiple Languages

\[StructuredMeaning \rightarrow LanguageSpecificRealization\]

Possible implementation example: SemantiK / SenTient / SemantiK Architect stack.

## P08 — Maintain AI-Independent Core Operation

\[AI	ext{-}assisted \neq AI	ext{-}required\]

## P09 — Add Optional AI Over Structured Substance
Prefer structured, sourced input to forcing an AI to reconstruct meaning from document chaos.

## P10 — Validate Contribution Through Relevant Expertise

\[Artifact \rightarrow RelevantReview \rightarrow Attestation \rightarrow BroaderReview\]

\[PriorStatus \neq ContributionQuality\]

## P11 — Preserve Attribution Through Aggregation
A small contribution should remain traceable when absorbed into a larger corpus.

## P12 — Provide Multiple Readings of Collective Signals

\[RawSignal \neq Reading\]

Possible implementation example: Smart Vote lenses.

## P13 — Deliberate Across Expertise, Stakes and Values
Use structured deliberation while preserving:

\[Expertise \neq Sovereignty\]

Possible implementation example: ethiKos.

## P14 — Support Remote Participation

\[PhysicalAbsence \not\Rightarrow ParticipationLoss\]

## P15 — Convert Expertise Into Formal Learning Artifacts

\[ExpertKnowledge \rightarrow Media \rightarrow Course \rightarrow Practice \rightarrow Evidence \rightarrow ReusableMasteryPath\]

Possible implementation example: UCKK model and media library.

## P16 — Fork and Recombine Knowledge Without Erasing Context

\[SourceArtifact \rightarrow Fork \rightarrow DerivedArtifact\]

\[Fork \neq Endorsement\]

## P17 — Distinguish Representation From Truth Status

\[ExistenceOfClaim \neq ValidityOfClaim \neq Endorsement\]

## P18 — Maintain Local Operation With Optional Federation

\[LocalCore \subset LocalCore+Federation\]

## P19 — Protect Legitimate Authority While Improving Advice

\[ExpertAdvice \neq DecisionAuthority\]

## P20 — Turn Outcomes Into Reusable Learning

\[Action \rightarrow Outcome \rightarrow Review \rightarrow Memory \rightarrow FutureCapability\]

# Pattern design rule

Before adding a new pattern, ask whether it is genuinely new or just a domain-specific version of an existing mechanism.

Prefer:

\[FewStrongPatterns \rightarrow ManyCompositions\]

rather than duplicated mechanisms.

---

## P21 — Articulate Many Capabilities Through One Hub

**Problem:** users reconstruct context across search, social, knowledge, governance and work tools.

\[
FragmentedCapabilities \rightarrow ArticulationHub \rightarrow CoherentJourney
\]

**Possible implementation example:** Konnaxion/Koali as a common hub.

**Risks:** attention monopoly, terminal dependency, hidden defaults, monolithic coupling.

---

## P22 — Integrate External Capability by Mimic or Annex

**Problem:** adding mature external functionality either duplicates effort or creates a new silo.

\[
ExternalCapability \rightarrow MimicOrAnnex \rightarrow SharedContracts
\]

**Possible implementation example:** Kintsugi + Kompendio.

**Risks:** dual truth, license incompatibility, hidden dependency, adapter drift.


---

## P23 — Preserve Contestable Worldviews

**Problem:** a shared knowledge infrastructure becomes a de facto central authority if alternative worldviews cannot be represented, forked or compared.

\[
ReferenceCorpus + ForkableWorldviews
\]

while preserving:

\[
FreedomToRepresent \neq EqualEvidence
\]

**Possible implementation example:** Kristal branch lineage with explicit axioms, provenance and validation state.

**Risks:** relativism, branch confusion, hidden canonical coercion, propaganda forks presented as reference truth.

---

## P24 — Distinguish Apparent Support From Causal Independence

**Problem:** many citations, experts or publications can create an illusion of independent confirmation while tracing back to the same source, operator or unsupported claim.

\[
CitationCount \neq IndependentEvidenceCount
\]

A system should preserve enough provenance to estimate or inspect causal independence.

**Risks:** Sybil-like epistemic amplification, citation laundering, circular validation, prestige cascades.

---

## P25 — Rehearse Legitimate Opposition Before Crisis

**Problem:** formal rights of contestation may be unusable if people have never practiced how to exercise them against a powerful internal authority.

\[
FormalRight
\rightarrow
Practice
\rightarrow
ReusableCounterpower
\]

**Possible implementation example:** civic resilience drills such as `SCN-GOV-001`.

**Risks:** exercise becomes polarization, simulated abuse causes real harm, opposition becomes identity conflict rather than proposition-level contestation.
