# ISO 26262: Functional Safety Standard for Modern Road Vehicles: Theory, Techniques, Testing and Tools


An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about ISO 26262: Functional Safety  in Cybersecurity.
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources.


## `Table of Contents`
   - [1 - Functional Safety Introduction](#)
      - [What is Functional Safety](#)


## 1 - Functional Safety Introduction
### `1.1 - What is Functional Safety?`

Safety can be defined by referring to two existing safety standards:
- **IEC 61508 (International Electrotechnical Commission (IEC), a functional safety standard for the general electronics market developed by the IEC.**
  - IEC 61508 Definition:
> Safety is the freedom from unacceptable risk of physical injury or of damage to the health of people, either directly, or indirectly as a result of damage to property or to the
environment.
> Functional Safety is part of the overall safety that depends on a system or equipment operating correctly in response to its inputs.


- **ISO 26262 (IEC), a functional safety standard for automobiles from ISO. It has rapidly gaining acceptance as the guideline for the automotive engineer since its release.***
   - ISO 26262 Definition:
> Absence of unacceptable risk due to hazards caused by mal-functional behavior of electrical and/or electronic systems and the interactions of these systems.



### `1.2 - Functional Safety Basic Concepts`
- All systems will have some inherent, quantifiable failure rate. It is not possible to develop a system with zero failure rate.
- For each application, there is some tolerable failure rate which does not lead to unacceptable risk.
- Acceptable failure rates vary per application, based on the potential for direct or indirect physical injury in the event of system malfunction.
- The hazards and risks of applications can be analyzed and assigned categories based on the level of acceptable risk. These categories are known as Safety Integrity Levels, or SILs.

### `1.3 - Terms & Definitions`

#### Fault
> Operational issue in a system which may lead to a failure

#### Failure
> Result of a fault which leads to an inability to execute safety critical functionality

Fault Tolerance
> Ability to continue safe operation after a fault

#### Fail Safe System:
> System where a fault which may lead to failures is detected and the system is put into a safe state such that faults may not propagate to other systems

#### Fail Functional/Operational System
> System where a fault which may lead to failures is detected and the system can continue operation without loss of safety function

#### Reliability
> Ability to execute operations in system without failure (generally independent of consideration for a safety function)

#### Availability
> Amount of time in which a safety function is available divided by total system operation time. Systems with high reliability and fail functional systems tend to have higher availability than fail safe systems

#### Security
> Ability to detect, resist, or prevent tampering with product functionality

#### Dependability
> Availability + Reliability + Safety + Security + Maintainability


### 1.4 - Evolution of Functional Safety

4 specific steps in the evolution of functional safety:

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/evolution_functional.png?raw=true" alt="Sublime's custom image"/>
</p>

- Fail-safe: the system goes into safe mode when a failure occurs.
- Fail-silent: the system recognizes that it is receiving the wrong information due to a fault, so the ongoing operation moves to degraded mode.
- Fail-operational: sometimes also referred to as fault-tolerant, a failure in one component does not stop the whole system from working correctly, the system reconfigures itself to compensate for the fault.
- High-dependability: this is advanced failure prediction.

### `1.5 - Safety Failures and their causes` 
Failures in a functional safety system can be broadly classified into two categories:
Systematic and Random failures
• Systematic Failures
− Result from a failure in design or manufacturing
− Often a result of failure to follow best practices
− Occurrence of systematic failures can be reduced through continual and rigorous process
improvement and robust analysis of any new technology
• Random Failures
− Result from random defects or soft errors inherent to process or usage condition
− Rate of random faults cannot generally be reduced; focus must be on the detection and handling
of random faults to prevent application failure
