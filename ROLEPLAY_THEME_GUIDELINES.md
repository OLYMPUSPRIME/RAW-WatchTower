# 🎭 WATCHTOWER — Role Play Theme Guidelines

![Project](https://img.shields.io/badge/Project-WATCHTOWER-6f42c1?style=for-the-badge)
![Document](https://img.shields.io/badge/Document-Role%20Play%20Theme-8A2BE2?style=for-the-badge)
![Reference](https://img.shields.io/badge/Reference-Role%20Play%205-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Standard-success?style=for-the-badge)

> **Purpose:** This document defines the standard formatting and visual theme for all WATCHTOWER Role Play files.
>
> **Primary Reference:** RolePlay_5_Operational_Security.md
>
> **Rule:** Future WATCHTOWER Role Plays must follow this theme unless the user explicitly requests a different format.

---

## 🎯 1. Core Theme

All WATCHTOWER Role Play documents should have a consistent:

- 🎭 Cybersecurity training / professional learning style
- 🌑 Clean GitHub-friendly Markdown presentation
- 🎨 Purple, green, orange, pink, and blue badge palette
- 🛡️ Security-focused visual language
- 📋 Structured sections with clear hierarchy
- 💬 Conversational role-play format
- 📊 Practical security summaries and checklists
- 🧠 Educational takeaways
- 🏁 Final assessment / conclusion

**Do not create a completely new visual style for each Role Play.**

The subject matter can change, but the document structure and presentation should remain consistent.

---

# 🏷️ 2. Header and Badge Format

Every Role Play must begin with a WATCHTOWER title followed by these badges:

- Project badge: WATCHTOWER, color 6f42c1, style for-the-badge
- Topic badge: topic name, color 8A2BE2, style for-the-badge
- Role Play badge: role-play number, color 2ea44f, style for-the-badge
- Duration badge: 10 minutes by default, color orange, style for-the-badge
- Status badge: Completed, color success, style for-the-badge
- Jennifer badge: Security Strategist, color ff69b4, style for-the-badge
- Venkat Nishit badge: current role, color 007ec6, style for-the-badge

The Venkat role may change depending on the scenario, for example Security Manager, Security Architect, Security Analyst, SOC Analyst, or Security Engineer.

Jennifer should normally remain **Security Strategist**.

---

# 📋 3. Opening Metadata Block

Immediately after the badges, include:

> **Role Play <NUMBER>** — <TOPIC>  
> **Role:** Venkat Nishit — <ROLE>  
> **Security Strategist:** Jennifer

Keep this format consistent across all Role Plays.

---

# 📋 4. Scenario Section

Use the heading:

## 📋 Scenario

The Scenario should:

1. Establish the user's role.
2. Explain the organization's situation.
3. Describe the security problem.
4. Give Jennifer a reason to challenge the user.
5. Clearly establish the learning context.

Use bullets for multiple facts.

---

# 👥 5. Roles Section

Use:

## 👥 Roles

Always define both characters.

### 👩‍💼 Jennifer — Security Strategist

Jennifer is a security strategist who believes in practical, layered security controls.

### 👨‍💻 Venkat Nishit — <ROLE>

As the <ROLE>, Venkat is responsible for evaluating the security situation and recommending appropriate controls.

Keep the descriptions professional and directly related to the scenario.

---

# 🎯 6. Role Play Goals

Use:

## 🎯 Role Play Goals

Goals should normally contain 4–6 numbered learning objectives.

Each goal should begin with an action-oriented verb such as:

- Explain
- Identify
- Describe
- Compare
- Evaluate
- Recommend
- Analyze
- Develop
- Assess

---

# 🎬 7. Role Play Conversation

Use:

# 🎬 Role Play Conversation

This is the most important formatting rule.

## Jennifer formatting

Before every Jennifer section, include the Jennifer badge:

![Jennifer](https://img.shields.io/badge/Jennifer-Security%20Strategist-ff69b4?style=for-the-badge)

Then:

### 👩‍💼 Jennifer — Security Strategist

Jennifer should ask questions that test the user's understanding and introduce the next security concept.

## Venkat formatting

Before every Venkat section, use a right-aligned block:

<div align="right">

![Venkat%20Nishit](https://img.shields.io/badge/Venkat%20Nishit-<ROLE>-007ec6?style=for-the-badge)

### 👨‍💻 Venkat Nishit — <ROLE>

Venkat's answer goes here.

</div>

This alternating visual structure is a **core part of the WATCHTOWER Role Play theme**.

Use horizontal rules between conversation blocks.

---

# 💬 8. Conversation Style

Jennifer should:

- Ask challenging questions.
- Test the user's understanding.
- React positively to strong answers.
- Introduce the next security concept.
- Maintain a professional but conversational tone.

Venkat should:

- Answer technically and accurately.
- Explain the reasoning behind recommendations.
- Use appropriate cybersecurity terminology.
- Connect security controls to business risk.
- Demonstrate practical understanding.

The conversation should feel like a **security interview / mentoring session**, not a simple Q&A.

---

# 🛡️ 9. Security Callouts

Use emojis and bold text for important security concepts.

Examples:

- 🛡️ **Defense in depth**
- 🔐 **Least privilege**
- 🚨 **Incident response**
- ⚠️ **Attack surface**
- 🎯 **Risk reduction**

Do not overuse emojis. They should improve scanning and visual structure.

---

# 📊 10. Security Control Summary

After the conversation, include a practical summary table.

Recommended heading:

## 🛡️ <TOPIC> Control Summary

Preferred structure:

| Security Risk | Recommended Control | Security Objective |
|---|---|---|
| Risk | Control | Objective |

The table should translate the role-play discussion into practical security controls.

---

# ⚠️ 11. Key Risks

Use:

## ⚠️ Key Risks Identified

Create 3–5 focused subsections.

Example:

### ⚠️ Risk Name

Explanation of the risk and why it matters.

Keep the explanations concise but technically meaningful.

---

# 🏰 12. Mermaid Diagram

Where the topic supports it, include a Mermaid architecture or security-flow diagram.

Recommended diagram types:

- Security architecture
- Attack path
- Defense-in-depth
- Network flow
- Incident-response flow
- Authentication flow
- Detection and response flow
- Trust boundaries

The diagram should explain the topic rather than merely decorate the document.

---

# 🔐 13. Defense-in-Depth Diagram

When appropriate, include:

## 🔐 Defense-in-Depth Approach

Use a simple ASCII diagram when it communicates layered controls clearly.

Example:

                    SECURITY
                       │
          ┌────────────┼────────────┐
          │            │            │
          ▼            ▼            ▼
      PREVENTION    DETECTION    RESPONSE
          │            │            │
       Controls      Alerts     Containment
          │            │            │
          └────────────┼────────────┘
                       ▼
                    RECOVERY

---

# 🛡️ 14. Recommended Security Controls

Use:

## 🛡️ Recommended Security Controls

Provide a practical bullet list.

Controls should be specific to the topic.

Examples:

- 🔐 Access controls
- 🛡️ Firewalls
- 📋 Logging
- 📊 Monitoring
- 🚨 Alerting
- 🔄 Continuous improvement

---

# 📋 15. Implementation Checklist

Use:

## 📋 <TOPIC> Implementation Checklist

Use GitHub-compatible checkboxes:

- [ ] Identify the security requirements
- [ ] Assess the current environment
- [ ] Define controls
- [ ] Test the controls
- [ ] Deploy gradually
- [ ] Monitor effectiveness
- [ ] Review and optimize

The checklist should be actionable rather than theoretical.

---

# 🧠 16. Key Takeaways

Use:

## 🧠 Key Takeaways

Include approximately 8–12 concise bullets.

Important concepts should be bolded.

Examples:

- **Least privilege** reduces unnecessary access.
- **Defense in depth** prevents reliance on a single control.
- **Continuous monitoring** improves detection.
- Security controls should be **tested and reviewed regularly**.

---

# 🏁 17. Final Assessment

Every Role Play should end with:

## 🏁 Final Assessment

Include:

1. A strong security principle or conclusion as a blockquote.
2. A short explanation of the lesson.
3. A compact security strategy using arrows.

Example:

> **Assume breach. Design for containment.**

A strong security architecture combines multiple controls.

**Identify → Prevent → Detect → Respond → Recover**

The final assessment should summarize the main security lesson of the Role Play.

---

# 🏷️ 18. Footer

Every Role Play should end with:

---

**Role Play <NUMBER> | <TOPIC>**

Keep the footer consistent.

---

# 🎨 19. Visual Consistency Rules

Maintain these colors:

| Element | Color |
|---|---|
| WATCHTOWER / Project | 6f42c1 |
| Topic | 8A2BE2 |
| Role Play | 2ea44f |
| Duration | orange |
| Status | success |
| Jennifer | ff69b4 |
| Venkat | 007ec6 |

Formatting rules:

- Use H1 for the document title.
- Use H2 for major sections.
- Use H3 for subsections and speakers.
- Use bold for important security concepts.
- Use blockquotes for important statements.
- Use tables for control summaries.
- Use checkboxes for implementation checklists.
- Use Mermaid for meaningful architecture/flow diagrams.
- Use horizontal rules between major conversation blocks.

---

# 🚫 20. Things NOT to Change

Unless explicitly requested by the user:

- ❌ Do not invent a new badge style.
- ❌ Do not remove Jennifer/Venkat speaker badges.
- ❌ Do not remove the right-aligned Venkat conversation blocks.
- ❌ Do not change the core section order.
- ❌ Do not remove the Scenario, Roles, Goals, Conversation, Key Takeaways, or Final Assessment sections.
- ❌ Do not replace the professional cybersecurity tone with casual writing.
- ❌ Do not create a completely different theme for a new Role Play.
- ❌ Do not add unnecessary decorative elements that make the document harder to read.
- ❌ Do not change the WATCHTOWER identity or color scheme.

---

# 🔄 21. Standard Role Play Structure

The standard order is:

1. 🎭 Title
2. 🏷️ Badges
3. 📋 Metadata
4. 📋 Scenario
5. 👥 Roles
6. 🎯 Role Play Goals
7. 🎬 Role Play Conversation
8. 🛡️ Security Control Summary
9. ⚠️ Key Risks Identified
10. 🏰 Security / Architecture Diagram
11. 🔐 Defense-in-Depth Approach
12. 🛡️ Recommended Security Controls
13. 📋 Implementation Checklist
14. 🧠 Key Takeaways
15. 🏁 Final Assessment
16. Footer

Not every Role Play needs every optional diagram, but the **overall structure should remain consistent**.

---

# 📌 22. Reference Document

The primary reference for the visual and conversational style is:

**RolePlay_5_Operational_Security.md**

When generating a new Role Play, use Role Play 5 as the baseline for:

- Badge appearance
- Speaker formatting
- Conversation layout
- Section hierarchy
- Emoji usage
- Tables
- Checklists
- Mermaid diagrams
- Final assessment
- Overall GitHub presentation

The **content should be new**, but the **presentation should feel like it belongs to the same WATCHTOWER Role Play series**.

---

# 🧠 Golden Rule

> **Same WATCHTOWER identity. Same Role Play structure. New cybersecurity topic.**

Every new Role Play should look like it belongs beside Role Play 5 in the same repository.

---

**WATCHTOWER | Role Play Theme Guidelines | Reference: Role Play 5**
