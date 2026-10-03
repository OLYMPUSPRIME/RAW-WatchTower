# 🛡️ WATCHTOWER — Quiz 01

![Course](https://img.shields.io/badge/Project-WATCHTOWER-6f42c1?style=for-the-badge)
![Topic](https://img.shields.io/badge/Topic-Cybersecurity-0A66C2?style=for-the-badge)
![Quiz](https://img.shields.io/badge/Quiz-01-2ea44f?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-4-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Quiz 01** — Security, Convenience, MFA, Attack Surface & Account Management

---

## 📋 Quiz Overview

This quiz covers four foundational cybersecurity concepts:

1. ⚖️ Balancing **security and convenience**
2. 🔐 The role of **Multifactor Authentication (MFA)**
3. 🛡️ **Attack surface reduction**
4. 👤 Removing **old and unused accounts**

---

# 🧠 Question 1

### In the context of security and convenience, what does the lesson suggest is crucial?

- [ ] Prioritizing convenience over security
- [x] **Striking the right balance between security and convenience**
- [ ] Ignoring user convenience for maximum security
- [ ] Eliminating convenience for complete security

### ✅ Correct Answer

**Striking the right balance between security and convenience**

### 💡 Why?

Cybersecurity controls need to provide adequate protection without making systems unnecessarily difficult to use. If security becomes excessively inconvenient, users may try to bypass controls or adopt unsafe workarounds.

The goal is therefore to achieve an effective **security–usability balance**.

### 🎨 Concept Diagram

```mermaid
flowchart LR
    A["🔐 Security"] --> C["⚖️ Balanced Approach"]
    B["😊 Convenience"] --> C
    C --> D["🛡️ Effective Protection"]
    C --> E["👤 Better User Experience"]

    classDef security fill:#ffdddd,stroke:#d32f2f,stroke-width:2px,color:#111;
    classDef convenience fill:#ddeeff,stroke:#1976d2,stroke-width:2px,color:#111;
    classDef balance fill:#fff2cc,stroke:#d6a700,stroke-width:3px,color:#111;
    classDef result fill:#ddf5e1,stroke:#2e7d32,stroke-width:2px,color:#111;

    class A security;
    class B convenience;
    class C balance;
    class D,E result;
```

---

# 🔐 Question 2

### What's the role of multifactor authentication in enhancing security?

- [x] **It adds an extra layer of protection beyond usernames and passwords**
- [ ] It complicates user logins
- [ ] It requires users to remember multiple passwords

### ✅ Correct Answer

**It adds an extra layer of protection beyond usernames and passwords**

### 💡 Why?

MFA requires more than one authentication factor. Even if an attacker obtains a user's password, an additional factor can help prevent unauthorized access.

Common authentication factors include:

- 🧠 **Something you know** — password or PIN
- 📱 **Something you have** — phone, security key, authenticator device
- 👆 **Something you are** — fingerprint or other biometric

### 🎨 MFA Protection Diagram

```mermaid
flowchart TD
    A["👤 User"] --> B["🔑 Username + Password"]
    B --> C["📱 Additional Authentication Factor"]
    C --> D["🛡️ MFA Verification"]
    D --> E["✅ Access Granted"]

    B --> X["❌ Password Alone"]
    X --> Y["⚠️ Greater Exposure"]

    classDef identity fill:#ddeeff,stroke:#1976d2,stroke-width:2px,color:#111;
    classDef factor fill:#fff2cc,stroke:#d6a700,stroke-width:2px,color:#111;
    classDef secure fill:#ddf5e1,stroke:#2e7d32,stroke-width:3px,color:#111;
    classDef risk fill:#ffdddd,stroke:#d32f2f,stroke-width:2px,color:#111;

    class A,B identity;
    class C,D factor;
    class E secure;
    class X,Y risk;
```

---

# 🛡️ Question 3

### Why is minimizing the attack surface important in cybersecurity?

- [ ] It simplifies network management
- [ ] It increases the complexity of cybersecurity
- [x] **It reduces potential points of vulnerability**
- [ ] It encourages users to install more software

### ✅ Correct Answer

**It reduces potential points of vulnerability**

### 💡 Why?

The **attack surface** represents the collection of possible entry points that an attacker could potentially exploit.

Reducing unnecessary:

- 🌐 Network exposure
- 🖥️ Services
- 📦 Applications
- 👤 Accounts
- 🔓 Open ports
- ☁️ Publicly exposed resources

can reduce the number of opportunities available to an attacker.

### 🎨 Attack Surface Reduction Diagram

```mermaid
flowchart LR
    A["🌐 Large Attack Surface"] --> B["🔍 Identify Unnecessary Exposure"]
    B --> C["🧹 Remove / Disable Unneeded Resources"]
    C --> D["🛡️ Smaller Attack Surface"]
    D --> E["📉 Fewer Potential Vulnerabilities"]

    classDef large fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef process fill:#fff2cc,stroke:#d6a700,stroke-width:2px,color:#111;
    classDef secure fill:#ddf5e1,stroke:#2e7d32,stroke-width:3px,color:#111;

    class A large;
    class B,C process;
    class D,E secure;
```

---

# 👤 Question 4

### Which key task is mentioned as essential for cybersecurity in the lesson?

- [ ] Allowing users to manage software installations
- [x] **Cleaning up old, unused accounts**
- [ ] Continuously adding new devices to the network

### ✅ Correct Answer

**Cleaning up old, unused accounts**

### 💡 Why?

Old or unused accounts can become security risks, especially when they retain active permissions or access to systems.

Regular account cleanup supports:

- 🔐 Access control
- 👤 Identity management
- 🛡️ Least privilege
- 🧹 Attack-surface reduction
- 🚨 Reduced opportunity for unauthorized access

This is commonly connected to **account lifecycle management**: accounts should be created, maintained, reviewed, disabled, and removed according to their actual business need.

### 🎨 Account Lifecycle Diagram

```mermaid
flowchart LR
    A["👤 Account Created"] --> B["🔐 Access Granted"]
    B --> C["🔎 Periodic Access Review"]
    C --> D{"Still Required?"}
    D -->|Yes| E["✅ Keep & Review"]
    D -->|No| F["🧹 Disable / Remove"]
    F --> G["🛡️ Reduced Attack Surface"]

    classDef account fill:#ddeeff,stroke:#1976d2,stroke-width:2px,color:#111;
    classDef review fill:#fff2cc,stroke:#d6a700,stroke-width:2px,color:#111;
    classDef keep fill:#ddf5e1,stroke:#2e7d32,stroke-width:2px,color:#111;
    classDef remove fill:#ffdddd,stroke:#d32f2f,stroke-width:2px,color:#111;
    classDef result fill:#e6ddff,stroke:#6f42c1,stroke-width:3px,color:#111;

    class A,B account;
    class C,D review;
    class E keep;
    class F remove;
    class G result;
```

---

# 📚 Key Takeaways

| # | Concept | Key Point |
|---|---|---|
| 1 | ⚖️ Security vs Convenience | Effective security should balance protection with usability. |
| 2 | 🔐 MFA | Adds an additional authentication layer beyond passwords. |
| 3 | 🛡️ Attack Surface | Reducing unnecessary exposure reduces potential vulnerability points. |
| 4 | 👤 Account Cleanup | Removing unused accounts helps reduce unnecessary access and exposure. |

---

## 🧩 Security Concepts Connection

```mermaid
flowchart TD
    A["🛡️ Cybersecurity Fundamentals"] --> B["⚖️ Security + Convenience"]
    A --> C["🔐 MFA"]
    A --> D["📉 Attack Surface Reduction"]
    A --> E["👤 Account Lifecycle Management"]

    B --> F["👥 Usable Security"]
    C --> G["🔒 Stronger Authentication"]
    D --> H["🎯 Fewer Exposure Points"]
    E --> H

    F --> I["🛡️ Overall Security Posture"]
    G --> I
    H --> I

    classDef root fill:#6f42c1,stroke:#4a148c,stroke-width:3px,color:#fff;
    classDef concept fill:#ddeeff,stroke:#1976d2,stroke-width:2px,color:#111;
    classDef outcome fill:#ddf5e1,stroke:#2e7d32,stroke-width:2px,color:#111;

    class A root;
    class B,C,D,E concept;
    class F,G,H,I outcome;
```

---

## 📝 Quick Revision

> **Remember:**  
> **Balance → Authenticate → Minimize → Clean Up**
>
> ⚖️ Balance security with convenience  
> 🔐 Strengthen authentication with MFA  
> 🛡️ Minimize the attack surface  
> 🧹 Clean up old and unused accounts

---

**Repository:** `WATCHTOWER`  
**Quiz:** `Quiz 01`  
**Focus:** Cybersecurity Fundamentals
