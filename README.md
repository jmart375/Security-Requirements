# Security-Requirements

# Table of Contents
1. [Step 1: Security Categorization](#step-1-security-categorization)
2. [Step 2: Minimum Security Requirements](#step-2-minimum-security-requirements)
3. [Step 3: NIST SP 800-171](#step-3-nist-sp-800-171)
4. [Step 4: Cross Reference](#step-4-cross-reference)
5. [Step 5: Complete Set of Requirements](#step-5-complete-set-of-requirements)
6. [References](#references)

## Step 1: Security Categorization
The characterization of information or an information system is based on an assessment of the potential impact that a loss of confidentiality, integrity, or availability of such information or information system would have on organizational operations, organizational assets, or individuals...

Example: SC information system VPN = {(confidentiality, LOW), (integrity, MODERATE), (availability, LOW)}.
SC contract information = {(confidentiality, MODERATE), (integrity, MODERATE), (availability, LOW)}.
SC administrative information = {(confidentiality, LOW), (integrity, LOW), (availability, LOW)}.
SC acquisition system = {(confidentiality, MODERATE), (integrity, MODERATE), (availability, LOW)}.

## Step 2: Minimum Security Requirements
The Protection Lab will have minimum security requirements to successfully run our business...

## Step 3: NIST SP 800-171
### Purpose and Applicability
This approach provides adequate security and enhances the security posture of the organization.
### Target Audience
The NIST SP 800-171 serves a diverse group of individuals and organizations...

### Security Requirements
The security requirements are organized into fourteen families. Each family contains the requirements related to the general security topic of the family.

#### Access Control
- 3.1.2 TPL will ensure there is limited system access to the types of transactions and functions that authorized users are permitted to execute...
- 3.1.3 TPL will control the flow of systems in accordance with approved authorizations...
- 3.1.4 TPL will confirm that separate the duties of individuals in order to reduce the risk of malicious activity...

#### Awareness and Training
- 3.2.1 TPL will make sure that managers, systems administrators, and users of organizational systems are made aware of the security risks associated with their activities...

#### Configuration Management
- 3.4.1 TPL will also establish and maintain baseline configurations and inventories of organizational systems...

#### Identification and Authentication
- 3.5.1 As a means to identify systems users and processes, TPL will implement common device identifiers...

#### Incident Response
- 3.6.1 TPL will establish a collection of operational incident handling systems that includes preparation, detection, analysis, containment, recovery, and user response activities...

#### Physical Protection
- 3.10.1 TPL will limit physical access to organizational systems, equipment, and the respective operating environments to authorized individuals...

#### Risk Assessment
- 3.11.1 TPL will periodically assess organizational operations such as mission, organizational assets, and individuals...

## Step 4: Cross-Reference
Cross-reference and build a complete set of Security Requirements using an MS Excel spreadsheet with the High-level controls you determined in Table 9-8, NIST controls you determined above, and any specialized controls (HIPAA, SOX, PCI-DSS) required by your organization...

## Step 5: Complete Set of Requirements
### SECURITY CONTROL REQUIREMENT TIPS ON IMPLEMENTING
- Keep security logs immediately available for 90 days...
- Forward security logs to a central Syslog server for auditing purposes and integrity...
- Download and install logstash by elastic...

References:
1. [Minimum information security requirements for systems, applications, and Data](https://safecomputing.umich.edu/information-security-requirements)
2. [Chapter 15: PCI, HIPAA, and SOX -- government regulatory compliance](https://www.smartfile.com/blog/chapter-15-pci-hipaa-and-sox-government-regulatory-compliance)
3. [Security best practices for your windows 10 computer](https://carbidesecure.com/resources/security-best-practices-hardening-windows-10/)
4. [Cyber security](https://commons.lbl.gov/display/cpp/Minimum+Security+Requirements)
5. [Minimum security requirements for Federal Information and Information Systems](https://csrc.nist.gov/publications/detail/fips/200/final)
6. [Release search - NIST risk management framework: CSRC](https://nvd.nist.gov/800-53)
7. [FIPS 199, Standards for Security Categorization Federal Info and Info Sys](https://csrc.nist.gov/publications/detail/fips/199/final)
8. [Protecting controlled unclassified information in nonfederal systems - NIST](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-171r2.pdf)
