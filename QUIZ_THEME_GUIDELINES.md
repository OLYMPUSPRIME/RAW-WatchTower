# 🧠 WATCHTOWER — Quiz Theme Guidelines

![Project](https://img.shields.io/badge/Project-WATCHTOWER-6f42c1?style=for-the-badge)
![Document](https://img.shields.io/badge/Document-Quiz%20Theme-8A2BE2?style=for-the-badge)
![Reference](https://img.shields.io/badge/Reference-Quiz%2003-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Standard-success?style=for-the-badge)

> **Purpose:** Standard formatting, visual theme, structure, and presentation rules for all WATCHTOWER Quiz Markdown files.
>
> **Primary Reference:** Quiz_03_Example_Employee_Security_Policy.md
>
> **Rule:** Future WATCHTOWER quizzes must follow this theme unless the user explicitly requests a different format.

---

## 🎯 1. Core Theme

All WATCHTOWER Quiz documents should have a consistent:

- 🧠 Cybersecurity learning and assessment style
- 🎨 WATCHTOWER badge and color identity
- 📋 Structured question presentation
- ✅ Clearly identified correct answers
- 💡 Explanations for every answer
- 🏰 Meaningful Mermaid diagrams
- 📚 Key Takeaways
- 🧩 Concept Connection section
- 📝 Quick Revision section

The quiz content can change completely, but the visual structure and learning experience should remain consistent.

**Do not create a generic question list for a new quiz.**

---

# 🏷️ 2. Header and Badge Format

Every Quiz must begin with:

# 🧠 WATCHTOWER — Quiz <NUMBER>: <TOPIC>

Follow the title with WATCHTOWER badges.

Standard badges:

- Project: WATCHTOWER
- Topic: current quiz topic
- Quiz: current quiz number
- Questions: actual question count
- Status: Completed
- Difficulty: when appropriate

Use the same for-the-badge style used by the Role Play theme.

Preferred WATCHTOWER project color: 6f42c1

Preferred topic accent: 8A2BE2

Status: success

Do not introduce a completely different badge palette for individual quizzes.

---

# 📋 3. Quiz Overview

Immediately after the badges, include:

## 📋 Quiz Overview

The overview should briefly identify:

- 🎯 Topic
- 🔢 Number of questions
- 📈 Difficulty
- 🎓 Learning objective
- 🛡️ Security domain, when useful

Keep the overview concise.

Preferred structure:

| Field | Details |
|---|---|
| Topic | <Topic> |
| Questions | <Count> |
| Difficulty | <Difficulty> |
| Focus | <Learning focus> |

Adapt the fields to the actual quiz.

---

# 🎯 4. Quiz Objective

State what the learner should understand after completing the quiz.

Example:

> **Objective:** Test your understanding of the security concepts covered in this quiz.

The objective must match the actual quiz content.

---

# 📝 5. Question Structure

Each question should have its own clearly separated section.

Use:

## ❓ Question 1

Then present the question in a clean, readable format.

For multiple-choice questions, show options clearly:

- **A.** Option
- **B.** Option
- **C.** Option
- **D.** Option

For other formats, preserve the format actually requested by the user.

**Do not combine all questions into one large block.**

---

# 🧠 6. Answer Presentation

Every question should clearly show the correct answer.

Use:

### ✅ Correct Answer

> **B. <Correct answer>**

Then immediately provide:

### 💡 Why?

Explain why the answer is correct and connect it to the cybersecurity concept being tested.

The explanation should be educational rather than simply saying that the answer is correct.

---

# 📚 7. Answer Explanation Rules

For every question:

1. Identify the correct answer.
2. Explain the underlying security concept.
3. Explain why it matters in a real environment.
4. Keep the explanation technically accurate.
5. Avoid unnecessary repetition.

When useful, briefly explain why major distractors are incorrect.

Do not reveal the answer before the question is presented.

---

# 🏰 8. Mermaid Diagrams

Use Mermaid diagrams where they improve understanding.

Quiz 3 is the primary reference for using diagrams as part of the learning material.

Good diagram types include:

- Security-policy flow
- Attack / defense flow
- Authentication flow
- Incident-response flow
- Security decision tree
- Control relationship
- Concept map

Example structure:

flowchart TD
    A["Employee"] --> B["Security Policy"]
    B --> C["Required Behavior"]
    C --> D["Security Control"]
    D --> E["Risk Reduction"]

### Diagram Rules

- Diagram the concept being tested.
- Keep diagrams simple enough to understand quickly.
- Use meaningful labels.
- Do not add diagrams merely for decoration.
- Prefer flowchart TD for straightforward security relationships.
- Use emojis in node labels when they improve readability.

---

# 🧩 9. Concept Connection

After the individual questions, include a section showing how the quiz concepts connect.

Use:

## 🧩 Concept Connection

A Mermaid diagram is preferred.

Example:

flowchart LR
    A["Policy"] --> B["Employee Behavior"]
    B --> C["Security Controls"]
    C --> D["Risk Reduction"]
    D --> E["Security Posture"]

The connection diagram should represent the actual concepts covered by the quiz.

---

# 📚 10. Key Takeaways

Use:

## 📚 Key Takeaways

Provide approximately 5–10 concise learning points.

Important cybersecurity concepts should be **bolded**.

The takeaways should summarize the quiz rather than introduce unrelated concepts.

---

# 📝 11. Quick Revision

Every quiz should end with a compact revision section.

Use:

## 📝 Quick Revision

Prefer a table:

| Concept | Remember |
|---|---|
| <Concept> | <Short explanation> |
| <Concept> | <Short explanation> |
| <Concept> | <Short explanation> |

This section should be useful for reviewing the topic before an exam or interview.

---

# 🎨 12. Visual Consistency

Maintain the WATCHTOWER visual identity across all quizzes.

| Element | Standard |
|---|---|
| Project color | 6f42c1 |
| Topic accent | 8A2BE2 |
| Badge style | for-the-badge |
| Question icon | ❓ |
| Correct answer | ✅ |
| Explanation | 💡 |
| Key Takeaways | 📚 |
| Concept Connection | 🧩 |
| Quick Revision | 📝 |
| Main diagram | Mermaid |

Do not randomly change the color scheme between quizzes.

---

# 🔢 13. Question Count

The quiz number and question count must reflect the actual quiz.

Examples:

- Quiz 3 → 3 questions
- Quiz 8 → 5 questions
- Quiz 9 → 3 questions
- Quiz 10 → actual requested count
- Quiz 11 → actual requested count

Never add extra questions simply to fill a template.

---

# 🧠 14. Question Quality

Every question should:

- Test a specific cybersecurity concept.
- Have one clearly defensible answer unless multiple answers are explicitly requested.
- Use plausible distractors.
- Avoid trick wording.
- Avoid ambiguity.
- Match the difficulty of the source material.
- Be answerable from the learning material.
- Avoid repeating another question's exact concept unnecessarily.

Questions should test **understanding**, not merely keyword recognition.

---

# 🛡️ 15. Cybersecurity Context

Where appropriate, connect questions to relevant concepts such as:

- 🔐 Confidentiality
- 🛡️ Integrity
- 🌐 Availability
- 👤 Identity and access management
- 🚨 Incident response
- 🧑‍💻 Security awareness
- 📋 Security policies
- 🕵️ Threats and vulnerabilities
- 🔎 Monitoring and detection
- 🏰 Defense in depth
- 🔑 Least privilege
- 🎯 Risk reduction

Only include concepts relevant to the actual quiz.

---

# 🚫 16. Things NOT to Change

Unless explicitly requested:

- ❌ Do not turn the quiz into a plain numbered list.
- ❌ Do not remove the WATCHTOWER header and badges.
- ❌ Do not remove the Quiz Overview.
- ❌ Do not remove individual question sections.
- ❌ Do not remove the **✅ Correct Answer** section.
- ❌ Do not remove the **💡 Why?** explanation.
- ❌ Do not remove useful Mermaid diagrams.
- ❌ Do not remove **📚 Key Takeaways**.
- ❌ Do not remove **🧩 Concept Connection**.
- ❌ Do not remove **📝 Quick Revision**.
- ❌ Do not invent a new visual theme for every quiz.
- ❌ Do not use irrelevant diagrams or filler content.
- ❌ Do not change the question count requested by the user.

---

# 🔄 17. Standard Quiz Structure

The normal order should be:

1. 🧠 Quiz Title
2. 🏷️ Badges
3. 📋 Quiz Overview
4. 🎯 Quiz Objective
5. ❓ Question 1
   - Options
   - ✅ Correct Answer
   - 💡 Why?
   - Optional diagram
6. ❓ Question 2
   - Options
   - ✅ Correct Answer
   - 💡 Why?
   - Optional diagram
7. Continue for all questions
8. 🧩 Concept Connection
9. 📚 Key Takeaways
10. 📝 Quick Revision

This is the standard WATCHTOWER Quiz format.

---

# 📁 18. File Naming Convention

Use:

Quiz_<NUMBER>_<Topic_Name>.md

Example:

Quiz_03_Example_Employee_Security_Policy.md

Rules:

- Use the quiz number.
- Use descriptive topic words.
- Use underscores instead of spaces.
- Keep the filename consistent with the repository's existing quiz naming convention.

---

# 📌 19. Primary Reference

The primary visual and structural reference is:

**Quiz_03_Example_Employee_Security_Policy.md**

When generating a new quiz, compare it against Quiz 3 for:

- Header
- Badges
- Overview
- Question formatting
- Correct-answer presentation
- Explanation style
- Mermaid diagrams
- Concept Connection
- Key Takeaways
- Quick Revision
- Overall GitHub presentation

The **quiz content must be new**, but the **presentation should look like it belongs to the same WATCHTOWER quiz series**.

---

# 🏆 Golden Rule

> **Same WATCHTOWER identity. Same Quiz structure. New cybersecurity topic.**

Every new WATCHTOWER Quiz should look like it belongs beside **Quiz 3** in the same repository.

---

**WATCHTOWER | Quiz Theme Guidelines | Reference: Quiz 3**
