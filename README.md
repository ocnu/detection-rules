// README.md
# Detection Rules

MITRE ATT&CK v19-mapped Sigma detection rules for common
adversary TTPs, written by a transitioning CNO operator
with 6 years of offensive cyber operations experience.

## About

These rules were built from direct knowledge of how adversaries
operate — not from a textbook. Each rule maps to a real technique
observed in threat actor playbooks and is designed for deployment
in enterprise SIEM environments via sigma-cli conversion.

## Coverage

| Tactic                | Rules |
|-----------------------|-------|
| Credential Access     | 4     |
| Persistence           | 4     |
| Lateral Movement      | 3     |
| Stealth               | 2     |
| Defense Impairment    | 2     |
| Discovery             | 2     |
| Execution             | 1     |
| Command and Control   | 2     |
| **Total**             | **20**|

## Rule Format

All rules are written in [Sigma](https://github.com/SigmaHQ/sigma)
format, compatible with MITRE ATT&CK v19. Convert to any SIEM
platform using sigma-cli.

## Certifications

- GIAC Certified Incident Handler (GCIH)
- GIAC Penetration Tester (GPEN)
- CompTIA Security+
- AWS Security Specialty (in progress)

## Contact

Portfolio: ohstephen.com