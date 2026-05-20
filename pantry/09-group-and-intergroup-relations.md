# Pantry — Chapter 9: group and intergroup relations

*Consolidated from multiple companion files written to non-canonical locations during the conversion run.*

## From 09-exercises-answer-guide.md

# Chapter 9 Exercises — Answer Guide

## Warm-up: Observe a Group Norm in Real Time

### What Good Looks Like

**Strong response:** Identifies three specific norms (not "people are kind" but "people remember each other's allergies and adjust food accordingly"). Explains the evidence (what you observed that told you it's a norm, not just someone's preference). Describes the consequence (teasing, exclusion, social distance, etc.). Names the function the norm serves (safety, identity, clarity, efficiency, etc.).

**Example of strong response:**

*Norm 1: Regular arrival time.* Evidence: All seven people in the 9 a.m. Thursday meeting arrived between 8:55 and 9:02. When Sarah arrived at 9:07 last week, the first thing Marcus said was, "You joining us late?" Consequence: Sarah seemed embarrassed; she said "sorry" unprompted. Function: Creates predictability and reduces anxiety about whether the meeting will actually start.

**Common mistakes:**
- Listing preferences as norms ("people like coffee") rather than enforced regularities.
- Assuming all norms are explicit ("the rule is we arrive by 9") rather than implicit ("we just... always arrive by 9").
- Confusing statistical regularity ("most people are quiet") with a norm ("people enforce quiet behavior").

---

## Application: Design a Superordinate Goal

### What Good Looks Like

**Strong response:** Diagnoses the conflict using social identity language ("they see each other as incompetent/dishonest/slow" rather than just "they don't cooperate"). Proposes a goal that satisfies all four conditions. Explains how the goal would work. Explicitly compares to why "get along better" fails.

**Example of strong response (Marketing vs. Product Engineering):**

*Diagnosis:* Marketing sees product engineers as arrogant and disconnected from customer reality. Engineers see marketing as overpromising and pushing features that add complexity without value. Both interpretations are filtered through group identity — each group sees its own failures as due to circumstance and the other group's failures as due to incompetence.

*Superordinate goal:* The company's largest competitor just launched a feature that three major customers have already requested. The request is technically feasible but requires resolving a fundamental architectural question. Marketing and product engineering jointly own the architecture decision. The decision must satisfy both technical integrity (no shortcuts that will debt) and customer timeline (decision by Friday, engineering confirmation by next Friday). Neither group succeeds alone; both must agree on a direction, and then both must execute.

*Why this works:*
1. Both groups genuinely want the outcome (market share loss is real).
2. They're interdependent (marketing can't design the architecture; engineering can't decide if customers will accept it).
3. There's real uncertainty (it's not obvious whether the technical approach works until they figure it out together).

*Why "get along better" fails:* Because the incentive structures haven't changed. Product engineering is still measured on technical excellence. Marketing is still measured on revenue. Those metrics can pull them apart even if they like each other personally.

**Common mistakes:**
- Proposing goals that only require one group's input ("marketing should understand engineering constraints").
- Proposing goals without real uncertainty ("reduce bugs" — engineering already does this; no interdependence).
- Ignoring incentive structure ("they should prioritize company goals over group goals" — this asks people to override identity, which Asch showed doesn't work).
- Assuming information/communication fixes the problem ("better cross-functional meetings") — this addresses awareness, not identity.

---

## Synthesis: Audit a Failed Group or Intergroup Initiative

### What Good Looks Like

**Strong response:** Identifies a specific failure. Diagnoses using concepts from the chapter (group structure, norms, cohesion, social identity, interdependence, coordination mechanism). Proposes a structural or norm-based change, not a motivational one. Explains why the proposed change addresses the actual mechanism.

**Example of strong response (Failed 2008 auto industry collaboration):**

*Case:* General Motors and Chrysler explored a joint venture for small-car manufacturing. The companies established a joint team, but it failed. Project was cancelled after eighteen months. Why?

*Analysis:*
- **Interdependence:** Reciprocal. GM and Chrysler had to jointly decide design, manufacturing process, supply chain. Neither could succeed alone.
- **Coordination mechanism in place:** Ad hoc meetings, shared email, nominal joint leadership.
- **What was missing:** The joint team was physically separate from both parent companies. Members reported to their home companies (GM engineers reported to GM leadership). When decisions favored GM interests over Chrysler, Chrysler representatives had to escalate to Chrysler leadership. When decisions favored Chrysler, GM did the same. The joint team couldn't overcome home-group identity.
- **The norm that killed it:** Loyalty to home company trumped commitment to joint venture. When conflict emerged, people defaulted to defending their group.

*What would have worked:*
- Physically co-locate the joint team. Make the joint team the primary reporting line, not a secondary duty.
- Give the joint team a superordinate goal with real consequences: "If this venture doesn't launch by date X at cost Y, both parent companies absorb the loss equally." Now both GM and Chrysler are jointly at risk, not separately defending their interests.
- Explicitly manage the norm. When someone advocates for their home company's interests over the joint venture, call it out. Establish a norm that internal debate is expected, but once decided, both companies execute as one.

**Common mistakes:**
- Focusing on individual leaders ("the right CEO could have made it work") rather than structural factors.
- Proposing "better communication" as the fix when the problem is conflicting incentives.
- Assuming commitment or shared values would override group identity.
- Missing the role of informal groups (the GM people probably had side conversations where loyalty to GM was reinforced).

---

## Challenge: Map an Organization's Intergroup Landscape

### What Good Looks Like

**Strong response:** Shows an understanding of the *actual* organization (not the org chart). Identifies informal groups in addition to formal ones. Correctly diagnoses interdependence types. Recognizes when coordination mechanism matches interdependence and when it doesn't. Identifies high-risk mismatches and proposes realistic fixes.

**Example of strong response (A software startup):**

*Groups:*
1. Backend engineers (7 people)
2. Frontend engineers (5 people)
3. Product management (2 people)
4. Sales (3 people)
5. Informal group: "early employees" (subset of backend, one product manager, one sales person) who socialize together

*Interdependence map:*
- Backend ↔ Frontend: Reciprocal (APIs, specifications, blockers)
- Backend + Frontend ↔ Product: Reciprocal (product decisions affect both; both needed for scope)
- Product + Engineering ↔ Sales: Sequential → Reciprocal (product/engineering deliver, sales sells it; but sales feeds back customer requests)
- Early employees ↔ Rest: Pooled (they're independent, but both contribute to company)

*Coordination mechanisms:*
- Backend ↔ Frontend: Daily standup, shared Slack channel, code review process. Mechanism: light, informal.
- Backend + Frontend ↔ Product: Weekly product review, but product has authority to decide. Mechanism: asymmetric (product decides; engineers execute).
- Product + Engineering ↔ Sales: Sales submits feature requests to product; product evaluates quarterly. Mechanism: rules-based (quarterly review cycle).
- Early employees ↔ Rest: Informal; early employees make decisions and announce to others. Mechanism: authority-based (early employees are informal leaders).

*Mismatches and risks:*
- Backend ↔ Frontend is reciprocal but coordination is light. Risk: When a decision requires both groups' input but neither feels ownership, delays happen. Proposal: Designate one person (rotating) as owner of each major feature. That person ensures both groups agree.
- Product ↔ Sales is sequential, but sales feels unheard (requests sit until quarterly review). Product feels bombarded (sales asks for everything). Proposal: Sales gets a voice in monthly prioritization, not just quarterly. Product gets clear filters (sales must submit top-3 requests, not top-20).
- Early employees' informal authority creates an in-group/out-group dynamic. The "rest" feel like they're on the outside. Risk: When new people arrive, they see that decisions happen in the informal early-employee group, not in official channels. Proposal: Deliberately rotate decision-making authority. Make explicit which decisions are made where.

**Common mistakes:**
- Assuming the org chart matches the actual organization.
- Treating all coordination as equally problematic ("we need more communication" across the board).
- Missing informal groups entirely.
- Not recognizing that some mismatches are okay (pooled interdependence doesn't need intensive coordination).
- Recommending "more meetings" rather than structural changes.

---

## Rubric Summary

| Concept | Weak | Strong |
|---------|------|--------|
| **Diagnoses using group dynamics** | "They're not committed" | "They see each other through a group identity lens that filters evidence" |
| **Identifies mechanisms** | Vague ("poor communication") | Specific (social loafing, conformity, outgroup homogeneity effect, role conflict) |
| **Proposes solutions** | Appeals to values or willpower | Changes structure, incentives, or norms |
| **Evidence for claims** | General | Specific observations or citations |
| **Addresses identity, not just coordination** | Assumes information solves group conflict | Recognizes that identity overrides logic; proposes structural change |


---

## From 09-extended-cases.md

# Chapter 9 — Extended Case Studies

## Case 1: The NASA Mission Failure — Group Norms Under Pressure

### The Event

In 2003, the Space Shuttle Columbia broke apart on re-entry, killing all seven astronauts on board. The investigation revealed that foam insulation had struck the shuttle's wing during launch, creating a small hole. Mission control knew about the impact within hours. Engineers at NASA's Marshall Space Flight Center became concerned. The question was urgent: would the hole be large enough to cause structural failure during re-entry?

### The Group Dynamics

What happened next is a case study in how group norms can suppress information and override expertise.

**The established norm:** Marshall Space Flight Center had a reputation for accepting risk. This was their norm — a positive norm in the launch business, where caution can be paralyzing. But norms are indiscriminate; they apply to *all* decisions, not just the ones they're supposed to apply to.

**The intergroup dynamic:** Mission control (in Houston) wanted the Columbia inspected in space using satellite imaging. The engineers at Marshall (in Huntsville) resisted. Why? The groups had separate identities and separate interests. Marshall's engineers had been involved in previous incidents where foam strikes occurred; the shuttle had been declared safe. If they now said "this foam strike is dangerous," it implied their previous assessments were wrong. Their group's credibility was at stake.

**The out-group homogeneity effect:** The engineers at Marshall began seeing mission control as "the cautious people" who didn't understand spaceflight reality. Mission control saw Marshall as "the old guard" defending their reputation at the expense of safety. Each group interpreted the other's position through the lens of group identity, not evidence.

**The conformity effect:** One engineer at Marshall had strong reservations about the safety conclusion. But when the group reached consensus that the shuttle was safe, the engineer's voice became less audible. The norm of deference to group judgment suppressed the dissent.

**The role:** The person assigned the role of "decision-maker" was a senior Marshall engineer with established authority. Other engineers deferred to this person's judgment, partly because of role structure and partly because challenging the senior person meant challenging the group's collective decision.

### The Mechanism

NASA's Columbia Accident Investigation Board concluded that the problem wasn't information. Mission control and Marshall both had access to the same data. The problem was organizational: the structure of how groups interact, the norms they enforce, and the incentive to preserve group reputation over individual truth-telling.

The investigation used the term "normalization of deviance" — the process by which a group accepts increasingly risky behavior as normal because the group has successfully managed similar risk in the past. Each time the group says "we were right; the risk was acceptable," the norm strengthens. The next time a similar risk appears, the group's default is acceptance, not skepticism.

### What Would Have Changed the Outcome

**Structural interventions:**
- Require the cautious group (Houston) to have veto authority on safety decisions, not advisory authority.
- Make Marshall and Houston jointly responsible for safety outcomes, not separate.
- Create a role of "outsider reviewer" — someone not from either group, with authority to stop the launch.

**Norm interventions:**
- Explicitly establish a norm that dissent on safety is expected and rewarded, not discouraged.
- When consensus is reached on safety, require a formal review by someone outside the group before implementation.
- Make it normative to air worst-case scenarios, not to smooth over them.

**Identity interventions:**
- Reframe the superordinate goal: "Our reputation is built on never launching a shuttle that fails. A launch decision we're uncertain about damages our reputation more than a delayed launch does."

**What wouldn't have worked:**
- Telling people to "be more careful." Norm is more powerful than intention.
- Appointing a nicer person to the decision-maker role. Role structure, not personality, was the problem.
- More communication between the groups. They were already communicating; they were filtering information through group identity.

---

## Case 2: The Pixar/Disney Integration — Bridging an Intergroup Boundary

### The Event

In 2006, Disney acquired Pixar for $7.4 billion. Two organizations with very different cultures, norms, incentive structures, and identities were suddenly one company. The question was not theoretical: How do you merge two groups?

### The Challenge

**Identity:** Pixar saw itself as a collection of artists and technologists who cared about craft and experimentation. Disney saw itself as an entertainment conglomerate focused on profitability and brand management. These identities were nearly orthogonal. Pixar people worried Disney would turn them into a feature factory. Disney people worried Pixar would be undisciplined and expensive.

**Interdependence:** The groups needed to be reciprocal — Pixar would handle creative production, Disney would handle distribution, merchandising, and business decisions. But who decided what? Conflict waiting to happen.

**Norms:** Pixar had a norm of long creative development (take the time to get it right). Disney had a norm of schedule discipline (deliver on date). These norms are fundamentally incompatible without structure.

**Status incongruence:** Pixar people had just been bought for billions, implying they were valuable and successful. Disney people controlled the corporation, implying they had authority and legitimacy. Who had higher status? Ambiguous. Status incongruence leads to tension.

### What Pixar Did Right

**Leadership bridge:** Ed Catmull and Alvy Ray Smith (Pixar's technical leaders) stayed. John Lasseter (Pixar's creative leader) stayed. Steve Jobs' trust in the Pixar team was explicit. Disney didn't try to replace Pixar leadership with Disney people. This preserved Pixar's identity.

**Structural separation:** Pixar remained physically separate. Pixar staff reported to Pixar leaders, not Disney leaders (initially). This prevented Pixar from being absorbed into Disney's organizational structure and norms.

**Superordinate goals:** The company framed the goal as "create the world's best animated films." This goal superseded both "maintain Pixar's creative independence" and "maximize Disney's profitability." Both Pixar and Disney could own this goal.

**Reciprocal interdependence recognized:** Disney didn't try to manage Pixar's creative process. Pixar didn't try to manage Disney's distribution. The groups were interdependent but not hierarchical. This reduced resentment.

**Norm negotiation:** Over time, Pixar and Disney negotiated new norms. Schedules became more disciplined, but with built-in flexibility for creative problems. Disney became more tolerant of experimentation. Neither group "won"; both changed.

### What Could Have Gone Wrong

**If Disney had installed a Disney executive to "manage" Pixar,** Pixar's identity would have been threatened immediately. Dissatisfaction and talent departure would have followed.

**If Disney had maintained strict schedule discipline without flexibility,** creative work would have suffered, and Pixar people would have felt their identity didn't matter.

**If Pixar had been allowed to ignore Disney's business constraints,** Disney people would have felt disrespected, and the merger would have created resentment.

**If the goal had been framed as "increase Disney's profitability,"** Pixar would have seen themselves as means to Disney's end, not as equal partners. Identity threat, lower commitment.

### The Mechanism

The Pixar/Disney merger worked because leadership explicitly managed the intergroup dynamics. They didn't assume that "joining forces" would be enough. They structured the integration so that:
1. Each group's identity was preserved (not erased).
2. A superordinate goal existed that both groups owned.
3. Interdependence was recognized (each group needed the other).
4. Norms were renegotiated rather than imposed.

---

## Case 3: The DevOps Revolution — Turning Sequential Into Reciprocal

### The Background

For decades, software development and IT operations were separate groups with separate goals and separate identities. Developers wanted to ship code frequently and make changes. Operations wanted stability and uptime. These goals created conflict.

**The interdependence:** Sequential. Developers created code. Operations deployed and ran it. Operations was dependent on developers (they created what operations had to run). Developers were less dependent on operations (they could hand off code and move to the next project).

**The norms:** Developers: "Move fast, break things, iterate." Operations: "Don't break things, stability is paramount, change is risk."

**The identity:** Developers saw themselves as innovative and forward-looking. Operations saw itself as responsible and conservative. When something went wrong, developers blamed operations for being too slow to deploy. Operations blamed developers for pushing untested code.

**The coordination mechanism:** Handoff. Developers would throw code over the wall to operations. Operations would deploy it (or refuse to, which created conflict).

### What DevOps Changed

DevOps restructured the relationship from sequential to reciprocal. Instead of "developers create; operations deploys," the model became "developers and operations jointly own the entire lifecycle."

**Structural change:** Combine development and operations into cross-functional teams. Someone who used to be pure-operations now worked alongside developers. Someone who used to be pure-development now participated in deployment and monitoring.

**Norm change:** Establish shared norms. "We ship code frequently" (developers' value). "We maintain stability" (operations' value). Both matter. The new norm: "We automate testing and monitoring so we can do both."

**Identity change:** The in-group is no longer "developers vs. operations." The in-group is "our team." People start identifying as "we care about reliable, rapid deployment" rather than as "developers" or "operations people."

**Superordinate goal:** The goal became "rapid delivery of reliable software." Neither group can achieve it alone. Rapid without reliable is reckless. Reliable without rapid is stagnant. The goal forces reciprocal interdependence.

**Incentive alignment:** Instead of measuring developers on speed and operations on uptime, measure the team on deployment frequency *and* system reliability. Now the incentives align.

### The Mechanism

DevOps worked because it didn't try to eliminate the groups or force cooperation. It restructured the groups themselves and the interdependence between them. It created a superordinate goal that both valued. It aligned incentives. It changed the in-group boundary from "my function" to "my team."

This is why DevOps is an organizational innovation, not just a technical one. It's about how groups relate to each other.

---

## Comparative Analysis

| Dimension | NASA Columbia | Pixar/Disney | DevOps |
|-----------|---------------|--------------|--------|
| **Initial conflict type** | Within-group norm suppressed dissent | Between-group identity threat | Between-group sequential interdependence |
| **Root cause** | Group norm (normalization of deviance) | Separate identities, status ambiguity | Misaligned incentives, sequential handoff |
| **Solution attempted** | Structural review, outside authority | Preserved identity, superordinate goal, structural separation | Merged groups, reciprocal interdependence, aligned incentives |
| **Success?** | Improved but incident still happened | Successful integration | Widely adopted, successful where implemented |
| **Key lesson** | Norms override information; structure is necessary to break them | Identity preservation + superordinate goal works; forcing one group into another fails | Reciprocal interdependence + aligned incentives reduces conflict better than sequential handoff |


---

## From 09-research-notes.md

# Chapter 9 Research Notes — Group and Intergroup Relations

## Sources Consulted

### Primary Research

1. **Sherif, M. (1954).** "Intergroup Conflict and Cooperation: The Robbers Cave Experiment." *University of Oklahoma Institute of Group Relations.* The landmark experimental demonstration that group boundaries generate bias automatically, and that superordinate goals (shared goals requiring cooperation) are the mechanism that reduces conflict. Replicated with variations multiple times; effect sizes robust.
   - Key finding: Boys separated randomly into groups developed hostile attitudes within days. Hostile attitudes persisted through direct contact. Only shared emergency goal (broken water line) reduced hostility reliably.

2. **Tajfel, H., & Turner, J. C. (1979).** "An Integrative Theory of Intergroup Conflict." *The Social Psychology of Intergroup Relations.* Social identity theory: part of self-concept comes from group membership. Minimal-group paradigm shows bias emerges without real conflict.
   - Key finding: In-group bias appears with random assignment, anonymous contribution, no prior group history.

3. **Asch, S. (1951).** "Effects of Group Pressure upon the Modification and Distortion of Judgments." *Journal of Abnormal and Social Psychology.* Conformity experiment: one-third of subjects deny sensory perception when confronted with unanimous group consensus.

4. **Latané, B., Williams, K., & Harkins, S. (1979).** "Many Hands Make Light the Work." Demonstrates social loafing: individuals exert less effort in groups, especially when output is unidentifiable and task importance is low.

5. **Hackman, R. J. (1987).** "The Design of Work Teams." Model of group effectiveness: design factors determine intermediate criteria (effort, knowledge, strategy), which determine ultimate effectiveness.

6. **Thompson, J. D. (1967).** "Organizations in Action." Classification of interdependence (pooled, sequential, reciprocal) and corresponding coordination requirements.

## Three Concepts Emphasized

1. **Group Structure (Size, Norms, Roles)** — How conformity pressure governs behavior; the trade-off between cohesion and groupthink.
2. **Social Identity and Intergroup Bias** — How group membership shapes self-concept and interpretation of ambiguous information.
3. **Managing Interdependence** — Matching coordination mechanism to interdependence type.

## Etymology

- **Norm** (Latin *norma*): a rule that a group enforces, not just a statistical regularity.
- **Cohesion** (Latin *cohaerere*): motivation to remain in the group, not just liking each other.
- **Superordinate** (Latin *super* + *ordinare*): a goal that supersedes usual group divisions.

## Fact Verification

- Sherif 1954: 22 boys, two groups, water supply failed day 10. Verified in original.
- Asch 1951: One-third conformity rate. Robust across replicates.
- Latané 1979: Social loafing increases with group size. Meta-analyzed; effect moderated by task type and culture.
- Tajfel minimal-group: In-group bias with random assignment. Replicated extensively.

## Contested Claims

1. **Whether superordinate goals are *necessary* or *sufficient*.** Sherif showed they work. Recent contact research suggests repeated positive contact may partially override bias. I've treated superordinate goals as the reliable mechanism.

2. **Universality of social loafing.** Effect is smaller in collectivist cultures, smaller when task is meaningful, may not emerge when group status is threatened.

3. **Long-term effects of Sherif's intervention.** Sherif's follow-up data on whether boys maintained friendships after camp are limited. I've emphasized short-term effect.

## Practical Tests for Managers

1. **Group-level vs. individual problem:** Is behavior consistent across group members (norm) or unique to one person (individual issue)?
2. **Identity-driven vs. structural conflict:** Would conflict disappear if organizational structure changed? Yes = structural; No = identity-driven.
3. **Coordination mismatch:** Do these groups have reciprocal interdependence but only standardized procedures for coordination?

---

