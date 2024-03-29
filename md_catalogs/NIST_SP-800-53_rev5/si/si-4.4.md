---
x-trestle-set-params:
  si-4.4_prm_1:
    values:
  si-4.4_prm_2:
    values:
  si-04.04_odp.01:
    values:
  si-04.04_odp.02:
    values:
  si-04.04_odp.03:
    values:
  si-04.04_odp.04:
    values:
x-trestle-global:
  sort-id: si-04.04
---

# si-4.4 - \[System and Information Integrity\] Inbound and Outbound Communications Traffic

## Control Statement

- \[(a)\] Determine criteria for unusual or unauthorized activities or conditions for inbound and outbound communications traffic;

- \[(b)\] Monitor inbound and outbound communications traffic {{ insert: param, si-4.4_prm_1 }} for {{ insert: param, si-4.4_prm_2 }}.

## Control Assessment Objective

- \[SI-04(04)(a)\]

  - \[SI-04(04)(a)[01]\] criteria for unusual or unauthorized activities or conditions for inbound communications traffic are defined;
  - \[SI-04(04)(a)[02]\] criteria for unusual or unauthorized activities or conditions for outbound communications traffic are defined;

- \[SI-04(04)(b)\]

  - \[SI-04(04)(b)[01]\] inbound communications traffic is monitored {{ insert: param, si-04.04_odp.01 }} for {{ insert: param, si-04.04_odp.02 }};
  - \[SI-04(04)(b)[02]\] outbound communications traffic is monitored {{ insert: param, si-04.04_odp.03 }} for {{ insert: param, si-04.04_odp.04 }}.

## Control guidance

Unusual or unauthorized activities or conditions related to system inbound and outbound communications traffic includes internal traffic that indicates the presence of malicious code or unauthorized use of legitimate code or credentials within organizational systems or propagating among system components, signaling to external systems, and the unauthorized exporting of information. Evidence of malicious code or unauthorized use of legitimate code or credentials is used to identify potentially compromised systems or system components.
