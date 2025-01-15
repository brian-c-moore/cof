# Continuous Operations Framework: Core Principles

## Introduction
The Continuous Operations Framework (COF) is a structured set of guidelines, rooted in core DevOps principles, for enabling the continuous delivery of operations services. The COF seeks to be in alignment with other operations management frameworks and serves as an overlay to transform high-level abstract lifecycle principles into actionable, ticket-driven processes.

This framework draws inspiration from the foundational DevOps principles, *The Three Ways*, in order to streamline the flow of operations work and deliver continuous service operations. In DevOps, the unit of work is typically code or a configuration change. The Operations Delivery Pipeline (ODP) manages the continuous stream of day-to-day operations work items, end-to-end through the entire lifecycle, and forms the cornerstone of this framework. While the COF is heavily rooted in DevOps and Lean IT principles, it does not strictly set out to be a “DevOps” or "Lean IT" solution.

In regards to specific operational processes, different frameworks (e.g., ITIL, DevOps, NIST, ISO) have varying levels of guidance on how to structure the flow of work for continuing service operations. This is where the COF fits into the process. The primary goal of this framework is to enable teams to continuously deliver services by efficiently managing work through the entire lifecycle, enabling continuous improvement and feedback, and ensuring alignment with strategic objectives. COF is designed to provide guidelines and suggestions, not rigid rules, to empower teams while aligning with core principles and governing frameworks.

“Management is doing things right; leadership is doing the right things.” – Stephen R. Covey

The Continuous Operations Framework aims to enable operations teams to accomplish both through workflow efficiency and alignment with governing principles.

---

## Overview
The Continuous Operations Framework is a lifecycle-centric approach to managing operations. This is done through a top-down process that ensures the workflow is in alignment with the overall governing strategy. It begins by developing an Operational Delivery Lifecycle that covers the lifecycle of a work item. Then, the lifecycle is laid flat and developed into an Operational Delivery Pipeline, representing the flow of work from left to right. Detailed workflow statuses are developed to gather metrics and provide applicable feedback to the team. Collectively, this process enables the continual delivery and improvement of services.

Managing operations work through the lens of the incident lifecycle represents a subtle but powerful shift. It allows for better visibility into the flow of work by providing additional context, improving identification of bottlenecks and scalability. For example, if tickets spend an unusually long time in a particular phase, it indicates an area that could benefit from process improvements or increased resources. Without visibility into the flow of work, identifying the correct phase becomes far more complex.

Consider the table below representing a few rows of tickets. The first column with the generic status tells you very little about the current state of the work while the second allows for immediate assesment. To get a more accurate status, research would need to be done for each ticket. Contrast with the second column, where that information is readily available. 

| **Generic Status** | **Lifecycle Status**                |
|--------------------|-------------------------------------|
| Open               | Discovery                           |
| Open               | Discovery                           |
| In Progress        | In Progress: Triage                 |
| In Progress        | In Progress: Triage                 |
| In Progress        | In Progress: Triage                 |
| In Progress        | In Progress: Validation             |
| In Progress        | In Progress: Remediation            |
| In Progress        | In Progress: Remediation            |
| Pending            | Pending: Risk Documentation         |
| Pending            | Pending: Vendor Response            |
| Pending            | Pending: Change Approval            |
| Pending            | Pending: Change Approval            |
| Pending            | Pending: Validation                 |
| Pending            | Pending: Validation                 |
| Pending            | Pending: Validation                 |
| Pending            | Pending: Validation                 |
| Pending            | Pending: Validation                 |

The build-up of tickets with a status of “Pending: Validation” indicates a possible bottleneck needing attention, which would otherwise be obscured. For operations team members, this allows them to identify where they can contribute to progress the work. Being able to monitor and report on how work is flowing through the pipeline is what enables actionable feedback to the team at all levels.

**Note** that while the COF is deeply rooted in DevOps principles, a Kanban board is not required to take advantage of this process. A Kanban is a visual representation of the data, but the same information can be represented in a list with sorting. This can simplify implementation.

---

## Key Terms
- **The Continuous Operations Framework (COF):**  
  A structured methodology, rooted in core DevOps principles, for enabling the continuous delivery of operations services. The COF seeks alignment with other operations management frameworks.
  
- **The Operations Delivery Pipeline (ODP):**  
  The operational workflow for a work item end-to-end, as it relates to day-to-day operations. This begins when a work item has been created and reported, and ends when no further actionable work remains.

- **Work Item:**  
  An incident, event, support request, or any unit of work the operations team needs to address, usually delivered in the form of a ticket. The process is primarily aimed at work items that are not resolved in a single response and may need to flow through several stages.

### DevOps Principles: The Three Ways
The Continuous Operations Framework is heavily influenced by DevOps principles, particularly "The Three Ways," described in *The Phoenix Project* and *The DevOps Handbook* by Gene Kim and others. These emphasize:

1. **Flow:** Optimizing the delivery of work from concept to value.  
2. **Feedback:** Creating systems of learning and improvement by enabling feedback loops.  
3. **Continual Learning and Experimentation:** Building a culture of resilience and innovation.

For more details, see *The Phoenix Project* by Gene Kim, Kevin Behr, and George Spafford, and *The DevOps Handbook* by Gene Kim, Patrick Debois, John Willis, and Jez Humble.

---

## Lifecycle Identification and Mapping Flow
The Continuous Operations Framework (COF) begins with developing the Operations Delivery Lifecycle. To ensure alignment, this starts with a review and selection of any applicable governing lifecycles or frameworks in use by the organization.

From the Operations Delivery Lifecycle (ODL), a workflow is established for the lifecycle of a work item, which could be an incident, event, support request, or other unit of work. The intention is to focus on the areas that require input or actions from the operations team only—beginning with incident detection and reporting, ending with resolution.

The COF does not dictate specific workflow stages but derives them from the stages defined by the governing lifecycle. The first step is to analyze the relevant framework and identify the operational slice—where human-driven workflows are necessary. These stages form the basis of the ODP. Some frameworks prescribe stages for certain work items; in such cases, much of the mapping is already defined.

---

## Feedback
Structuring work processes around the lifecycle allows for metrics gathering and detailed status reporting that aligns with each position in the pipeline. For operations teams, this serves as a feedback loop, enabling quick monitoring of work flow and better decision-making.

---

## Continual Learning and Experimentation
The Continuous Operations Framework is flexible enough for customization and experimentation. Through regular feedback, the COF enables continued learning. While it is good practice, the COF doesn’t prescribe specific development or test environments that would allow for a high level of experimentation. Managing the larger operations environment is out of scope.

---

