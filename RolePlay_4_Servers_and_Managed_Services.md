# 🎭 Role Play 4 — Servers and Managed Services

## 📌 Topic

**Servers and Managed Services**

---

# 🎯 Scenario

Your company currently runs:

- On-premises SQL Server
- On-premises Exchange
- Physical servers in a secured server room

Leadership is considering moving to:

- Microsoft 365
- AWS RDS
- Azure SQL
- Other managed cloud services

They believe:

> **“The cloud is more secure.”**

You must assess:

1. What security responsibilities disappear?
2. What responsibilities remain?
3. What new risks are introduced?

Jennifer will challenge you to think critically about the **Shared Responsibility Model**.

---

# 👥 Roles

## 👩‍💼 Jennifer — Cloud Security Advisor

Jennifer is a strategic cloud security advisor focused on risk ownership rather than hype.

> **“The cloud provider secures the house. You secure the doors.”**

## 👨‍💻 Venkat Nishit — Systems Architect

As the Systems Architect, the responsibilities are to:

- Differentiate on-premises and managed-service responsibilities.
- Explain the Shared Responsibility Model.
- Identify provider-managed security tasks.
- Identify customer security responsibilities.
- Evaluate cloud misconfiguration risks.
- Recommend appropriate security controls.

---

# 🎯 Goals

1. Differentiate between on-premises server responsibilities and managed-service responsibilities.
2. Explain the Shared Responsibility Model in cloud environments.
3. Identify security tasks handled by the cloud provider.
4. Identify customer responsibilities such as IAM, MFA, firewall rules, VM patching where applicable, and credential hygiene.
5. Evaluate how cloud misconfiguration can still lead to compromise.

---

# 💬 Role Play

## 🗣️ Jennifer

**If you migrate your SQL Server to a managed cloud service, what security responsibilities disappear — and which ones are still completely yours?**

## 👨‍💻 Venkat Nishit

When migrating SQL Server to a managed cloud service, physical infrastructure responsibilities such as data-center security, hardware maintenance, physical networking, and underlying infrastructure management move to the cloud provider.

However, responsibilities such as **user access, IAM, MFA, credentials, data protection, service configuration, network rules, and application security remain with us**.

So, the cloud provider secures the **underlying infrastructure**, while we remain responsible for **how the service is configured, accessed, and used**.

---

## 🗣️ Jennifer

**Exactly, you've nailed it! The cloud provider takes care of the heavy lifting when it comes to the physical and infrastructure layers. But all those elements tied to access, data, and configuration — that's still completely on you. It's like they handle the foundation, but you're still in charge of the locks and what happens inside. Now, have you thought about how misconfigurations in these areas could create risks even in the cloud?**

## 👨‍💻 Venkat Nishit

Misconfigurations can still create serious risks in the cloud. For example, incorrect IAM permissions, weak credentials, missing MFA, overly permissive firewall rules, or publicly exposed data can allow unauthorized access.

So, even though the cloud provider secures the underlying infrastructure, we are still responsible for securely configuring and managing our cloud resources.

---

## 🗣️ Jennifer

**Absolutely, you're spot on! Misconfigurations are one of the top reasons for cloud-related breaches. Even with the provider handling the infrastructure, if something like overly permissive access or exposed data happens, it can totally compromise security. Regular audits, strong IAM policies, and tools like automated security checks can really help mitigate those risks. Anything specific you'd like to explore around managing these responsibilities?**

## 👨‍💻 Venkat Nishit

I’d focus on **regular security audits, strong IAM policies, least-privilege access, MFA, and automated security checks** to detect and prevent misconfigurations.

I’d also continuously monitor cloud resources and review configurations to ensure our security responsibilities are being properly managed.

---

## 🗣️ Jennifer

**That's a solid approach! Regular audits combined with least-privilege access and MFA really strengthen your defenses. Automated checks and continuous monitoring are like your safety net to catch issues early. With those practices in place, you're setting yourself up for really effective cloud security management. Anything else you want to dive into, or do you feel good about this plan so far?**

## 👨‍💻 Venkat Nishit

Yes, I feel good about the plan. Regular audits, least-privilege access, MFA, automated security checks, and continuous monitoring will help us identify and reduce security risks while maintaining strong control over our cloud environment.

---

## 🗣️ Jennifer — Closing

**That's fantastic to hear! You've got a really robust mindset for tackling cloud security. With this plan in place, you're well on your way to maintaining a secure and well-managed cloud environment. If you need more insights down the road, just let me know. Great work today!**

---

# 🔐 Responsibility Summary

| Security Area | On-Premises | Managed Cloud Service |
|---|---|---|
| Physical data center | Customer | Cloud provider |
| Physical servers | Customer | Cloud provider |
| Hardware maintenance | Customer | Cloud provider |
| Physical networking | Customer | Cloud provider |
| Underlying infrastructure | Customer | Cloud provider |
| User identities | Customer | Customer |
| IAM / permissions | Customer | Customer |
| MFA | Customer | Customer |
| Credentials | Customer | Customer |
| Data protection | Customer | Customer |
| Service configuration | Customer | Customer |
| Network access rules | Customer | Customer |
| Application security | Customer | Customer |
| Monitoring | Customer | Shared / Customer |
| Patching | More customer responsibility | Depends on the service |

---

# ⚠️ Key Cloud Security Risks

Even when infrastructure is managed by the provider, customers can introduce security risks through:

- Incorrect IAM permissions
- Weak or compromised credentials
- Missing MFA
- Excessive privileges
- Overly permissive firewall rules
- Publicly exposed resources or data
- Incorrect service configuration
- Insufficient logging and monitoring

---

# 🛡️ Security Controls

Recommended controls include:

- 🔐 Least-privilege IAM
- 🔑 Multi-factor authentication
- 📋 Regular security audits
- ⚙️ Automated configuration and security checks
- 📊 Continuous monitoring
- 🔎 Regular access reviews
- 📝 Logging and alerting
- 🛡️ Strong network controls

---

# 🧠 Key Takeaways

- Cloud migration **changes** security responsibilities; it does not eliminate them.
- The cloud provider handles more of the **physical and infrastructure layers**.
- The customer remains responsible for **access, identities, data, and configuration**.
- Misconfiguration can still result in serious cloud security incidents.
- **Least privilege, MFA, audits, automated checks, and continuous monitoring** are important customer-side controls.
- The **Shared Responsibility Model** must always be considered when evaluating cloud security.

---

# 🏁 Final Assessment

> **The cloud provider secures the underlying infrastructure, while the customer remains responsible for securely configuring, accessing, and using the managed service.**

A managed cloud service can reduce operational and physical-security responsibilities, but **secure cloud adoption still requires active customer responsibility**.

---

**Role Play 4 | Servers and Managed Services**
