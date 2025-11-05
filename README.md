# Linux IAM & Hardening — Submission Package
**Student:** Abhay Raj  
**Course:** B.Tech | **Branch:** CSE (Core)  
**Instructor:** Anshul Kaundal  
**Hostname (lab):** ubuntu-lab  
**Date:** 05 Nov 2025

## Contents
- README.md (this file)
- Linux_IAM_Final_Project_Abhay_Raj.pdf
- scripts/create_users.sh
- scripts/fix_misconfigs.sh
- examples/sudoers_example
- examples/audit_rules.rules
- evidence/ (filled with before/after outputs & audit snippets)

## How to use
1. Review the PDF and README.
2. Use scripts on a lab VM only (not production). Validate sudoers with `visudo -c`.
3. Place `examples/sudoers_example` into `/etc/sudoers.d/` and validate.
4. Place `examples/audit_rules.rules` into `/etc/audit/rules.d/` then `service auditd restart`.

## Evidence included (Style C: realistic with minor mistakes & corrections)
