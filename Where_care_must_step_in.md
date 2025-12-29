Human-Centered Design and Accessibility: Where Care Must Step In
By Alexander A Kouliy
We position CCD not as opposing HCD, but as its next evolutionary phase—adding emotional regulation, user sovereignty, system-level care.

Human-Centered Design (HCD) Shortfalls
Empathy limited to discovery phase → not iterative.
Ignores trauma, fluctuating capacity, and nervous-system load.
CCD adds care-retention loop via URSA re-checks.

Where Human-Centered Design (HCD) Falls Short for Disabled/Neurodiverse Users

1. Centering the “Average” User / Normative Bias
Issue: HCD often builds from “typical” users, underestimating variance in sensory, cognitive, motor experience. Accessibility gets treated as an addendum, not baked in.
Evidence: Van Velsen et al. survey nine limitations of HCD in eHealth, including “the tendency to focus on existing users rather than marginalized populations”. PMC
Implication: The design may work well for “average” tasks but break under edge cases: sensory overload, fine motor strain, processing delays.
CCD fix: Start from sensory extremes as design constraints (not exceptions). Always test with neurodivergent / disabled participants early.
2. Assumption That Needs Are Pre-Given / Static
Issue: HCD tends to treat user needs as fixed and knowable in advance, but many disabled / neurodiverse experiences are dynamic (fatigue, pain, flares) and context-dependent.
Evidence: Norman’s “Human-Centered Design Considered Harmful” argues that assuming stable needs can ignore evolving contexts. ResearchGate
Implication: A design that “meets the need” today may become hostile the next day (e.g. motion that was fine now feels overwhelming).
CCD fix: Design for adaptivity and sensory consent toggles (e.g., switching “Healing Mode” on/off mid-session).
3. Insufficient Voice / Participation from Disabled Users
Issue: HCD often involves users superficially (e.g. interviews, testing) without deep co-design or ownership. The result: designers misinterpret or oversimplify lived experience.
Evidence: Ortiz-Escobar et al. studied assistive tech claiming “user-centred design” but found many dropped ISO 9241-210 principles in practice—users’ inputs not fully integrated. PMC
Implication: You get a surface veneer of accessibility but leave behind subtler harm — e.g. interaction friction, emotional stress triggers, lack of flexibility.
CCD fix: Make disabled-led design the core—not auxiliary. Let users set thresholds for motion, contrast, pacing.
4. Overemphasis on Functionality / Usability vs. Emotional Safety
Issue: HCD typically optimizes task completion, efficiency, error rates—but downplays how the user feels during and after use. For many, emotional dysregulation is as critical as task failure.
Evidence: The “Limitations of HCD” paper in eHealth notes neglect of “emotional burden or cognitive burden” in design evaluation. PMC
Implication: A form may be “usable” but emotionally exhausting or dysregulating—users avoid it despite correctness.
CCD fix: Introduce metrics like felt-safety, fatigue, overwhelm, alongside time-on-task and error rates.
5. Failure to Account for Variability / Fluctuation
Issue: People with chronic illness, neurodiversity, or sensory sensitivities often have days/hours where performance drops. HCD tends to assume a steady state.
Evidence: Barriers to access literature (Clemente et al.) shows fluctuating access—physical/health conditions vary over time. PMC
Implication: A design that works on “good days” collapses on “bad days.”
CCD fix: Allow mode switching, reducing density, stashing state, rest/resume patterns.
6. Ignoring Systemic / Structural Constraints
Issue: HCD focuses on interface and service, but often fails to account for institutional, policy, or infrastructural constraints that disable users (e.g. procurement rules, policies, architecture).
Evidence: In social computing research, the neurodiversity lens shows that many “solutions” assume neurotypical norms and restrict alternative expression. arXiv
Implication: You design a “better UI,” but the system still forces harmful outcomes (e.g. forced synchronous escalation, opaque policies).
CCD fix: Push care upward—policy, procurement, auditing. Integrate CCD at macro/meso levels, not just micro UI.
7. Lack of Transparency & Legibility in Design Decisions
Issue: HCD often hides trade-offs (e.g. “We dropped motion to speed load”) and doesn’t explain implications to users. For disabled users, that opacity is harmful—no way to contest or adapt.
Evidence: HCD in workplaces faces “Competing Visions” and “Sidestepping Responsibility,” making trade-offs opaque in practice. arXiv
Implication: Users can’t understand why design behaves a certain way, can’t trust the system, can't request overrides.
CCD fix: Always expose why (e.g. “Motion reduced due to sensory safety”) + provide override consent.

WCAG Shortfalls
Binary contrast ratios ignore physiological distress.
No metric for predictability or emotional safety.
CCD introduces Nervous-System-Safe Mode, Care Audits, and Regulation Scales.

Where WCAG Falls Short — and How Care-Centered Design Expands It

1. Focus on Visual / Auditory Clarity, Not Sensory Regulation
Issue: WCAG defines accessibility as perceivable, operable, understandable, robust — but never regulated. Meeting a 4.5 : 1 contrast ratio can still trigger anxiety or sensory pain.
Evidence: Harvard IT Accessibility warns that “high-contrast combinations can create glare or flicker effects for some users” (Harvard University IT, 2022).
The W3C COGA Task Force (2023) notes that predictability and emotional safety remain unmet needs.
CCD Fix: Add a “Nervous-System-Safe Mode” criterion — user-selectable contrast, animation, and tone profiles; treat calm as a success metric.
2. Binary Pass/Fail Ratios Ignore Context and Emotion
Issue: WCAG’s numeric thresholds treat perception as static. They don’t account for context, cumulative strain, or cross-sensory load.
Evidence: Lavie (2005) and Sweller (2011) show that cognitive overload, even with readable text, reduces comprehension.
CCD Fix: Replace binary compliance with graded regulation scales — measure HRV variance, self-reported calm, and time-on-task stability.
3. Neglect of Cognitive & Emotional Disabilities
Issue: WCAG 2.1 added few cognitive provisions; 2.2 still treats them as advisory. COGA Usable 2023 remains non-normative.
Evidence: COGA § 3.4 explicitly calls out that “many users will not be able to complete tasks without additional support”.
CCD Fix: Make COGA binding — integrate trauma-informed UX (SAMHSA 2014; Hopper et al. 2010) into every success criterion. Require choice, predictability, transparency.
4. Inflexible Motion & Timing Rules
Issue: SC 2.2.1 (“Timing Adjustable”) and 2.3.3 (“Animation from Interactions”) only mitigate seizures, not vestibular stress or ADHD hyperarousal.
Evidence: MDN Docs confirm that motion such as parallax or large-scale transforms can trigger dizziness and migraines even below seizure thresholds (MDN 2025).
CCD Fix: Add Somatic Motion Controls — <0.7 s default, global “reduced motion” toggle, and an “emergency still” mode.
5. No Recognition of Fluctuating Capacity
Issue: WCAG assumes stable user performance. Chronic illness, fatigue, or fluctuating executive function are not addressed.
Evidence: Clemente et al. (2022) document variable accessibility over time for disabled users seeking services.
CCD Fix: Introduce Temporal Adaptivity Criteria — session memory, auto-save, and resumable workflows; measure recovery time, not just completion.
6. Accessibility Stops at Interface, Not Policy
Issue: WCAG governs markup and content, not systemic empathy — support channels, escalation, or human response.
Evidence: The Accessible Canada Act (2019) calls for “barrier-free services,” yet portals like NSLSC still trap users in inaccessible loops.
CCD Fix: Require Care Audits alongside security audits: review not only code but workflow, tone, and emotional impact.
7. Opaque Updates and Unstable States
Issue: WCAG has no rule for emotional continuity during updates. Sudden visual or structural changes disorient neurodivergent users.
Evidence: Palani et al. (2024) found autistic participants significantly more distressed by unannounced UI changes than neurotypicals.
CCD Fix: Add Change Transparency Criterion — version notes, “classic view,” opt-in rollouts, visual transition cues.
8. No Framework for Emotional Harm or Repair
Issue: WCAG defines errors as technical, not affective; there’s no language for apology, reassurance, or repair after harm.
Evidence: Hopper et al. (2010) emphasize safety and trust as universal design imperatives; absent in WCAG’s feedback criteria.
CCD Fix: Require Empathic Error States — messages that reassure (“Let’s fix that together”), offer options, and explain context.

Summary Table
WCAG Gap	CCD Extension	Physiological / Psychological Rationale
Contrast only measures visibility	Nervous-System-Safe Mode	Prevents sympathetic activation (HR↑ 10–20%)
Binary thresholds	Regulation Scale / FRI	Captures gradations in stress & calm
Non-normative cognitive guidance	Trauma-Informed UX	Ensures safety + predictability
Motion only covers seizures	Somatic Motion Controls	Reduces vestibular / autonomic dysregulation
No fluctuating-capacity model	Temporal Adaptivity	Supports pacing and rest-resume
Interface-only scope	Care Audits	Embeds empathy in operations
No update transparency	Change Disclosure	Preserves trust, prevents disorientation
No emotional-repair language	Empathic Error Design	Restores safety, maintains engagement

Works Cited (MLA 9)
Barrett, Lisa Feldman. How Emotions Are Made: The Secret Life of the Brain. Houghton Mifflin Harcourt, 2017.
Clemente, Maria et al. “Accessibility Barriers and Fluctuating Health Conditions.” Disability and Health Journal, 2022.
Hopper, Elizabeth, Ellen Bassuk, and Jeffrey Olivet. “Shelter from the Storm: Trauma-Informed Care in Homeless Services Settings.” Open Health Services and Policy Journal, vol. 3, 2010.
Harvard University Information Technology. Use Sufficient Color Contrast. Harvard University, 2022, https://accessibility.huit.harvard.edu/.
Lavie, Nilli. “Selective Attention under Load.” Trends in Cognitive Sciences, vol. 9, no. 2, 2005.
Palani, R., et al. “Interface Design for Autism in an Ever-Updating World.” University of Kent, 2024.
Porges, Stephen W. The Polyvagal Theory. Norton, 2011.
SAMHSA. Concept of Trauma and Guidance for a Trauma-Informed Approach. U.S. HHS, 2014.
Sweller, John. “Cognitive Load Theory.” Psychology of Learning and Motivation, vol. 55, 2011.
W3C. Web Content Accessibility Guidelines (WCAG) 2.2. World Wide Web Consortium, 2024.
W3C COGA Task Force. Making Content Usable for People with Cognitive and Learning Disabilities. World Wide Web Consortium, 2023.

---
**Care-Centered Design (CCD)**  
A nervous-system-first design framework created by **Alex Kouliy**, developed at Nulltech Designs.  
CCD integrates accessibility, trauma-informed UX, and emotional design into a unified ethical practice.
