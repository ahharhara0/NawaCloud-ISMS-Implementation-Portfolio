# Practical Simulation Exercises

These exercises are fictional learning activities for the NawaCloud case. They are not evidence of controls operating in a real organization. Use synthetic records only; never introduce actual customer, employee, production, or security incident data.

## Exercise 1 — Risk assessment walkthrough

**Scenario:** A developer's account is phished. The account can access the code repository and a build service. A privileged deployment token may be available to a pipeline.

**Learner tasks:** Identify assets and boundaries; describe the event, threat, enabling condition, and consequences; select likelihood and impact with reasons; identify existing safeguards; propose treatment, owner, date, control links, and closure test; describe residual-risk acceptance.

**Facilitator key:** Likely assets are workforce identity, source repository, build pipeline, and production service. Consider unauthorized code change, credential exposure, and customer data impact. Link to identity, privileged access, secure authentication, source-code access, secret protection, change management, logging, and incident response controls. A strong treatment combines phishing-resistant MFA, short-lived scoped credentials, reviewed builds, secret scanning, alerting, and an exercised response. Do not treat cyber insurance or a policy as full risk removal.

## Exercise 2 — Tenant isolation release gate

**Scenario:** A change adds a support export endpoint. In a synthetic test, a user from Tenant A can request a Tenant B record by changing an identifier in the URL.

**Learner tasks:** Decide whether to stop the release; define containment and investigation steps; identify data and tenants potentially affected; create a safe regression test; map treatment to risk and controls; define the evidence needed to close the issue.

**Facilitator key:** Block release, preserve relevant test artifacts, assess whether production exposure occurred, and use synthetic tenant records. Require server-side authorization tests for positive and negative cases, code review, and regression coverage. If production may have been affected, activate incident triage and assess obligations through authorized counsel. Evidence must show the test case, reviewed fix, successful rerun, and approval.

## Exercise 3 — Backup restoration tabletop

**Scenario:** An operator deletes a production database after a compromised administrator session. The last backup is available, but its restoration has not been tested this quarter.

**Learner tasks:** Assign incident and recovery roles; prevent further destructive access; determine the recovery point; restore in an isolated environment; validate tenant separation and integrity; measure RTO/RPO; document customer communication decisions and lessons.

**Facilitator key:** Do not restore over the source before preserving necessary evidence. Revoke or contain the account, validate backup integrity and access, use an isolated recovery path, confirm application compatibility, and reconcile transactions. Compare measured outcomes to approved targets; record deviations and corrective actions. A backup-success notification alone is not restore evidence.

## Exercise 4 — Supplier support access review

**Scenario:** A support SaaS vendor requests a broader administrator role to investigate an intermittent integration failure. The ticket contains customer booking metadata.

**Learner tasks:** Determine whether to grant access and on what basis; minimize data; identify approvals, duration, logging, contract terms, and exit steps; define a supplier-risk review.

**Facilitator key:** Prefer time-bound least-privilege access, a named account, approved scope, monitored session, sanitized ticket data, and post-access revocation. Confirm contractual confidentiality, incident notice, subprocessors, deletion, and assurance. Record the business owner and review date. A vendor certificate does not replace assessment of actual service use and permissions.

## Exercise 5 — Phishing and incident reporting drill

**Scenario:** A support employee receives a simulated message asking them to re-authenticate and open a customer export. A synthetic credential entry is recorded by the training platform.

**Learner tasks:** Practice reporting without blame; identify immediate account-protection steps; determine who receives the alert; define metrics that respect privacy; select targeted follow-up learning.

**Facilitator key:** Measure reporting time and safe handling, not just click rate. Do not collect real passwords. If any real credentials are entered, treat that as a real event and follow the actual response process. Use aggregate results, provide coaching, and verify that the reporting channel reaches a responder.

## Exercise 6 — Internal audit sample tracing

**Scenario:** The auditor is given a fictional access review, a release record, and a restore exercise result. One item lacks an owner approval and another has no period covered.

**Learner tasks:** State audit criteria; assess evidence relevance and limitation; distinguish observation from nonconformity; expand the sample if risk warrants; write a finding with condition, criteria, impact, cause, and action; verify closure independently.

**Facilitator key:** Evidence should be dated, attributable, relevant to the control, and sufficient for the conclusion. An undocumented approval may be a finding where approval is required. Missing period limits the conclusion. Do not infer full-year effectiveness from one sample. Require root cause, accountable owner, due date, and a follow-up sample after correction.

---

Prepared by **Ahmed Ban Harhara**  
[Ahmed.banharhara@gmail.com](mailto:Ahmed.banharhara@gmail.com)  |  [LinkedIn](https://www.linkedin.com/in/ahmed-ban-harhara-285a76264)

