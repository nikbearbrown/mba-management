# Images and Figures: Chapter 3 — Perception and Job Attitudes

## Figure placeholders and descriptions

### Concept 1 figures

**Figure 1.1: The Perceptual Process (flow diagram)**

Three-stage flow:
1. External and internal stimuli → 2. Selectivity (attention filtering) → 3. Organization (categorization) → 4. Interpretation (meaning assignment) → 5. Behavior/Response

Annotations:
- External stimulus examples: loud noise, bright color, motion, repetition, size, contrast
- Internal stimulus examples: immediate needs (hunger, fatigue), past experience, disposition
- Organization: putting stimuli into categories (ambitious worker, detail-oriented, political)
- Interpretation: assigning meaning (this person is a builder vs. executor)

**Figure 1.2: Selectivity at work — the stopped machine scenario**

Split screen or two side-by-side images:
- Left: Manager's perception focused on stopped equipment (machinery illustration, dollar-sign clock)
- Right: Manager's perception focused on worker troubleshooting (person at work, lightbulb)

Caption: Same situation; different selective attention produces different perceptions and different decisions.

**Figure 1.3: Response salience example — the three workers in the same moment**

Illustration of a warehouse floor with three workers:
- Worker 1 thinking about clock (fatigue, response salience to quitting time)
- Worker 2 thinking about lunch (hunger, response salience to food/break)
- Worker 3 thinking about company financials visible on a posted notice (ambitious, response salience to advancement)

Caption: The same environment produces different perceptions because different needs are salient.

### Concept 2 figures

**Figure 2.1: The Three-Factor Attribution Model**

Table or structured framework:

| Factor | High | Low |
|--------|------|-----|
| **Consensus** | Others do this too (external cause) | Only this person does it (internal cause) |
| **Consistency** | Person does it repeatedly (internal) | One-off behavior (external) |
| **Distinctiveness** | Person does it across situations (internal: skill) | Person does it only in this situation (external) |

Example rows filled in:
- **Salesperson closes all deals, everywhere**: Low consensus, high consistency, low distinctiveness → **Internal cause (her skill)**
- **Everyone in the market sells well right now**: High consensus, high consistency, high distinctiveness → **External cause (market conditions)**

**Figure 2.2: Attribution errors — the two biases illustrated**

Two-panel illustration:

Panel 1 (Fundamental Attribution Error):
- Boss misses deadline
- You think: "Boss is disorganized"
- Actual: Boss was blocked waiting for info, managing three crises, deadline was unrealistic
- The gap: You underestimated the situation

Panel 2 (Self-Serving Bias):
- You close a deal
- You think: "I was the right person for this; I closed it"
- Someone else closes a deal
- You think: "Market conditions were good; they got lucky"
- The gap: You take credit for yours; you give circumstances credit for theirs

**Figure 2.3: Worked example — the software ship date**

Three columns representing three perspectives:

| Platform Team View | Your Team View | CFO View | Your Attribution |
|---|---|---|---|
| "The design was over-scoped" | "We delivered on schedule after platform delivered APIs" | "PM didn't buffer for risk" | "This was a sequential dependency issue no team could prevent" |

Bottom annotation: Each is partly true. Each uses different attribution model. Each leads to different lesson learned.

### Concept 3 figures

**Figure 3.1: Four job attitudes and what they predict**

2x2 matrix:

| Attitude | Definition | Predicts | Example |
|---|---|---|---|
| **Satisfaction** | Emotional response to job experience | Turnover (moderate), absenteeism | "I like working here day-to-day" |
| **Involvement** | Care about doing the job well | Quality, conscientiousness | "I care about this work being done right" |
| **Commitment** | Identification with org goals and mission | Retention, discretionary effort | "I want to help this organization succeed" |
| **Engagement** | Mental and emotional absorption in work | Effort, initiative, learning | "I'm focused and energized by this work" |

Emphasis: Satisfaction and commitment are not the same. Organizations measure satisfaction and miss commitment.

**Figure 3.2: The satisfaction-performance relationship**

Scatter plot (conceptual):
- X-axis: Job Satisfaction (low to high)
- Y-axis: Performance (low to high)
- Points scattered in a cloud with a weak upward trend
- Annotation: "r ≈ 0.30 — satisfaction explains about 9% of performance variation"
- Note: "Good performance CAN lead to satisfaction (people happy when winning), but satisfaction does NOT reliably lead to performance"

**Figure 3.3: What predicts retention**

Horizontal bar chart comparing predictors:

- Satisfaction: moderate relationship with retention
- Commitment: strong relationship with retention
- Engagement: strong relationship with retention
- Visible growth path: strongest relationship with retention

Caption: "Organizations often measure satisfaction (the weakest predictor) and miss what actually predicts whether people stay."

**Figure 3.4: Three-component organizational commitment**

Three overlapping circles or Venn diagram:

- **Affective commitment** (top): "I like being here" — emotional attachment
- **Continuance commitment** (left): "I'd lose too much by leaving" — calculation/cost
- **Normative commitment** (right): "I should stay" — obligation

Color coding:
- Affective only: green (predicts strong retention + high performance)
- Continuance only: yellow/orange (predicts staying but going through motions)
- Normative only: blue (predicts ambivalence, watchful for exits)

**Figure 3.5: The Southwest Airlines case**

Infographic or timeline:

- 43 years of profit sharing with employees
- 2017: $586M in profits shared with 54K employees (avg 13.2% bonus) + $351M to 401(k)s
- CEO quote: "Our people-first approach means our company does well, our people do really, really well"
- Outcome: High satisfaction AND high retention (both rare)
- The mechanism: Visible investment (profit sharing), clear values (people-first), visible paths (flight attendants become managers)

**Figure 3.6: The self-fulfilling prophecy loop**

Circular flow diagram:

1. Manager forms early perception (maybe accurate, maybe biased)
2. ↓
3. Perception shapes treatment (assignments, feedback, opportunities)
4. ↓
5. Treatment shapes opportunities (what assignments, what learning, what visibility)
6. ↓
7. Opportunities shape outcomes (what you can become, what you achieve)
8. ↓
9. Outcomes confirm initial perception
10. ↓ (loop back to 1)

Annotations on the loop showing examples:
- "Sarah filed as detail-oriented" → "Gets tactical assignments" → "Visibility limited to execution" → "Doesn't get strategic opportunities" → "Can't prove strategic thinking" → "Stays detail-oriented in manager's mind"

Escape hatch annotation: "To break loop: change treatment (give bigger assignment), or change social signal (explicit belief in growth)"

## Implementation notes for design

### Figure priority

Essential (high information value):
- Figure 3.1 (four attitudes table) — This is new clarity vs. source material
- Figure 2.1 (three-factor model table) — Canonical framework
- Figure 3.6 (self-fulfilling prophecy loop) — Core mechanism of the chapter

Valuable (clarify examples):
- Figure 1.1 (perceptual process flow)
- Figure 2.2 (attribution errors)
- Figure 3.3 (what predicts retention)

Enhancement (illustration):
- Figure 1.2 (stopped machine scenario)
- Figure 1.3 (response salience examples)
- Figure 3.5 (Southwest case infographic)

### Design direction

- **Color coding**: Use colors consistently across figures. Green for positive outcomes (high commitment, engagement). Red/orange for biases or barriers. Blue for neutral mechanisms.
- **Typography**: Use sans-serif for clarity. Keep labels short and active ("Perception shapes treatment" not "The manner in which perception influences treatment").
- **Accessibility**: Include text descriptions for all figures, not just labels. Avoid pure red-green distinctions for color-blind readers.
- **Style**: Favor data tables and flow diagrams over decorative illustrations. Keep illustrations (1.2, 1.3, 3.5) grounded and specific.

### Figure-to-text alignment

- Figure 1.1 appears after "The perceptual process at work" and before concept breakdown
- Figure 1.2 appears after "same stimulus, different perception" example in Concept 1 opening
- Figure 2.1 appears when introducing the three factors; referenced multiple times through Concept 2
- Figure 2.2 appears when introducing the two biases
- Figure 3.1 appears when introducing the four attitudes
- Figure 3.6 appears in Synthesis section as the capstone diagram

### Figure references in text

All figures are referenced in the chapter text, not as decoration:

Examples:
- "As shown in Figure 1.1, the perceptual process has three stages..."
- "The three-factor model, diagrammed in Figure 2.1, suggests..."
- "Table 3.1 contrasts the four attitudes and what they predict..."

## Notes on what's missing vs. source material

The source material included many figures that were content-delivery rather than concept-clarifying:

Removed or simplified:
- **"Learning Outcomes" image** — This is text-based in the chapter structure; doesn't need an image
- **"Major Influences on Selective Attention" figure from source** — Valuable but complex; consolidated into Figure 1.1
- **"Social Perception Influences" figure from source** — This diagram of three circles (person, situation, perceiver) is conceptually important but the text explains it clearly; an image would duplicate
- **"Perceptual barriers table" from source** — Included in text; added worked examples instead of image
- **"Golf tournament" illustration** — Source had this for the distinctiveness example; text explanation is clearer and less is-this-about-golf confusing

Added:
- **Figure 3.6 (self-fulfilling prophecy loop)** — This is the integrating mechanism of the whole chapter; source material didn't have a visual for it
- **Figure 3.5 (Southwest case)** — Source had the Southwest example but it was a text case. An infographic grounds the numbers and makes the path-forward insight visual

## Storage location

All figures should be stored in `/Users/bear/Documents/CoWork/bear-textbooks/books/principles-of-management-bundle/images/` with naming convention:

- `ch03-fig-1-1-perceptual-process.png` (or .svg for diagrams)
- `ch03-fig-2-1-three-factors.png`
- etc.

This file tracks the descriptions; the actual image files will be created/sourced separately by the design team.
