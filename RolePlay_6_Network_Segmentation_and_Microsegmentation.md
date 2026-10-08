# WATCHTOWER --- Role Play 6: Network Segmentation and Microsegmentation

## Scenario

You are a Security Architect reviewing your company's network design.

-   Web servers in one VLAN.
-   App servers in another VLAN.
-   Database servers in a third VLAN.
-   A perimeter firewall controls traffic between VLANs.

A penetration test revealed that once a web server was compromised, the
attacker could freely communicate with other web servers in the same
VLAN.

## Roles

### Jennifer --- Network Security Strategist

Jennifer is a network security strategist with deep experience in zero
trust and lateral movement prevention.

> "Assume breach. Design for containment."

### Venkat Nishit --- Security Architect

Venkat reviews the network design, identifies segmentation weaknesses,
and recommends controls that reduce lateral movement.

## Goals

1.  Explain traditional VLAN-based segmentation.
2.  Identify Layer 2 segmentation limitations.
3.  Describe microsegmentation at the workload or virtual network
    interface level.
4.  Compare centralized and distributed firewall enforcement.
5.  Evaluate how microsegmentation reduces lateral movement.

## Role Play Conversation

### Jennifer

> If two compromised servers are in the same VLAN, why might your
> firewall never even see that traffic?

### Venkat Nishit

> Because traffic between two servers in the same VLAN is switched
> directly at Layer 2, it may never traverse the perimeter firewall. The
> firewall typically filters traffic between different network segments,
> so it cannot inspect or block lateral traffic within the same VLAN.
> This is a key limitation of traditional VLAN-based segmentation.

------------------------------------------------------------------------

### Jennifer

> Exactly! Traffic within the same VLAN is handled by the switch at
> Layer 2, so it bypasses the firewall entirely. That's why attackers
> can move laterally within the VLAN without being stopped. So, what
> strategies would you consider to address this limitation?

### Venkat Nishit

> I would address this by implementing microsegmentation and enforcing
> security policies at the individual workload or virtual network
> interface level. We can define rules that allow only required
> communication between specific servers and block unnecessary east-west
> traffic.
>
> I would also use host-based or distributed firewalls, network access
> control lists, and least-privilege rules to restrict communication
> within the VLAN. This would reduce the attacker's ability to move
> laterally even if one server is compromised.

------------------------------------------------------------------------

### Jennifer

> That's a fantastic approach! Microsegmentation really helps limit
> lateral movement by enforcing granular policies, and least-privilege
> rules are a great way to minimize unnecessary access. Adding
> host-based or distributed firewalls strengthens your defenses even
> further. Do you foresee any challenges in implementing
> microsegmentation in your current environment?

### Venkat Nishit

> The main challenges would be policy complexity, visibility, and
> operational overhead. We would need to understand application
> dependencies and define granular rules without accidentally blocking
> legitimate traffic.
>
> There may also be compatibility issues with legacy systems and
> additional monitoring and management requirements. I would address
> these by starting with a small set of critical workloads, mapping
> their communication patterns, testing policies in a controlled
> environment, and gradually expanding microsegmentation. This approach
> reduces disruption while improving security step by step.

------------------------------------------------------------------------

### Jennifer

> You've really thought this through! Starting small and mapping
> dependencies is such a smart move---it reduces the risk of breaking
> things while giving you better visibility. Gradual implementation is
> key to managing complexity and minimizing operational strain. How
> would you measure the success of your microsegmentation rollout?

### Venkat Nishit

> I would measure success using both security and operational metrics.
>
> Key metrics would include a reduction in unauthorized east-west
> traffic, fewer successful lateral-movement paths, the percentage of
> workloads covered by microsegmentation policies, and the number of
> unnecessary network connections blocked.
>
> I would also monitor application availability, policy violations,
> false positives, and performance impact to ensure security
> improvements are not disrupting legitimate business traffic. Regular
> reviews and penetration testing would help validate that the
> segmentation is actually reducing the blast radius after a compromise.

------------------------------------------------------------------------

### Jennifer

> That's a solid and well-rounded way to measure success! Tracking both
> security and operational metrics ensures you're improving protection
> without hurting functionality. Regular reviews and penetration tests
> are perfect for keeping the policies effective over time. I'd say
> you've got a strong handle on this. Anything else you'd like to tackle
> about segmentation or microsegmentation before we wrap up?

### Venkat Nishit

> Before we wrap up, I'd also consider continuous monitoring and policy
> optimization. As the environment changes, new workloads and
> dependencies may appear, so segmentation policies should be reviewed
> and updated regularly.
>
> I'd also ensure that the team has clear documentation, ownership, and
> incident-response procedures for segmentation-related events. This
> keeps microsegmentation effective and manageable as the network
> evolves.

------------------------------------------------------------------------

### Jennifer --- Closing Statement

> Absolutely! Continuous monitoring and regular policy updates are
> essential to keeping microsegmentation aligned with a dynamic
> environment. Clear documentation and ownership make a huge difference
> in maintaining effectiveness and ensuring everyone knows their role in
> incident response. You've really nailed the key considerations here.
> Great job tackling such an important topic!

## Technical Summary

  -----------------------------------------------------------------------
  Concept                             Key Point
  ----------------------------------- -----------------------------------
  VLAN segmentation                   Provides logical network
                                      separation.

  Layer 2 traffic                     Same-VLAN traffic can bypass a
                                      perimeter firewall.

  Lateral movement                    Attackers may move between systems
                                      within the same segment.

  Microsegmentation                   Applies granular policies at
                                      workload or virtual interface
                                      level.

  Distributed firewall                Enforces controls closer to
                                      workloads.

  Least privilege                     Allows only required
                                      workload-to-workload communication.

  Blast radius                        Microsegmentation limits attacker
                                      movement after compromise.
  -----------------------------------------------------------------------

## Recommended Implementation

1.  Discover workloads and application dependencies.
2.  Prioritize critical workloads.
3.  Define least-privilege communication policies.
4.  Test policies in a controlled environment.
5.  Deploy gradually.
6.  Monitor traffic, violations, availability, and performance.
7.  Continuously optimize policies.
8.  Validate through security reviews and penetration testing.

## Key Takeaway

> Assume breach. Design for containment.

Traditional VLAN segmentation does not automatically prevent lateral
movement within the same Layer 2 segment. Combining VLANs with
microsegmentation, distributed enforcement, least privilege, continuous
monitoring, and regular validation reduces the blast radius of a
compromise.

**Role Play 6 \| Network Segmentation and Microsegmentation**
