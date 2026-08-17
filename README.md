<div align="center">

<br/>

```
  ◈ DIAGNOSE → DECIDE → LEAD ◈
```

# Design Org Decisions
### A Claude Code Skill

**Org design, people management, and executive decision-making for design leaders.**
Built for VP of Design, Head of Design, CPO, CTO, and Design Directors navigating the hard calls that don't have easy answers.

<br/>

[![Version](https://img.shields.io/badge/version-1.0.0-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/design-leadership-skill)
[![Domains](https://img.shields.io/badge/domains-9-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/design-leadership-skill/blob/main/SKILL.md)
[![Frameworks](https://img.shields.io/badge/frameworks-10+-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/design-leadership-skill/blob/main/SKILL.md)
[![Claude Code](https://img.shields.io/badge/Claude_Code-skill-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://claude.ai/claude-code)

<br/>

</div>

---

## Install

**Add to an existing Claude Code project:**

```bash
git clone https://github.com/65ping/design-leadership-skill.git .claude/skills/design-leadership
```

**Or install globally** (available across all your projects):

```bash
git clone https://github.com/65ping/design-leadership-skill.git ~/.claude/skills/design-leadership
```

Claude Code will detect the skill automatically. No configuration needed.

---

## What It Does

This skill turns Claude into a senior advisor for design org leadership. Bring it a real decision - org structure, hiring, a difficult conversation, a political problem, a VP transition - and get framework-grounded, opinionated guidance that connects design to business outcomes.

```
"Should I centralize or embed my designers now that we're scaling to 40 people?"
"I have a senior designer who's underperforming. How do I handle this without losing them?"
"Engineering keeps making design decisions without us. How do I fix this structurally?"
"I just got promoted to VP. What do I stop doing immediately?"
"How do I build a critique culture that doesn't feel like a roast?"
```

Claude responds with a diagnosis of your org stage, the relevant framework, a clear recommendation with trade-offs named, and the specific anti-patterns to avoid.

---

## The Nine Decision Domains

| # | Domain | What It Covers |
|---|---|---|
| 1 | **Org Structure** | Centralized vs. embedded vs. federated models, maturity stages, span of control |
| 2 | **Hiring** | What great looks like at each level, future org chart, IC vs. manager tracks |
| 3 | **Managing Up** | Earning exec credibility, language that works, when and how to push back |
| 4 | **Cross-Functional Relationships** | Design-product-engineering triangle, design systems as org strategy |
| 5 | **Vision and Strategy** | Setting direction, OKRs for design, communicating vision at scale |
| 6 | **Performance Management** | Feedback stack, coaching vs. managing, handling underperformers |
| 7 | **Culture** | Psychological safety, critique rituals, remote and distributed teams |
| 8 | **Scaling** | When to add headcount, internal vs. external hires, delegation as you grow |
| 9 | **Self-Management** | Director to VP transition, imposter syndrome, energy management |

---

## Core Frameworks

| Framework | What It Does |
|-----------|-------------|
| **Centralized / Embedded / Federated** | Three org models with when-to-use criteria and failure modes |
| **5 Design Org Maturity Stages** | Diagnose where you are and what the next stage actually requires |
| **12 Qualities of Effective Design Orgs** | Foundation, output, and management dimensions |
| **Three-Legged Stool** | Business + technology + design as peer capabilities at the exec table |
| **Double Diamond as Executive Tool** | How to push design upstream into strategy, not just execution |
| **Future Org Chart Exercise** | Hire for 18 months ahead, not for today's pain points |
| **Feedback Stack** | Three layers of performance feedback, all required |
| **Span of Control Guidelines** | 5-8 ICs, 3-5 managers, and why each number matters |
| **IC vs. Manager Track** | When to build a parallel path instead of forcing promotion |
| **Quick Decision Reference** | 13 common leadership questions mapped to the right framework |

---

## Example Prompts

This is the most important section. These show what the skill actually does when you use it.

---

**Org structure decision:**
> "We're growing from 12 to 40 designers over the next year. I currently have everyone reporting centrally. Should I keep it that way or shift to embedded pods?"

Claude identifies your current maturity stage, explains why a centralized structure works at 12 and breaks at 40, walks you through the Centralized / Embedded / Federated tradeoffs, recommends the federated model with a specific transition plan (what changes first, what stays central), and names the failure modes to watch for during the transition.

---

**Performance problem:**
> "I have a senior designer - strong craft, great instincts - but she's been missing deadlines for three months and getting defensive in critiques. I've hinted at it twice but nothing's changed. What do I do?"

Claude diagnoses why hints don't work (vague feedback is a form of avoidance), gives you the exact structure for the direct conversation (name the behavior, name the impact, set a concrete bar for 60 days), helps you decide whether this is a skills gap or a fit/values gap, and tells you what documentation to create now - not for HR, but for your own clarity.

---

**Complex org design challenge:**
> "I'm a new VP of Design at a Series C company. I've inherited a team of 18 designers: 14 embedded in product squads reporting to PMs, 4 in a central platform team reporting to me. Design quality is inconsistent across squads. No design system. Product is skeptical of centralizing anything. Engineering thinks design slows them down. I have 6 months before my first big review. What's my plan?"

Claude runs a full diagnosis across all nine domains. It identifies your maturity stage (Stage 2 transitioning to 3), maps the political landscape (product skepticism, eng friction, no shared infrastructure), gives you a sequenced 6-month plan (what to do in the first 30 days vs. 90 vs. 180), tells you the one structural move that will have the most leverage (a federated model with a design system as the forcing function), and flags the trap most new VPs fall into (trying to fix everything at once and losing credibility on all fronts).

---

**Managing up:**
> "My CEO keeps asking for 'faster' and 'simpler' but our product has real complexity. I can't just remove features. How do I have this conversation without sounding defensive?"

Claude reframes the conversation from design quality vs. speed to business risk vs. investment, gives you the exact language to use ("If we simplify this flow without the research, we risk building the wrong thing at 10x the cost"), explains how to translate design concerns into the vocabulary your CEO actually responds to (revenue, retention, competitive differentiation), and tells you when to fight for quality and when to commit to the call and move on.

---

**Critique culture:**
> "Our design critiques are either too soft (everyone says 'looks great') or too harsh (people leave feeling attacked). How do I fix this?"

Claude gives you the four critique principles (describe before you prescribe, ask don't tell, be specific, the presenter retains authority), a concrete structure for running the session, what to say when someone gets defensive, and the single most important thing the most senior person in the room needs to model for the culture to shift.

---

**VP transition:**
> "I was just promoted from Director to VP. My instinct is to stay close to the work and keep shipping. Is that wrong?"

Claude explains exactly why the skills that made you a great Director will actively make you a bad VP, what you need to stop doing immediately (being in every design meeting, solving your reports' problems for them, making decisions that should live one level below you), what the VP job actually is (building the organizational system, not the screens), and the three practices that separate good VPs from great ones.

---

## Who It's For

### VP of Design and Head of Design
Making the real org calls: structure, hiring, managing up, culture at scale. Getting a seat at the strategy table and keeping it.

- Org structure decisions grounded in maturity stage, not best practice lists
- Stakeholder language that translates design quality into business outcomes
- People management frameworks for the hardest conversations

### CPO and CTO
Designing the design-product-engineering partnership. Understanding what a healthy design org requires from adjacent functions.

- The Three-Legged Stool model for peer-level collaboration
- Design system strategy as org infrastructure, not just a component library
- Cross-functional ownership clarity when design and product disagree

### Design Directors
Preparing for the VP transition. Managing managers for the first time. Building culture across multiple teams.

- The Director-to-VP shift: what changes, what to stop doing
- Managing managers vs. managing ICs: what's different
- Delegation and trust as the team grows

### Senior Design Managers
Building critique culture. Growing as a leader. Handling underperformers and career conversations.

- Feedback stack: three layers of performance feedback, all required
- 1:1 structure that actually develops people
- Coaching vs. managing, and when to use each

---

## What's Inside

```
design-leadership/
│
├── SKILL.md                 <- Main skill file (auto-loaded by Claude Code)
│   ├── Domain 1             <- Org Structure: archetypes, maturity stages, span of control
│   ├── Domain 2             <- Hiring: what great looks like, future org chart, IC vs. manager
│   ├── Domain 3             <- Managing Up: credibility, language, when to push back
│   ├── Domain 4             <- Cross-Functional: product-eng-design triangle, design systems
│   ├── Domain 5             <- Vision & Strategy: setting direction, OKRs, communication
│   ├── Domain 6             <- Performance: feedback stack, coaching, underperformers, 1:1s
│   ├── Domain 7             <- Culture: psychological safety, critique, rituals, remote teams
│   ├── Domain 8             <- Scaling: headcount signals, internal vs. external, delegation
│   ├── Domain 9             <- Self-Management: VP transition, imposter syndrome, energy
│   └── Quick Decision Table <- 13 common questions mapped to the right framework
│
├── icon.svg                 <- Skill icon
└── README.md                <- This file
```

---

## Keywords

design leadership, VP of design, head of design, design org, org design, design management, design culture, design team structure, centralized vs embedded design, design maturity, managing up, design strategy, design vision, performance management for designers, design critique, design OKRs, design career ladder, federated design org, design systems strategy, design executive, CPO, design director, growing a design team, IC vs manager track, design org scaling, design leadership frameworks, Claude Code skill

---

<div align="center">

Built as a [Claude Code](https://claude.ai/claude-code) skill · v1.0.0

</div>
