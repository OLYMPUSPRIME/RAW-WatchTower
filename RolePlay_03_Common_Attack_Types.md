# 🎭 WATCHTOWER — Role Play 3: Common Attack Types

![Project](https://img.shields.io/badge/Project-WATCHTOWER-6f42c1?style=for-the-badge)
![Topic](https://img.shields.io/badge/Topic-Common%20Attack%20Types-8A2BE2?style=for-the-badge)
![Role Play](https://img.shields.io/badge/Role%20Play-3-2ea44f?style=for-the-badge)
![Duration](https://img.shields.io/badge/Duration-10%20minutes-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Jennifer](https://img.shields.io/badge/Jennifer-Incident%20Response%20Strategist-ff69b4?style=for-the-badge)
![Venkat%20Nishit](https://img.shields.io/badge/Venkat%20Nishit-Security%20Operations%20Manager-007ec6?style=for-the-badge)

> **Role Play 3** — Common Attack Types  
> **Role:** Venkat Nishit — Security Operations Manager  
> **Incident Response Strategist:** Jennifer

---

## 🎯 Scenario

You are the **Security Operations Manager** at a mid-sized company.

During the past 48 hours, the security team observed:

- 🌐 The public website went offline because of massive traffic spikes.
- 🔎 Network monitoring detected an unknown device beaconing outbound at approximately 3 a.m.
- 🗄️ A developer reported suspicious database behavior on a customer portal.

Leadership wants to understand what happened, determine the likely attack types, and establish an effective response.

Jennifer, an incident response strategist, guides the investigation and response planning.

---

## 👥 Roles

### Jennifer — Incident Response Strategist

Jennifer is a calm, experienced incident response strategist. She is analytical and methodical under pressure, with a focus on:

- Incident containment
- Root-cause analysis
- Long-term resilience
- Evidence preservation
- Decisive response

### Venkat Nishit — Security Operations Manager

Responsible for:

- Identifying attack types
- Coordinating incident response
- Containing affected systems
- Investigating indicators of compromise
- Strengthening security controls

---

# 🎯 Learning Goals

## 1. Differentiate Between DDoS, APT, and SQL Injection

### DDoS — Distributed Denial of Service

A DDoS attack attempts to overwhelm a service with excessive traffic, preventing legitimate users from accessing it.

**Scenario indicator:**
- Website receives approximately 50× normal traffic.
- Website becomes unavailable.

### APT — Advanced Persistent Threat

An APT involves an attacker maintaining unauthorized access to a target environment over an extended period.

**Scenario indicator:**
- Unknown device performing outbound beaconing at 3 a.m.
- Potential communication with malicious infrastructure.

### SQL Injection

SQL injection exploits insufficiently protected database queries to manipulate or retrieve database information.

**Scenario indicator:**
- Suspicious database behavior on the customer portal.
- Potential exploitation of a web application vulnerability.

---

## 2. Explain the Objective and Impact of Each Attack

| Attack Type | Primary Objective | Potential Impact |
|---|---|---|
| **DDoS** | Overwhelm a service with traffic | Service outage and loss of availability |
| **APT** | Maintain persistent unauthorized access | Data theft, espionage, lateral movement, long-term compromise |
| **SQL Injection** | Manipulate or retrieve database data | Data disclosure, modification, corruption, or unauthorized access |

---

## 3. Identify Early Warning Signs of Long-Term Network Compromise

Important indicators discussed during the roleplay included:

- Unknown outbound network connections
- Unusual beaconing activity
- Communication with suspicious or known malicious infrastructure
- Activity occurring at unusual times
- Unexpected database behavior
- Suspicious authentication or credential activity
- Correlation of endpoint and network events through SIEM/EDR
- Threat-intelligence matches for suspicious destinations

The investigation should determine whether the DDoS activity is isolated or potentially being used as a distraction for another intrusion.

---

## 4. Recommend Immediate Containment and Mitigation

### DDoS Response

Initial containment and mitigation actions:

1. Confirm the abnormal traffic pattern using monitoring and logs.
2. Distinguish malicious traffic from legitimate traffic.
3. Apply traffic filtering.
4. Implement rate limiting where appropriate.
5. Engage a dedicated DDoS mitigation service if required.
6. Continue monitoring service availability.

### Unknown Beaconing Device

1. Investigate the endpoint using EDR.
2. Correlate endpoint and network events in the SIEM.
3. Identify the destination IP/domain.
4. Check threat-intelligence sources.
5. Isolate the affected endpoint if compromise is suspected.
6. Preserve relevant evidence.

### Suspicious Database Activity

1. Review application and database logs.
2. Determine whether the activity was authorized.
3. Investigate for possible SQL injection.
4. Check for compromised or abused credentials.
5. Contain affected systems if required.
6. Preserve evidence for forensic investigation.

---

## 5. Develop Layered Defense Strategies

The following controls were identified for reducing future risk:

- 🛡️ SIEM-based centralized monitoring and correlation
- 🖥️ EDR for endpoint investigation and containment
- 🌐 Network-flow analysis
- 🔍 Threat-intelligence feeds
- 🔐 Least-privilege access
- 🧱 Network segmentation
- 🔄 Regular vulnerability management and patching
- 💾 Tested and protected backups
- 📊 Continuous security monitoring
- 📋 Updated incident-response playbooks
- 🧪 Regular incident-response exercises and tabletop simulations
- ⏱️ Measuring incident-response times
- 📝 Documenting lessons learned after incidents

This provides a layered defense covering **prevention, detection, response, containment, recovery, and continuous improvement**.

---

# 💬 Key Role Play Discussion

### Situation 1 — Website Traffic Spike

**Jennifer:** If your website suddenly receives 50 times its normal traffic and becomes unavailable, is that a success problem — or an attack?

**Response:** Treat it as a likely **DDoS attack**. Confirm the traffic pattern using monitoring and logs, then apply rate limiting, traffic filtering, and DDoS protection while maintaining service availability.

**Jennifer's feedback:** The traffic surge strongly indicates DDoS, but monitoring is important to distinguish an attack from legitimate high traffic.

---

### Situation 2 — Post-Containment Investigation

**Jennifer:** What would you prioritize next after initial containment?

**Response:** Prioritize **root-cause analysis and evidence preservation**. Review logs, traffic sources, affected systems, and indicators of compromise to determine whether the DDoS was isolated or potentially a distraction for another attack. Strengthen monitoring and update the incident-response plan based on lessons learned.

**Jennifer's feedback:** Root-cause analysis can reveal hidden threats, while preserved evidence supports forensic or legal investigation.

---

### Situation 3 — Security Tools and Investigation

**Jennifer:** What tools or techniques would you explore?

**Response:** Use **SIEM and EDR** for centralized monitoring and investigation, network-flow analysis for unusual traffic, secure log retention with synchronized timestamps, and threat-intelligence feeds for known malicious indicators.

**Jennifer's feedback:** These controls help correlate events, identify malicious infrastructure, preserve forensic evidence, and improve detection.

---

### Situation 4 — Applying the Strategy to Other Incidents

**Jennifer:** How would you apply these strategies to the outbound beaconing and suspicious database activity?

**Response:** For the beaconing device, investigate with EDR, correlate the activity in SIEM, and check threat intelligence for the destination. For the database activity, review database and application logs, verify whether the activity was authorized, and investigate for SQL injection or compromised credentials. Contain affected systems while preserving evidence.

**Jennifer's feedback:** The approach correctly combines investigation, threat intelligence, containment, and evidence preservation.

---

### Situation 5 — Team Preparedness

**Jennifer:** How prepared is your team to handle these types of incidents?

**Response:** The team is reasonably prepared, but should continue improving through regular incident-response exercises and tabletop simulations. Playbooks for DDoS, endpoint compromise, and SQL injection should be reviewed and refined. Response times and lessons learned should be measured after each exercise.

**Jennifer's feedback:** Regular exercises keep the team prepared, clarify responsibilities, and identify response gaps.

---

### Situation 6 — Further Defensive Improvements

**Jennifer:** What else could you do to further strengthen the defenses?

**Response:** Strengthen continuous monitoring, vulnerability management, threat intelligence, patching, least-privilege access, network segmentation, and tested backups. Combine these preventive controls with incident-response exercises to create a strong layered defense.

---

# 🧠 Key Takeaways

### DDoS
> Focuses on **availability** by overwhelming a service with traffic.

### APT
> Focuses on **persistent unauthorized access** and potentially long-term compromise.

### SQL Injection
> Targets **database-backed applications** and can allow unauthorized reading or modification of data.

### SOC/Incident Response Approach

**Detect → Validate → Contain → Investigate → Eradicate → Recover → Learn → Improve**

---

# ✅ Goal Completion

| Goal | Status |
|---|---|
| Differentiate DDoS, APT, and SQL Injection | ✅ Achieved |
| Explain objective and impact of each attack | ✅ Achieved |
| Identify early warning signs of long-term compromise | ✅ Achieved |
| Recommend immediate containment and mitigation | ✅ Achieved |
| Develop layered defense strategies | ✅ Achieved |

## 🏆 Final Status

**All 5 learning goals were successfully met.**

**Role Play 03 — Common Attack Types: COMPLETE ✅**

---

## 🔑 Skills Practiced

- DDoS identification
- APT indicators
- SQL injection awareness
- Incident triage
- SIEM investigation
- EDR investigation
- Network-flow analysis
- Threat intelligence
- Evidence preservation
- Incident containment
- Root-cause analysis
- Incident-response planning
- Layered defense
- Security operations management

---

**WATCHTOWER — Cybersecurity & SOC Learning Project** 🛡️
