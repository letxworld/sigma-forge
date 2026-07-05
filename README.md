## Rules

| Rule | Category | Technique | Severity |
|------|----------|-----------|----------|
| [Brute Force Login](rules/authentication/brute_force_login.yml) + [Correlation](rules/authentication/brute_force_correlation.yml) | Authentication | [T1110](https://attack.mitre.org/techniques/T1110/) | High |
| [Password Spraying](rules/authentication/password_spraying.yml) + [Correlation](rules/authentication/password_spraying_correlation.yml) | Authentication | [T1110.003](https://attack.mitre.org/techniques/T1110/003/) | High |
| [Suspicious PowerShell Encoded Command](rules/windows/suspicious_powershell_encoded.yml) | Windows / Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | High |