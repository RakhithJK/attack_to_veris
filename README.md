[![codecov](https://codecov.io/gh/center-for-threat-informed-defense/attack_to_veris/branch/main/graph/badge.svg?token=0DJ6K1YX6E)](https://codecov.io/gh/center-for-threat-informed-defense/attack_to_veris)

# VERIS Mappings to MITRE ATT&CK®
[Vocabulary for Event Recording and Incident Sharing (VERIS)](http://veriscommunity.net/), provides a common language for describing cybersecurity incidents, including the demographics, metadata, and technical details, in a repeatable manner. As a standard representation, it allows for the analysis of data across a variety of incidents and is used, among other things, to generate the [Verizon Data Breach Investigation Report (DBIR)](https://www.verizon.com/business/resources/reports/dbir/).

While VERIS is comprehensive in describing most aspects of cybersecurity incidents, it is focused on a high-level description of an incident as a whole, and as such does not provide the level of fidelity that [MITRE ATT&CK®](https://attack.mitre.org/) provides in describing the adversary behaviors that were used to carry out an attack at the system level.

This project created a mapping and translation layer between VERIS and ATT&CK that allows ATT&CK to describe the adversary behaviors that were observed in an incident coded in VERIS. This creates the opportunity for a joint analysis of the information that ATT&CK describes well (the behaviors adversaries use to attack systems) alongside the incident demographics and metadata that VERIS describes well.

The resulting mapping between VERIS and ATT&CK will allow cyber defenders to create a fuller and more detailed picture of cyber incidents, including the threat actor, technical behavior, assets targeted, and impact. While VERIS allows for the expression of all these aspects, ATT&CK provides a significant improvement in level of detail, consistency of detail, and comprehensiveness in describing technical behaviors. These improvements can be used to develop better predictions and insights about how we might be attacked in the future by understanding better how and why we were attacked in the past.

| VERIS Framework | Mappings as XLSX (download) | ATT&CK Navigator Layers | STIX Data |
|---|---|---|---|
| [All VERIS 1.3.5 resources](/frameworks/veris/) | [Spreadsheet](https://github.com/center-for-threat-informed-defense/attack_to_veris/raw/main/frameworks/veris/veris-mappings.xlsx) | [Navigator Layers](/frameworks/veris/layers) | [STIX](/frameworks/veris/stix) |

The example below shows the bidirectional mapping of the VERIS Action Hacking Vector's Desktop sharing software to a more granular set of ATT&CK techniques. This granular description of an adversary's behavior allows users to better understand how to detect and mitigate the threat.

<img src="/docs/veris-to-attack.png" width="900px">


## Repository Contents

- [VERIS Mappings](/frameworks/veris/) — contains the VERIS framework mappings to ATT&CK techniques, documentation and resources
- [Use Cases](/docs/use-cases.md) - use cases for VERIS framework mappings to ATT&CK
- [Mapping Methodology](/docs/methodology.md) — a description of the methodology used to create the VERIS mappings to ATT&CK
- [Tooling](/docs/tooling.md) — a set of python tools to support the creation of new mappings and the customization of existing mappings
- [STIX Format](/docs/STIX_format.md) — information regarding the STIX representation of the control frameworks and the mappings to ATT&CK
- [Visualization](/docs/visualization.md) — describes other ways to visualize mappings data
- [Contributing](/CONTRIBUTING.md) — information about how to contribute to this project

## Getting Involved

There are several ways that you can get involved with this project and help advance threat-informed defense. 

Please review the mappings, use them, and tell us what you think. We welcome your review and feedback on the VERIS mappings, our methodology, and resources. 

We are interested developing additional tools and resources to help the community understand and make threat-informed decisions in their risk management programs. Share your ideas and we will consider them as we explore additional research projects.  

## Questions and Feedback
   
Please submit issues for any technical questions/concerns or contact ctid@mitre-engenuity.org directly for more general inquiries.

Also see the guidance for contributors if are you interested in [contributing or simply reporting issues.](/CONTRIBUTING.md)

## Notice
Copyright 2021 MITRE Engenuity. Approved for public release. Document number CT0026

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

This project makes use of MITRE ATT&CK®

[ATT&CK Terms of Use](https://attack.mitre.org/resources/terms-of-use/)
