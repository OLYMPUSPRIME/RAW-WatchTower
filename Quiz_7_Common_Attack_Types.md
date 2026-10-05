# 🛡️ WATCHTOWER — Quiz 07

![Course](https://img.shields.io/badge/Project-WATCHTOWER-6f42c1?style=for-the-badge)
![Topic](https://img.shields.io/badge/Topic-Common%20Attack%20Types-0A66C2?style=for-the-badge)
![Quiz](https://img.shields.io/badge/Quiz-07-2ea44f?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-3-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Quiz 07** — Common Attack Types

---

## 📋 Quiz Overview

This quiz covers three common cybersecurity attack types:

1. 🌐 Distributed Denial of Service (DDoS)
2. 🕵️ Advanced Persistent Threats (APT)
3. 🗄️ SQL Injection

---

# 🌐 Question 1

### What is the primary objective of a distributed denial of service (DDoS) attack?

- [ ] To steal sensitive data from a network
- [ ] To access and modify database tables
- [x] **To make a website or application unavailable by overwhelming it with traffic**
- [ ] To infiltrate a network and establish long-term access

### ✅ Correct Answer

**To make a website or application unavailable by overwhelming it with traffic.**

### 💡 Why?

A DDoS attack attempts to overwhelm a target service with a large volume of traffic or requests. The goal is to consume resources such as bandwidth, server capacity, or application resources so legitimate users cannot access the service normally.

### 🎨 DDoS Attack Concept

```mermaid
flowchart LR
    A["🤖 Attacker-Controlled Sources"] --> B["🌐 Massive Traffic"]
    B --> C["🖥️ Target Website / Application"]
    C --> D["⚠️ Service Unavailable"]

    E["👤 Legitimate Users"] --> C

    classDef source fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef traffic fill:#fff2cc,stroke:#d6a700,stroke-width:3px,color:#111;
    classDef target fill:#e6ddff,stroke:#6f42c1,stroke-width:3px,color:#111;
    classDef impact fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef user fill:#ddeeff,stroke:#1976d2,stroke-width:2px,color:#111;

    class A source;
    class B traffic;
    class C target;
    class D impact;
    class E user;
```

---

# 🕵️ Question 2

### What characterizes an advanced persistent threat (APT)?

- [x] **Continuous, long-term access to a network by an attacker**
- [ ] An attack aimed at exhausting a network's bandwidth
- [ ] A method of modifying data in a database

### ✅ Correct Answer

**Continuous, long-term access to a network by an attacker.**

### 💡 Why?

An **Advanced Persistent Threat (APT)** is typically a targeted campaign in which an attacker gains access to a system or network and attempts to maintain that access over an extended period.

APT activity is characterized by:

- 🎯 Targeted attacks
- 🕵️ Stealth and persistence
- ⏳ Long-term access
- 🔍 Reconnaissance and monitoring
- 🗄️ Potential theft or compromise of sensitive information

Unlike a DDoS attack, which primarily focuses on availability, an APT generally focuses on maintaining access and achieving longer-term objectives.

### 🎨 APT Concept

```mermaid
flowchart TD
    A["🎯 Target Organization"] --> B["🔓 Initial Compromise"]
    B --> C["🕵️ Maintain Access"]
    C --> D["⏳ Long-Term Persistence"]
    D --> E["📊 Monitor / Collect Information"]

    classDef target fill:#ddeeff,stroke:#1976d2,stroke-width:2px,color:#111;
    classDef compromise fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef persistence fill:#fff2cc,stroke:#d6a700,stroke-width:3px,color:#111;
    classDef collection fill:#e6ddff,stroke:#6f42c1,stroke-width:3px,color:#111;

    class A target;
    class B compromise;
    class C,D persistence;
    class E collection;
```

---

# 🗄️ Question 3

### What kind of data manipulation is possible after a successful SQL injection attack?

- [ ] Changing user passwords and access rights
- [x] **Reading and altering data within a database**
- [ ] Modifying CPU and memory usage on a network

### ✅ Correct Answer

**Reading and altering data within a database.**

### 💡 Why?

A **SQL injection** attack exploits weaknesses in an application's handling of database queries. If successful, an attacker may be able to manipulate database queries beyond their intended purpose.

Depending on the application's permissions and database configuration, this can potentially allow an attacker to:

- 📖 Read database records
- ✏️ Alter existing data
- ➕ Insert unauthorized data
- 🗑️ Delete data
- 🔐 Access information that should be protected

Strong input validation, parameterized queries, prepared statements, and appropriate database permissions are important defenses against SQL injection.

### 🎨 SQL Injection Concept

```mermaid
flowchart LR
    A["👤 Attacker"] --> B["🌐 Vulnerable Application"]
    B --> C["🗄️ Database"]
    C --> D["📖 Read Data"]
    C --> E["✏️ Alter Data"]

    classDef attacker fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef app fill:#e6ddff,stroke:#6f42c1,stroke-width:3px,color:#111;
    classDef database fill:#fff2cc,stroke:#d6a700,stroke-width:3px,color:#111;
    classDef impact fill:#ffdddd,stroke:#d32f2f,stroke-width:2px,color:#111;

    class A attacker;
    class B app;
    class C database;
    class D,E impact;
```

---

# 📚 Key Takeaways

| # | Attack Type | Primary Characteristic |
|---|---|---|
| 1 | 🌐 DDoS | Overwhelms a service with traffic to make it unavailable. |
| 2 | 🕵️ APT | Maintains targeted, long-term access to a network. |
| 3 | 🗄️ SQL Injection | Can allow unauthorized reading or alteration of database data. |

---

## 🧩 Attack Types at a Glance

```mermaid
flowchart TD
    A["🛡️ Common Attack Types"] --> B["🌐 DDoS"]
    A --> C["🕵️ APT"]
    A --> D["🗄️ SQL Injection"]

    B --> E["🎯 Availability"]
    C --> F["⏳ Persistence"]
    D --> G["📊 Database Manipulation"]

    classDef root fill:#e6ddff,stroke:#6f42c1,stroke-width:3px,color:#111;
    classDef attack fill:#ffdddd,stroke:#d32f2f,stroke-width:3px,color:#111;
    classDef objective fill:#fff2cc,stroke:#d6a700,stroke-width:2px,color:#111;

    class A root;
    class B,C,D attack;
    class E,F,G objective;
```

---

## 📝 Quick Revision

> **Remember:**  
> **DDoS → Disrupt · APT → Persist · SQL Injection → Manipulate**
>
> 🌐 **DDoS** — Targets availability by overwhelming a service.  
> 🕵️ **APT** — Focuses on persistent, long-term access.  
> 🗄️ **SQL Injection** — Exploits vulnerable database queries to potentially read or modify data.

---

**Repository:** `WATCHTOWER`  
**Quiz:** `Quiz 07`  
**Focus:** Common Attack Types
