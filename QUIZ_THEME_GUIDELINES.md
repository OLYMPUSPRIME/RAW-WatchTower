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

## 🎯 Core Theme

All WATCHTOWER Quiz documents should have a consistent:

- 🧠 Cybersecurity learning and assessment style
- 🎨 WATCHTOWER badge and color identity
- 📋 Structured question presentation
- ✅ Clearly identified correct answers
- 💡 Explanations for every answer
- 🏰 Meaningful Mermaid diagrams
- 📚 Key Takeaways
- 🧩 Concept Connection
- 📝 Quick Revision

The quiz content can change completely, but the visual structure and learning experience should remain consistent.

---

## 🏷️ Header and Badges

Every Quiz must begin with:

# 🧠 WATCHTOWER — Quiz <NUMBER>: <TOPIC>

Follow the title with WATCHTOWER badges for:

- Project
- Topic
- Quiz number
- Question count
- Status
- Difficulty when appropriate

Use the `for-the-badge` style.

Preferred colors:

| Element | Color |
|---|---|
| Project | `6f42c1` |
| Topic | `8A2BE2` |
| Status | `success` |

Do not introduce a completely different badge palette for individual quizzes.

---

## 📋 Quiz Overview

Immediately after the badges:

## 📋 Quiz Overview

Include:

- 🎯 Topic
- 🔢 Number of questions
- 📈 Difficulty
- 🎓 Learning objective
- 🛡️ Security domain when useful

Preferred table:

| Field | Details |
|---|---|
| Topic | <Topic> |
| Questions | <Count> |
| Difficulty | <Difficulty> |
| Focus | <Learning focus> |

---

## 🎯 Quiz Objective

State what the learner should understand after completing the quiz.

> **Objective:** Test your understanding of the security concepts covered in this quiz.

The objective must match the actual quiz content.

---

## 📝 Question Structure

Each question must have its own clearly separated section.

Use:

## ❓ Question 1

For multiple-choice questions:

- **A.** Option
- **B.** Option
- **C.** Option
- **D.** Option

Do not combine all questions into one large block.

---

## 🧠 Answer Presentation

Every question should clearly show the correct answer.

Use:

### ✅ Correct Answer

> **B. <Correct answer>**

Then:

### 💡 Why?

Explain why the answer is correct and connect it to the cybersecurity concept being tested.

The explanation should be educational, technically accurate, and useful for revision.

---

## 🏰 Mermaid Diagrams

Use Mermaid diagrams where they improve understanding.

Quiz 3 is the primary reference for diagram usage.

Suitable diagrams include:

- Security-policy flow
- Attack / defense flow
- Authentication flow
- Incident-response flow
- Security decision tree
- Control relationship
- Concept map

Rules:

- Diagram the concept being tested.
- Keep diagrams simple.
- Use meaningful labels.
- Do not add diagrams merely for decoration.
- Prefer `flowchart TD` for straightforward security relationships.

---

## 🧩 Concept Connection

After the questions, include:

## 🧩 Concept Connection

A Mermaid diagram is preferred.

The diagram should show how the actual quiz concepts relate to each other.

---

## 📚 Key Takeaways

Use:

## 📚 Key Takeaways

Provide approximately 5–10 concise learning points.

Important cybersecurity concepts should be **bolded**.

The takeaways should summarize the quiz rather than introduce unrelated concepts.

---

## 📝 Quick Revision

Every quiz should end with:

## 📝 Quick Revision

Prefer a table:

| Concept | Remember |
|---|---|
| <Concept> | <Short explanation> |
| <Concept> | <Short explanation> |
| <Concept> | <Short explanation> |

This should be useful for exam and interview revision.

---

## 🎨 Visual Consistency

Maintain the WATCHTOWER visual identity.

| Element | Standard |
|---|---|
| Project color | `6f42c1` |
| Topic accent | `8A2BE2` |
| Badge style | `for-the-badge` |
| Question icon | ❓ |
| Correct answer | ✅ |
| Explanation | 💡 |
| Key Takeaways | 📚 |
| Concept Connection | 🧩 |
| Quick Revision | 📝 |
| Main diagram | Mermaid |

---

## 🔢 Question Count

The quiz number and question count must reflect the actual quiz.

Examples:

- Quiz 3 → 3 questions
- Quiz 8 → 5 questions
- Quiz 9 → 3 questions
- Quiz 10 → requested count
- Quiz 11 → requested count

Never add extra questions simply to fill a template.

---

## 🧠 Question Quality

Every question should:

- Test a specific cybersecurity concept.
- Have one clearly defensible answer unless multiple answers are explicitly requested.
- Use plausible distractors.
- Avoid trick wording and ambiguity.
- Match the source material and difficulty.
- Test understanding rather than keyword recognition.
- Avoid unnecessarily repeating another question.

---

## 🛡️ Cybersecurity Context

Where relevant, connect questions to concepts such as:

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

Only include concepts relevant to the quiz.

---

## 🚫 Things NOT to Change

Unless explicitly requested:

- ❌ Do not turn the quiz into a plain numbered list.
- ❌ Do not remove the WATCHTOWER header and badges.
- ❌ Do not remove the Quiz Overview.
- ❌ Do not remove individual question sections.
- ❌ Do not remove **✅ Correct Answer**.
- ❌ Do not remove **💡 Why?**.
- ❌ Do not remove useful Mermaid diagrams.
- ❌ Do not remove **📚 Key Takeaways**.
- ❌ Do not remove **🧩 Concept Connection**.
- ❌ Do not remove **📝 Quick Revision**.
- ❌ Do not invent a new visual theme for every quiz.
- ❌ Do not use irrelevant diagrams or filler.
- ❌ Do not change the question count requested by the user.

---

## 🔄 Standard Quiz Structure

1. 🧠 Quiz Title
2. 🏷️ Badges
3. 📋 Quiz Overview
4. 🎯 Quiz Objective
5. ❓ Questions
   - Options
   - ✅ Correct Answer
   - 💡 Why?
   - Optional diagram
6. 🧩 Concept Connection
7. 📚 Key Takeaways
8. 📝 Quick Revision

This is the standard WATCHTOWER Quiz format.

---

## 📁 File Naming Convention

Use:

`Quiz_<NUMBER>_<Topic_Name>.md`

Example:

`Quiz_03_Example_Employee_Security_Policy.md`

Rules:

- Use the quiz number.
- Use descriptive topic words.
- Use underscores instead of spaces.
- Keep the naming consistent with existing quiz files.

---

## 📌 Primary Reference

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

The **content must be new**, but the **presentation should look like it belongs to the same WATCHTOWER Quiz series**.

---

## 🏆 Golden Rule

> **Same WATCHTOWER identity. Same Quiz structure. New cybersecurity topic.**

Every new WATCHTOWER Quiz should look like it belongs beside **Quiz 3** in the same repository.

---

**WATCHTOWER | Quiz Theme Guidelines | Reference: Quiz 3**
