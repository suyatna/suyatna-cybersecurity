# Botium Toys: Internal security audit case study

# Table of contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Botium Toys: Scope, goals, and risk assessment report](#botiumtoys)
4. [Control categories](#controlcategories)
5. [Controls and compliance checklist](#controlandcompliance)
6. [Conclusion](#conclusion)

# I. Introduction <a name="introduction">

The audit evaluates Botium Toys’ cybersecurity program and examines how existing business practices align with industry standards and best practices. The assessment focuses on identifying high-risk vulnerabilities, providing mitigation recommendations, and defining an overall strategy to improve the organization’s security posture. Audit findings are documented clearly, supported by remediation plans, and structured to enable effective communication with stakeholders.

# II. Scenario <a name="scenario">

The audit evaluates Botium Toys’ cybersecurity program and examines how existing business practices align with industry standards and best practices. The assessment focuses on identifying high-risk vulnerabilities, providing mitigation recommendations, and defining an overall strategy to improve the organization’s security posture. Audit findings are documented clearly, supported by remediation plans, and structured to enable effective communication with stakeholders.

# III. Botium Toys: Scope, goals, and risk assessment report <a name="botiumtoys">

## 3.1. Scope and goals of the audit

### a. Scope

The scope of this audit covers the entire security program at Botium Toys. The assessment includes all assets managed by the IT department, encompassing systems, devices, data, and internal processes related to security control implementation and compliance with applicable standards.

The audit evaluates not only the technologies in use, but also asset management practices, access control mechanisms, and the consistency of security control application across daily operations.

### b. Goals

The primary goal of this audit is to evaluate the current security posture and identify gaps between existing practices and industry standards and best practices. The assessment focuses on reviewing existing assets and completing control and compliance checklists to determine which security measures should be implemented to improve Botium Toys’ overall security posture.

## 3.2. Current assets

Assets managed by the IT department at Botium Toys include:
- On-premises equipment supporting office operations
- Employee devices such as desktops, laptops, smartphones, remote workstations, and supporting peripherals
- Retail products sold through physical stores and online platforms, including warehouse storage
- Business systems and services, including accounting, telecommunications, databases, security systems, e-commerce platforms, and inventory management systems
- Internet access and internal network infrastructure

## 3.3. Risk assessment

### a. Risk description

Asset management at Botium Toys has not been implemented optimally. Existing security controls are limited and not fully aligned with national and international security regulations and standards. This situation exposes the organization to significant security risks, particularly related to sensitive data protection and business continuity.

### b. Control best practices

The recommended approach aligns with the Identify function of the NIST Cybersecurity Framework. Botium Toys should allocate resources to identify and classify all existing assets. This process provides a foundation for understanding risk levels, prioritizing protection efforts, and evaluating the business impact of potential asset loss.

### c. Risk score

The overall risk score is 8 out of 10, indicating a high level of risk. This score reflects limited security controls and low adherence to compliance requirements and security best practices.

### d. Additional risk considerations

The potential impact of asset loss is considered moderate due to the lack of clarity regarding which assets are most critical to operations. However, the likelihood of asset compromise and regulatory penalties is high, as security controls and data protection mechanisms are insufficient.

Specific findings include:
- All employees have broad access to internal data, including potential access to payment data and customer PII/SPII
- Encryption has not been implemented to protect credit card data processed and stored within internal systems
- Principles of least privilege and separation of duties have not been applied
- A firewall is implemented and configured with appropriate security rules
- Antivirus software is installed and actively monitored
- An Intrusion Detection System (IDS) has not been implemented
- Disaster recovery plans and data backup mechanisms are not currently in place
- Data breach notification procedures for EU customers comply with the 72-hour requirement
- A password policy exists but does not meet modern complexity standards
- A centralized password management system has not been implemented

# IV. Control categories <a name="controlcategories">

## 4.1. Control categories
 
Cybersecurity controls are grouped into three primary categories based on their function and area of protection within an organization. This classification helps ensure that human, technological, and physical aspects of security are addressed through a defense-in-depth approach.

The control categories used in the Botium Toys audit include:
- Administrative / managerial controls
- Technical controls
- Physical / operational controls

Each control is also classified by type to describe its role in preventing, detecting, responding to, or discouraging security incidents.

## 4.2. Control types
The control types referenced in this audit include:
- Preventative
- Corrective
- Detective
- Deterrent

These control types work together to protect organizational assets through layered security.

### a. Administrative / managerial controls
Administrative controls focus on the human element of cybersecurity. These controls include policies, procedures, and internal rules that define how data is managed and how employee responsibilities are assigned in relation to protecting the organization.

Administrative controls are typically policy-driven, but their effectiveness often relies on the support of technical and physical controls during implementation.

|Control name                 |Control types  |Control purpose                                                                                            |
|-----------------------------|---------------|-----------------------------------------------------------------------------------------------------------|
|Least privilege              |Preventative   |Reduce risk and overall impact of malicious insiders or compromised accounts                               |
|Disaster recovery plans      |Corrective     |Provide business continuity following a security incident                                                  |
|Password policies            |Preventative   |Reduce the likelihood of account compromise through brute force or dictionary attacks                      |
|Access control policies      |Preventative   |Strengthen confidentiality and integrity by defining access and modification rights                        |
|Account management policies  |Preventative   |Manage account lifecycles, reduce attack surface, and limit risks from default or former employee accounts |
|Account management policies  |Preventative   |Reduce the risk of abuse by separating critical responsibilities across roles                              |

### b. Technical controls
Technical controls consist of technology-based solutions used to protect systems, networks, and data from digital threats. These controls play a direct role in preventing, detecting, and responding to security incidents.

The implementation of technical controls enables organizations to achieve security objectives in a consistent and measurable manner.

|Control name                                     |Control types  |Control purpose                                                            |
|-------------------------------------------------|---------------|---------------------------------------------------------------------------|
|Firewall                                         |Preventative   |Filter unwanted or malicious traffic entering the network                  |
|IDS / IPS                                        |Detective      |Detect and prevent anomalous traffic based on defined rules or signatures  |
|Encryption                                       |Deterrent      |Provide confidentiality for sensitive information                          |
|Backups                                          |Corrective     |Restore systems and data after an incident                                 |
|Password management                              |Preventative   |Reduce password fatigue and improve policy compliance                      |
|Antivirus (AV) software                          |Corrective     |Detect and isolate known threats                                           |
|Manual monitoring, maintenance, and intervention |Preventative   |Identify and manage risks in legacy systems that lack automated updates    |

### c. Physical / operational controls
Physical controls are used to restrict unauthorized physical access to organizational assets. These controls protect facilities, infrastructure, and inventory from non-digital threats.

Physical security serves as a critical layer in safeguarding IT assets and supporting business operations.

|Control name                                     |Control types            |Control purpose                                                                   |
|-------------------------------------------------|-------------------------|----------------------------------------------------------------------------------|
|Time-controlled safe                             |Deterrent                |Reduce attack surface and limit the impact of physical threat                     |
|Adequate lighting                                |Deterrent                |Deter threats by eliminating concealed areas                                      |
|Closed-circuit television (CCTV)                 |Preventative, detective  |Deter incidents and provide evidence after events occur                           |
|Locking cabinets (network equipment)             |Preventative             |Prevent unauthorized physical access to network infrastructure                    |
|Alarm service provider signage                   |Deterrent                |Discourage attacks by increasing perceived risk                                   |
|Locks                                            |Preventative, deterrent  |Prevent and deter unauthorized access to physical assets                          |
|Fire detection and prevention systems            |Detective, preventative  |Detect fires and prevent damage to physical assets such as inventory and servers  |
