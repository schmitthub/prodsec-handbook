# Threat Modeling

``` mermaid
---
title: Threat Model Process
---
graph LR
    B[1. Scope your work]
    C[2. Determine Threats]
    D[3. Determine Countermeasures and Mitigation]
    E[4. Assess your work]

    B --> B1[Gain understanding of the application]
    B1 --> B1a[Draw diagrams e.g. DFDs]
    B1 --> B1b[Identify entry points]
    B1 --> B1c[Identify assets]
    B1 --> B1d[Identify trust levels]
    B1 --> B1e[Read/create user story or abuser story]
    B --> B2[Use DFDs to show paths and boundaries]
    B --> B3[Decompose app or model per story]

    C --> C1[Use threat categorization e.g. STRIDE]
    C --> C2[Leverage DFDs for threat targets]
    C --> C3[Organize threats with trees and lists]
    C --> C4[Use and abuse cases]

    D --> D1[Identify countermeasures using mapping lists]
    D --> D2[Prioritize based on likelihood damage cost]
    D --> D3[Evaluate threats business impact]
    D3 --> D3a[Accept risk]
    D3 --> D3b[Eliminate components]
    D3 --> D3c[Mitigate with controls]
    D3 --> D3d[Transfer risk]

    E --> E1[Check for records]
    E1 --> E1a[Diagram]
    E1 --> E1b[Threats list]
    E1 --> E1c[Control list]
```

## Tools

- **AWS Threat Composer**
      - [AWS Threat Composer Github](https://github.com/awslabs/threat-composer)
      - [AWS Threat Compose Site](https://awslabs.github.io/threat-composer/workspaces/default/dashboard)

## Reading

- [OWASP Threat Modeling Process](https://owasp.org/www-community/Threat_Modeling_Process)
