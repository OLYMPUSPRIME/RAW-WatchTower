# 🛡️ WATCHTOWER — Quiz 02

![Course](https://img.shields.io/badge/Project-WATCHTOWER-6f42c1?style=for-the-badge)
![Topic](https://img.shields.io/badge/Topic-Social%20Engineering-0A66C2?style=for-the-badge)
![Quiz](https://img.shields.io/badge/Quiz-02-2ea44e?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-3-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Quiz 02** — Social Engineering

---

## 📋 Quiz Overview

This quiz covers three key concepts related to social engineering:

1. 👤 Human trust as a security risk
2. 🧠 How to make employees more cautious
3. 🛡️ Discouraging unsafe trust in online content

---

# 👤 Question 1

### What is one of the key risks associated with social engineering in cybersecurity?

- [ ] Inadequate physical security measures
- [x] **Employees trusting and helping individuals when they shouldn't**
- [ ] Over-reliance on technology

### ✅ Correct Answer

**Employees trusting and helping individuals when they shouldn't**

### 💡 Why?

Social engineering attacks exploit human behavior rather than relying only on technical vulnerabilities.

Attackers may use:

- 🤝 Trust and helpfulness
- 🎭 Impersonation
- ⏱️ Urgency
- 👔 Authority
- 🗣️ Persuasion

An employee may unintentionally provide access, information, or assistance to an unauthorized person because the request appears legitimate.

### 🎨 Human Trust as an Attack Surface

```mermaid
flowchart LR
    A["👤 Employee"] --> B["🤝 Trust / Helpfulness"]
    B --> C["🎭 Social Engineer"]
    C --> D["⚠️ Manipulation"]
    D --> E["🔓 Unauthorized Access or Information"]

    classDef employee fill:#ddeeff,stroke:#1976d2,stroke-width:2px,color:#111;
    classDef human fill:#fff2cc,stroke:#d6a700,stroke-width:2px,color:#111;
    classDef attacker fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef outcome fill:#ddf5e1,stroke:#2e7d32,stroke-width:3px,color:#111;

    class A employee;
    class B human;
    class C,D attacker;
    class E outcome;
```

---

# 🧠 Question 2

### What approach is suggested to train employees to be more cautious in social engineering scenarios?

- [ ] Encourage them to always trust newcomers
- [x] **Reinforce a security penetration tactic involving diverse individuals**
- [ ] Avoid discussing security vulnerabilities with employees
- [ ] Discourage employees from questioning the legitimacy of external requests

### ✅ Correct Answer

**Reinforce a security penetration tactic involving diverse individuals**

### 💡 Why?

The key lesson is to reinforce awareness that social engineering can involve different types of people and approaches.

Employees should avoid making assumptions based on appearance, role, familiarity, or confidence. Instead, they should:

- 🔎 Verify identities and requests
- 🪪 Check authorization
- ❓ Question unusual requests
- 🚨 Report suspicious behavior
- 🛡️ Follow established security procedures

The goal is to move from **“trust first”** to **“verify first.”**

### 🎨 Trust → Verification

```mermaid
flowchart TD
    A["👤 Unfamiliar Person or Request"] --> B{"🔎 Verify?"}
    B -->|No| C["⚠️ Trust Assumption"]
    C --> D["🎭 Social Engineering Risk"]
    B -->|Yes| E["🪪 Verify Identity / Authorization"]
    E --> F["✅ Legitimate"]
    E --> G["🚨 Suspicious"]
    G --> H["📢 Report / Escalate"]

    classDef start fill:#ddeeff,stroke:#1976d2,stroke-width:2px,color:#111;
    classDef decision fill:#fff2cc,stroke:#d6a700,stroke-width:3px,color:#111;
    classDef risk fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef safe fill:#ddf5e1,stroke:#2e7d32,stroke-width:2px,color:#111;

    class A start;
    class B decision;
    class C,D,G,H risk;
    class E,F safe;
```

---

# 🛡️ Question 3

### Which of the following is a critical aspect of discouraging trust in social engineering scenarios?

- [ ] Emphasizing the importance of rapid response to external requests
- [ ] Allowing employees to download software from unverified sources
- [ ] Encouraging participation in online surveys
- [x] **Discouraging trust in anything found online, including downloads and surveys**

### ✅ Correct Answer

**Discouraging trust in anything found online, including downloads and surveys**

### 💡 Why?

Online content can be used as a vehicle for social engineering. Attackers may use malicious downloads, fake surveys, deceptive links, or convincing websites to manipulate users.

Employees should therefore:

- 🔎 Verify the source before trusting online content
- 📥 Avoid downloading software from unverified sources
- 📝 Treat unexpected surveys and requests cautiously
- 🔗 Be careful with unfamiliar links
- 🚨 Report suspicious activity

The principle is simple: **online content should not automatically be trusted.**

### 🎨 Online Trust Verification

```mermaid
flowchart LR
    A["🌐 Online Content"] --> B{"🔎 Can the Source Be Trusted?"}
    B -->|No| C["🚫 Do Not Interact"]
    C --> D["📢 Report if Suspicious"]
    B -->|Yes| E["✅ Verify Further"]
    E --> F["📥 Safe Action"]

    classDef online fill:#ddeeff,stroke:#1976d2,stroke-width:2px,color:#111;
    classDef decision fill:#fff2cc,stroke:#d6a700,stroke-width:3px,color:#111;
    classDef danger fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef safe fill:#ddf5e1,stroke:#2e7d32,stroke-width:2px,color:#111;

    class A online;
    class B decision;
    class C,D danger;
    class E,F safe;
```

---

# 📚 Key Takeaways

| # | Concept | Key Point |
|---|---|---|
| 1 | 👤 Human Trust | Social engineering exploits trust, helpfulness, authority, and urgency. |
| 2 | 🧠 Awareness | Employees should verify identities and requests instead of making assumptions. |
| 3 | 🛡️ Online Trust | Treat downloads, surveys, links, and other online content cautiously and verify sources. |

---

## 🔐 Social Engineering Defense Model

```mermaid
flowchart TD
    A["🎭 Social Engineering"] --> B["🤝 Exploit Human Trust"]
    A --> C["⏱️ Create Urgency"]
    A --> D["👔 Impersonate Authority"]
    A --> E["🌐 Use Online Content"]

    B --> F["🔎 Verify"]
    C --> F
    D --> F
    E --> F

    F --> G["🛡️ Secure Decision"]
    G --> H["🚨 Report Suspicious Activity"]

    classDef threat fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef control fill:#fff2cc,stroke:#d6a700,stroke-width:2px,color:#111;
    classDef outcome fill:#ddf5e1,stroke:#2e7d32,stroke-width:3px,color:#111;

    class A,B,C,D,E threat;
    class F control;
    class G,H outcome;
```

---

## 📝 Quick Revision

> **Remember:**  
> **Don't Trust Automatically → Verify → Report**
>
> 👤 Be aware that human trust can be exploited  
> 🔎 Verify identities, requests, and sources  
> 🌐 Treat online downloads and surveys cautiously  
> 🚨 Report suspicious activity

---

**Repository:** `WATCHTOWER`  
**Quiz:** `Quiz 02`  
**Focus:** Social Engineering
