# ISO 26262: Functional Safety Standard for Modern Road Vehicles: Theory, Techniques, Testing and Tools


An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about ISO/SAE 21434:2021: Road vehicles — Cybersecurity engineering:  in Cybersecurity.
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources.


## `Table of Contents`
   - [Functional Safety Introduction](#)
      - [What is Functional Safety](#)


### `What is Functional Safety?`

- ISO 26262 Definition:
> Absence of unacceptable risk due to hazards caused by mal-functional behavior of electrical and/or electronic systems and the interactions of these systems

- IEC 61508 Definition:
> Safety is the freedom from unacceptable risk of physical injury or of damage to the health of people, either directly, or indirectly as a result of damage to property or to the
environment.
> Functional Safety is part of the overall safety that depends on a system or equipment
operating correctly in response to its inputs.

### Functional Safety Basic Concepts
- All systems will have some inherent, quantifiable failure rate. It is not possible to develop a system with zero failure rate.
- For each application, there is some tolerable failure rate which does not lead to unacceptable risk.
- Acceptable failure rates vary per application, based on the potential for direct or indirect physical injury in the event of system malfunction.
- The hazards and risks of applications can be analyzed and assigned categories based on the level of acceptable risk. These categories are known as Safety Integrity Levels, or SILs.

### Terms & Definitions

#### Fault
− Operational issue in a system which may lead to a failure

#### Failure
− Result of a fault which leads to an inability to execute safety critical functionality
• Fault Tolerance
− Ability to continue safe operation after a fault
• Fail Safe System:
− System where a fault which may lead to failures is detected and the system is put into a safe state such that faults may not
propagate to other systems
• Fail Functional/Operational System
− System where a fault which may lead to failures is detected and the system can continue operation without loss of safety
function
• Reliability
− Ability to execute operations in system without failure (generally independent of consideration for a safety function)
• Availability
− Amount of time in which a safety function is available divided by total system operation time. Systems with high reliability
and fail functional systems tend to have higher availability than fail safe systems
• Security
− Ability to detect, resist, or prevent tampering with product functionality
• Dependability
− Availability + Reliability + Safety + Security + Maintainability
