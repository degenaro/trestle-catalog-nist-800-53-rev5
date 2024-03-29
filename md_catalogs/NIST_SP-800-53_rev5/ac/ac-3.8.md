---
x-trestle-set-params:
  ac-03.08_odp:
    values:
x-trestle-global:
  sort-id: ac-03.08
---

# ac-3.8 - \[Access Control\] Revocation of Access Authorizations

## Control Statement

Enforce the revocation of access authorizations resulting from changes to the security attributes of subjects and objects based on {{ insert: param, ac-03.08_odp }}.

## Control Assessment Objective

- \[AC-03(08)[01]\] revocation of access authorizations is enforced, resulting from changes to the security attributes of subjects based on {{ insert: param, ac-03.08_odp }};

- \[AC-03(08)[02]\] revocation of access authorizations is enforced resulting from changes to the security attributes of objects based on {{ insert: param, ac-03.08_odp }}.

## Control guidance

Revocation of access rules may differ based on the types of access revoked. For example, if a subject (i.e., user or process acting on behalf of a user) is removed from a group, access may not be revoked until the next time the object is opened or the next time the subject attempts to access the object. Revocation based on changes to security labels may take effect immediately. Organizations provide alternative approaches on how to make revocations immediate if systems cannot provide such capability and immediate revocation is necessary.
