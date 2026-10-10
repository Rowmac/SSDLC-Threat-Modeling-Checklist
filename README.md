# SSDLC-Threat-Modeling-Checklist
An Excel-based SSDLC Threat Modeling Checklist for identifying, assessing, prioritizing, and mitigating application security threats using STRIDE, risk scoring, and structured threat tracking.


# SSDLC Threat Modeling Checklist

A practical, Excel-based threat modeling toolkit designed to help software developers, application security engineers, architects, and DevSecOps teams identify and manage security threats throughout the **Secure Software Development Life Cycle (SSDLC)**.

The toolkit provides a structured approach to threat identification, risk assessment, security control planning, mitigation tracking, and security review.

## Key Features

- **75 Threat Modeling Checklist Controls** covering eight key areas of the SSDLC.
- **STRIDE Threat Identification** to assess Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, and Elevation of Privilege.
- **Threat Register** to document threat scenarios, affected assets, attack vectors, existing controls, and mitigation plans.
- **Risk Scoring** using likelihood and impact ratings to calculate inherent risk.
- **Mitigation Tracking** to assign control owners, document evidence, and follow up on security gaps.
- **Assessment Status Tracking** with Pass Mark, status, risk priority, evidence, and follow-up fields.
- **Summary Dashboard** to review assessment progress and summarize results by control area.
- **Usage Guidance** for conducting threat modeling and reviewing security risks.

## Workbook Structure

| Worksheet | Purpose |
|---|---|
| Summary | Displays assessment counts, progress, and threat statistics. |
| Threat Modeling Checklist | Contains 75 threat modeling requirements with assessment fields. |
| Threat Register | Records threat scenarios, risk ratings, treatment plans, and residual risk. |
| Guidance | Explains the assessment workflow, risk scoring, and review process. |

## SSDLC Coverage

The checklist covers the following areas:

1. Initiation and Scope
2. Architecture and System Decomposition
3. Assets, Data and Security Objectives
4. Threat Identification
5. Risk Analysis and Prioritization
6. Mitigation and Security Requirements
7. Verification and Validation
8. Governance, Release and Maintenance

## Threat Modeling Methodology

The checklist incorporates **STRIDE** as a threat-identification approach.

| Threat Category | Description |
|---|---|
| Spoofing | Impersonation of users, services, or systems. |
| Tampering | Unauthorized modification of data, messages, configurations, or software. |
| Repudiation | Denial of actions where adequate evidence or auditability is absent. |
| Information Disclosure | Unauthorized exposure of sensitive information. |
| Denial of Service | Disruption of application availability or resource exhaustion. |
| Elevation of Privilege | Obtaining permissions beyond those authorized. |

Privacy, supply-chain, cloud-specific, and application-specific threats should also be considered where applicable.

## Risk Assessment

The workbook provides a starter risk-scoring model based on:

**Inherent Risk Score = Likelihood × Impact**

Both likelihood and impact are rated on a scale of 1–5.

| Score | Default Rating |
|---:|---|
| 1–5 | Low |
| 6–14 | Medium |
| 15–19 | High |
| 20–25 | Critical |

These are default guidance bands. Organizations should align them with their approved risk assessment methodology and risk acceptance criteria.

## How to Use

1. Download the Excel workbook from this repository.
2. Record the application details, version, facilitator, and review date.
3. Review the checklist during architecture and design activities.
4. Document components, data flows, trust boundaries, assets, and security objectives.
5. Identify relevant threats using STRIDE and other applicable threat scenarios.
6. Record individual threats in the Threat Register.
7. Assess likelihood and impact, identify existing controls, and define mitigation actions.
8. Assign owners and record supporting evidence.
9. Verify mitigation effectiveness through appropriate security testing.
10. Document unresolved risks, obtain authorized risk acceptance where applicable, and revisit the model when significant changes occur.

## Intended Audience

- Software developers and engineering teams
- Application Security (AppSec) engineers
- Security architects
- DevSecOps teams
- Penetration testers and security consultants
- Product owners and technical project managers
- Cybersecurity governance and assurance teams

## Recommended SSDLC Integration

Use this checklist during:

- Requirements and security planning
- Architecture and design reviews
- Application and API development
- Security testing and remediation
- Pre-release security reviews
- Significant application changes and periodic reassessments

Threat modeling should be integrated early in the design process and updated when architecture, data flows, dependencies, trust boundaries, or application exposure materially change.

## Security Verification

Threat modeling complements, but does not replace, security testing. Depending on application risk, verification activities may include:

- Static Application Security Testing (SAST)
- Dynamic Application Security Testing (DAST)
- Software Composition Analysis (SCA)
- Infrastructure and configuration security reviews
- Manual secure code reviews
- Penetration testing

## References

- [OWASP Threat Modeling](https://owasp.org/www-community/Threat_Modeling)
- [OWASP Software Assurance Maturity Model (SAMM)](https://owaspsamm.org/)
- [Microsoft Security Development Lifecycle](https://www.microsoft.com/en-us/securityengineering/sdl)
- [NIST Secure Software Development Framework (SP 800-218)](https://csrc.nist.gov/pubs/sp/800/218/final)

## Disclaimer

This project is intended as a practical security assessment aid. The checklist should be tailored to the application's architecture, technology stack, threat landscape, business requirements, and organizational risk criteria. Completing the checklist does not independently establish regulatory compliance or guarantee that an application is secure.

## Contributions

Suggestions, improvements, and contributions that strengthen threat modeling practices and application security are welcome. Please document proposed changes clearly and provide supporting rationale where appropriate.
