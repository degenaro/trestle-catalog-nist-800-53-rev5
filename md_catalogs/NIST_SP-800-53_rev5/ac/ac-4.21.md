---
x-trestle-set-params:
  ac-4.21_prm_1:
    values:
  ac-04.21_odp.01:
    values:
  ac-04.21_odp.02:
    values:
  ac-04.21_odp.03:
    values:
x-trestle-global:
  sort-id: ac-04.21
---

# ac-4.21 - \[Access Control\] Physical or Logical Separation of Information Flows

## Control Statement

Separate information flows logically or physically using {{ insert: param, ac-4.21_prm_1 }} to accomplish {{ insert: param, ac-04.21_odp.03 }}.

## Control Assessment Objective

- \[AC-04(21)[01]\] information flows are separated logically using {{ insert: param, ac-04.21_odp.01 }} to accomplish {{ insert: param, ac-04.21_odp.03 }};

- \[AC-04(21)[02]\] information flows are separated physically using {{ insert: param, ac-04.21_odp.02 }} to accomplish {{ insert: param, ac-04.21_odp.03 }}.

## Control guidance

Enforcing the separation of information flows associated with defined types of data can enhance protection by ensuring that information is not commingled while in transit and by enabling flow control by transmission paths that are not otherwise achievable. Types of separable information include inbound and outbound communications traffic, service requests and responses, and information of differing security impact or classification levels.
