# ISO 26262: Functional Safety Standard for Modern Road Vehicles: Theory, Techniques, Testing and Tools


An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about ISO 26262: Functional Safety Standard for Modern Road Vehicles in Cybersecurity.
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources.


## `Table of Contents`
   - [1 - Introduction to ISO 26262](#)
      - [1.1 - Discover ISO 26262](#)
      - [1.2 - What is Functional Safety](#)
   - [2 - ISO 26262 Safety Integrity Levels](#)
     - [2.1 - Determining ISO 26262 ASIL Leve](#)


## 1 - Introduction to ISO 26262
ISO 26262 is a standard for implementing functional safety measures for electric systems in an automotive vehicle. The first version of ISO 26262 was released in 2011. This version only covered functional safety for passenger cars. 
> A later edition of the standard, released in 2018, extended the scope to include all road vehicles except for mopeds.

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/iso26262-1.png?raw=true" alt="Sublime's custom image"/>
</p>

The **ISO 26262 series of standards** is the adaptation of **IEC 61508 series of standards** to address the sector specific needs of electrical and/or electronic (E/E) systems within road vehicles. 
This adaptation applies to all activities during the safety lifecycle of safety-related systems comprised of electrical, electronic and software components.
> Safety is one of the key issues in the development of road vehicles. Development and integration of automotive functionalities strengthen the need for functional safety and the need to provide evidence that functional safety objectives are satisfied. With the trend of increasing technological complexity, software content and mechatronic implementation, there are increasing risks from systematic failures and random hardware failures, these being considered within the scope of functional safety.

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/iso26262-3.png?raw=true" alt="Sublime's custom image"/>
</p>

- ISO 26262 series of standards includes guidance to mitigate these risks by providing appropriate requirements and processes. To achieve functional safety, the ISO 26262 series of standards:
   - a) provides a reference for the automotive safety lifecycle and supports the tailoring of the activities to be performed during the lifecycle phases, i.e., development, production, operation, service and decommissioning;
   - b) provides an automotive-specific risk-based approach to determine integrity levels [Automotive Safety Integrity Levels (ASILs)]; iTeh STANDARD PREVIEW (standards.iteh.ai)
   -  c) uses ASILs to specify which of the requirements of ISO 26262 are applicable to avoid unreasonable residual risk;
   -  d) provides requirements for functional safety management, design, implementation, verification, validation and confirmation measures; and ISO 26262-1:2018 htps:/standards.iteh.ai/catalog/standards/sist/c1a72b85-fd93-4952-bc1e38aedd5d0742/iso-26262-1-2018
   -  e) provides requirements for relations between customers and suppliers.

### `1.1 - Discover ISO 26262`
Ensure your automotive software meets the highest safety standards by mastering ISO 26262 verification requirements and avoid critical, costly recalls by guaranteeing road-ready reliability.

- ISO 26262 is divided into 12 parts.

  <p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/iso26262-2.png?raw=true" alt="Sublime's custom image"/>
</p>


### `1.2 - What is Functional Safety?`

Safety can be defined by referring to two existing safety standards:
- **IEC 61508 (International Electrotechnical Commission (IEC), a functional safety standard for the general electronics market developed by the IEC.**
  - IEC 61508 Definition:
> Safety is the freedom from unacceptable risk of physical injury or of damage to the health of people, either directly, or indirectly as a result of damage to property or to the
environment.
> Functional Safety is part of the overall safety that depends on a system or equipment operating correctly in response to its inputs.


- **ISO 26262 (IEC), a functional safety standard for automobiles from ISO. It has rapidly gaining acceptance as the guideline for the automotive engineer since its release.***
   - ISO 26262 Definition:
> Absence of unacceptable risk due to hazards caused by mal-functional behavior of electrical and/or electronic systems and the interactions of these systems.


### `1.3 - ISO 26262 Reading recommendation`

  <p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/iso26262-4.png?raw=true" alt="Sublime's custom image"/>
</p>

### `1.4 - Scope of ISO 26262`
  <p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/iso26262-5.png?raw=true" alt="Sublime's custom image"/>
</p>

### `1.5 - Safety Lifecycle`
  <p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/iso26262-6.png?raw=true" alt="Sublime's custom image"/>
</p>

### `1.6 - ISO 26262 Key Differences from IEC 61508`

- ISO 26262 aligns with auto industry use cases and definition of acceptable risk
- IEC 61508 concept of safety function is replaced with ISO 26262 safety goals.
   − Safety function concept was based on the idea of defining a system under control and then “bolting-on” risk reduction measures
   − Safety goal concept requires that risk reduction be part of the initial control system design
- Typical IEC 61508 systems are installed and then validated in place. ISO 26262 systems must be validated before release to market.
- ISO 26262 standard clearly defines work products for each requirement. This makes determination of compliance easier but limits flexibility of development system definition.
- ISO 26262 has hazard and risk analysis, failure rates and metrics adapted for Automotive use cases.

 ## 2 - ISO 26262 Safety Integrity Levels
     
### 2.1 - Determining ISO 26262 ASIL Level

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/iso26262-7.png?raw=true" alt="Sublime's custom image"/>
</p>


### 2.2 Automotive Safety Integrity Level

The Automotive Safety Integrity Level (ASIL) is a classification system used in ISO 26262. Each component of an automotive system is assigned an ASIL based on the level of risk should the component fail, and this determines the verification activities required to demonstrate functional safety for the component. A risk can be assigned one of five ASIL ratings:

- A (lowest integrity) to D (highest integrity), which define the level of risk in the event of failure. Failure at ASIL D could be potential for loss of life and require stricter compliance requirements compared to ASIL A.
- QM (Quality Management), which assumes that the risk will be mitigated sufficiently by Quality Assurance activities.

The ASIL rating is calculated based on the following factors (see Table 1):

- **Severity** of injuries afflicted to the passengers
- **Probability** of exposure
- **Controllability** of the hazard (probability that the passenger will avoid the harm)

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/iso26262-8.png?raw=true" alt="Sublime's custom image"/>
</p>



<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-iso-26262/blob/main/img/iso26262-9.png?raw=true" alt="Sublime's custom image"/>
</p>

## `License`
MIT License & [cc](https://creativecommons.org/licenses/by/4.0/) license

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

To the extent possible under law, [Paul Veillard](https://github.com/paulveillard/) has waived all copyright and related or neighboring rights to this work.
