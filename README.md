# sigma-forge

Custom [Sigma](https://github.com/SigmaHQ/sigma) detection rules for common attack techniques, built and maintained as part of my SOC/detection engineering practice.

## What is Sigma?

Sigma is an open, generic signature format for writing detection rules that can be converted to work with SIEMs like Splunk, Elastic, and Microsoft Sentinel — write once, deploy anywhere.

## Rules

| Rule | Category | Technique | Severity |
|------|----------|-----------|----------|
| [Brute Force Login](rules/authentication/brute_force_login.yml) | Authentication | [T1110](https://attack.mitre.org/techniques/T1110/) | High |

## Structure